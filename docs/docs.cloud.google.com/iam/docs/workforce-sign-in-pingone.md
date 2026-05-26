---
name: documents/docs.cloud.google.com/iam/docs/workforce-sign-in-pingone
uri: https://docs.cloud.google.com/iam/docs/workforce-sign-in-pingone
title: Configure Workforce Identity Federation with PingOne AIC
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This document shows you how to configure Workforce Identity Federation with PingOne Advanced Identity Cloud (AIC) as an identity provider (IdP) and manage access to Google Cloud. After you configure the PingOne AIC IdP, federated users can access Google Cloud services that [support Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/federated-identity-supported-services) by using the SAML 2.0 protocol.

## Before you begin

Make sure that you set up a Google Cloud organization.

[Install](https://docs.cloud.google.com/sdk/docs/install) the Google Cloud CLI. After installation, [initialize](https://docs.cloud.google.com/sdk/docs/initializing) the Google Cloud CLI by running the following command:

    gcloud init

If you're using an external identity provider (IdP), you must first [sign in to the gcloud CLI with your federated identity](https://docs.cloud.google.com/iam/docs/workforce-log-in-gcloud) .

> **Note:** If you installed the gcloud CLI previously, make sure you have the latest version by running `gcloud components update` .

### Create a hosted IdP

1.  In **Native Consoles \> Access Management** , go to **Realms \> REALM\_NAME \> Dashboard** , and click **SAML Applications** .

2.  Click **Add Entity Provider \> Hosted** .

3.  Enter an **Entity ID** . Record this value for later use.
    
    > **Note:** Advanced Identity Cloud truncates multiple spaces to a single space in values like entity IDs. For example, if **MyEntityID value** (one space) exists, adding a new entity named **My Entity ID** (multiple spaces) causes an error because Advanced Identity Cloud treats them as identical.
    
    1.  Verify that the **Entity Provider Base URL** value is correct. Advanced Identity Cloud uses this value for all SAML 2.0 related endpoints.
    2.  In the **Meta Aliases** section, provide a URL-friendly value in the **Identity Provider Meta Alias** property. This alias must be unique in the circle of trust.
    3.  Click **Create** .
    4.  On the **Assertion Processing** tab, in the **Attribute Mapper** section, map SAML attribute names to local attribute names. The SAML attribute names are the names that are used in an assertion.
    5.  Click **Add** or **Update** for each mapping.
    6.  Click **Save Changes** .

### Use attributes

This section describes how to use attributes from the SAML assertion.

In the following examples, attributes in the SAML assertion are mapped to local attributes:

| SAML attribute | Local attribute |
| -------------- | --------------- |
| `IDPEmail`     | `mail`          |
| `FirstName`    | `givenName`     |
| `groups`       | `groups`        |

Set up the required attributes in the attribute mapping section. You will map these attributes when you create the workforce identity pool provider later in this guide.

### Export provider metadata

You can access the SAML 2.0 metadata for your hosted provider in one of the following ways:

  - **Over REST**
    
    Run the following command:
    
        curl --output METADATA_XML \
            "https://TENANT_ENV_FQDN/am/ExportSamlMetadata?entityid=ENTITY_ID&realm=/REALM"

  - **In a browser**
    
    Open your tenant environment's metadata URL in a browser to download the XML file: ` https:// TENANT_ENV_FQDN /am/ExportSamlMetadata?entityid= ENTITY_ID &realm=/ REALM  `

<!-- end list -->

1.  Save the XML file to your local machine.

### Import Google as a remote SP

1.  Prepare the Google Cloud SP metadata XML. Use the following template, replacing the placeholder values:
    
        <?xml version="1.0" encoding="UTF-8"?>
        <md:EntityDescriptor xmlns:md="urn:oasis:names:tc:SAML:2.0:metadata" xmlns:ds="http://www.w3.org/2000/09/xmldsig#" entityID="https://iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID">
           <md:SPSSODescriptor AuthnRequestsSigned="false" WantAssertionsSigned="true" protocolSupportEnumeration="urn:oasis:names:tc:SAML:2.0:protocol">
              <md:NameIDFormat>urn:oasis:names:tc:SAML:1.1:nameid-format:unspecified</md:NameIDFormat>
              <md:NameIDFormat>urn:oasis:names:tc:SAML:1.1:nameid-format:emailAddress</md:NameIDFormat>
              <md:AssertionConsumerService Binding="urn:oasis:names:tc:SAML:2.0:bindings:HTTP-POST" Location="https://auth.cloud.google/signin-callback/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID" index="0" isDefault="true"/>
           </md:SPSSODescriptor>
        </md:EntityDescriptor>

2.  Import the metadata in one of the following ways:
    
      - **In the console**
        
        1.  In the PingOne AIC admin console, navigate to **SAML Applications** .
        2.  Click **Add Entity Provider \> Remote** .
        3.  Upload the Google Cloud SP metadata XML file you just created.
        4.  Click **Create** .
    
      - **Over REST**
        
        1.  Convert the XML metadata to a base64url-encoded string.
        
        2.  [Get an access token](https://docs.pingidentity.com/pingoneaic/developer-docs/authenticate-to-rest-api-with-access-token.html#get_an_access_token) .
        
        3.  Run the following command:
            
                curl --request POST \
                    --header 'authorization: Bearer ACCESS_TOKEN' \
                    --header 'Content-Type: application/json' \
                    --header 'Accept-API-Version: resource=1.0' \
                    --data-raw '{"standardMetadata": "BASE64URL_ENCODED_METADATA"}' \
                    'https://TENANT_ENV_FQDN/am/json/realms/root/realms/alpha/realm-config/saml2/remote?_action=importEntity'

### Create a circle of trust (CoT)

1.  Navigate to **Realms \> REALM\_NAME \> Applications \> Federation \> Circles of Trust** .
2.  Click **Add Circle of Trust** .
3.  Enter a name and click **Create** .
4.  On the **Circle of Trust** page, in the **Entity Providers** property, select your hosted IdP and the Google Cloud remote SP.
5.  Click **Save Changes** .

## Create the PingOne AIC workforce identity pool provider

This section describes how to create a [workforce identity pool provider](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#workforce-identity-pool-providers) to enable your IdP users to access Google Cloud. You can configure the provider to use the SAML protocol.

### Create a SAML workforce identity pool provider

1.  To create a SAML workforce identity pool provider, you want to ensure that your identity provider metadata includes at least the SAML entity ID, the single sign-on URL, and one signing public key. To do this, follow these steps:
    
    ### gcloud
    
    1.  Save the SAML metadata from your PingOne AIC app.
    
    2.  To create the SAML workforce identity pool provider, run the following command:
        
            gcloud iam workforce-pools providers create-saml WORKFORCE_PROVIDER_ID \
                --workforce-pool="WORKFORCE_POOL_ID" \
                --display-name="DISPLAY_NAME" \
                --description="DESCRIPTION" \
                --idp-metadata-path="XML_METADATA_PATH" \
                --attribute-mapping="ATTRIBUTE_MAPPING" \
                --attribute-condition="ATTRIBUTE_CONDITION" \
                --location=global
        
        Replace the following:
        
          - `  WORKFORCE_PROVIDER_ID  ` : a provider ID.
          - `  WORKFORCE_POOL_ID  ` : the workforce identity pool ID.
          - `  DISPLAY_NAME  ` : a display name.
          - `  DESCRIPTION  ` : a description.
          - `  XML_METADATA_PATH  ` : the path to the XML-formatted metadata file you exported from PingOne AIC.
          - `  ATTRIBUTE_MAPPING  ` : the [attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) ; for example, `google.subject=assertion.subject,google.groups=assertion.attributes.groups,attribute.department=assertion.attributes.department[0]` .
          - `  ATTRIBUTE_CONDITION  ` : an optional [attribute condition](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) ; for example, to limit the `ipaddr` attribute to a certain IP range you can set the condition `assertion.ipaddr.startsWith('98.11.12.')` .
        
        For more information, see [Attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mapping) .
        
        This command assigns the `subject` , `groups` , and `department` in the SAML assertion to `google.subject` , `google.groups` , and `attribute.department` attributes, respectively. The attribute condition also ensures that only users within a certain IP range can sign in using this workforce provider.
    
    ### Console
    
    To configure the SAML provider by using the Google Cloud console, do the following:
    
    1.  In the Google Cloud console, go to the **Workforce Identity Pools** page:
    
    2.  In the **Workforce Identity Pools** table, select the pool for which you want to create the provider.
    
    3.  In the **Providers** section, click **add Add Provider** .
    
    4.  In the **Select a Provider vendor** list, select **Generic Identity Provider** .
    
    5.  In **Select an authentication protocol** , select **SAML** .
    
    6.  In the **Create a provider** section, do the following:
        
        1.  In **Name** , enter a name for the provider.
        2.  Optional: In **Description** , enter a description for the provider.
        3.  In **IDP metadata file (XML)** , select the metadata XML file you exported from PingOne AIC.
        4.  Ensure that **Enabled provider** is enabled.
        5.  Click **Continue** .
    
    7.  In the **Share your provider information** section, click **Continue** .
    
    8.  In the **Configure provider** section, do the following:
        
        1.  In **Attribute mapping** , enter a CEL expression for `google.subject` (for example, `assertion.subject` ).
        
        2.  Optional: To enter other mappings, click **Add mapping** and enter other mappings—for example:
            
                google.subject=assertion.subject,
                google.groups=assertion.attributes['https://example.com/aliases'],
                attribute.costcenter=assertion.attributes.costcenter[0]
        
        3.  Optional: To add an attribute condition, click **Add condition** and enter a CEL expression representing an attribute condition. For example, to limit the `ipaddr` attribute to a certain IP range you can set the condition `assertion.attributes.ipaddr.startsWith('98.11.12.')` . This example condition ensures that only users with an IP address that starts with `98.11.12.` can sign in using this workforce provider.
    
    9.  To turn on detailed audit logging, in **Detailed logging** , click the **Enable attribute value audit logging** toggle.
    
    10. To create the provider, click **Submit** .

## Manage access to Google Cloud resources

This section shows how to manage access to Google Cloud resources for PingOne AIC users.

The sample project used in this guide can be different from the project that you used to set up Workforce Identity Federation.

You can manage roles for single identities, a group of identities, or an entire pool. For more information, see [Represent workforce identity pool users in IAM policies](https://docs.cloud.google.com/iam/docs/configuring-workforce-identity-federation#representing-workforce-users) .

### Use mapped department attributes

To grant the Storage Admin role ( `roles/storage.admin` ) to all identities within a specific department for the `  TEST_PROJECT_ID  ` project, run the following command:

    gcloud projects add-iam-policy-binding TEST_PROJECT_ID \
        --role="roles/storage.admin" \
        --member="principalSet://iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/attribute.department/DEPARTMENT_VALUE"

Replace the following:

  - `  TEST_PROJECT_ID  ` : the project ID.
  - `  WORKFORCE_POOL_ID  ` : the workforce identity pool ID.
  - `  DEPARTMENT_VALUE  ` : the mapped `attribute.department` value.

### Use mapped groups

To grant the Storage Admin role ( `roles/storage.admin` ) to all identities within the `  GROUP_ID  ` group for the `  TEST_PROJECT_ID  ` project, run the following command:

    gcloud projects add-iam-policy-binding TEST_PROJECT_ID \
        --role="roles/storage.admin" \
        --member="principalSet://iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/group/GROUP_ID"

Replace the following:

  - `  TEST_PROJECT_ID  ` : the project ID.
  - `  WORKFORCE_POOL_ID  ` : the workforce identity pool ID.
  - `  GROUP_ID  ` : a group in the mapped `google.groups` claim.

## Sign in and test access

In this section, you sign in as a workforce identity pool user and test your access.

### Sign in

### console (federated) sign-in

To sign in to the Google Cloud Workforce Identity Federation console, also known as the console (federated), do the following:

1.  Go to the console (federated) sign-in page.

2.  Enter the provider name, which is formatted as follows:
    
        locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID

### Google Cloud CLI browser-based sign-in

To sign in to gcloud CLI using a browser-based sign-in flow:

To create the login configuration file, run the following command. You can optionally activate the file as the default for the gcloud CLI by adding the [`--activate` flag](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/create-login-config) . You can then run `gcloud auth login` without specifying the configuration file path each time.

    gcloud iam workforce-pools create-login-config \
        locations/global/workforcePools/WORKFORCE_POOL_ID/providers/PROVIDER_ID \
        --output-file=LOGIN_CONFIG_FILE_PATH

Replace the following:

  - `  WORKFORCE_POOL_ID  ` : the workforce pool ID
  - `  PROVIDER_ID  ` : the provider ID
  - `  LOGIN_CONFIG_FILE_PATH  ` : the path to a configuration file that you specify—for example, `login.json`

The file contains the endpoints used by the gcloud CLI to enable the browser-based authentication flow and set the audience to the IdP that was configured in the workforce identity pool provider. The file doesn't contain confidential information.

The output looks similar to the following:

    {
      "type": "external_account_authorized_user_login_config",
      "audience": "//iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID",
      "auth_url": "https://auth.cloud.google/authorize",
      "token_url": "https://sts.googleapis.com/v1/oauthtoken",
      "token_info_url": "https://sts.googleapis.com/v1/introspect"
    }

> **Caution:** We recommend that you first ensure that the contents of this file are correct and then safeguard the file—for example, by making it read-only and restricting access with an ACL. The file isn't validated; a malicious actor with write access to this file can change the endpoints and intercept credentials.

To stop `gcloud auth login` from using this configuration file automatically, you can unset it by running `gcloud config unset auth/login_config_file` .

To authenticate using browser-based sign-in authentication, you can use one of the following methods:

  - If you used the `--activate` flag when you created the configuration file, or if you activated the configuration file with `gcloud config set auth/login_config_file` , the gcloud CLI uses your configuration file automatically:
    
        gcloud auth login

  - To sign in by specifying the location of the configuration file, run the following command:
    
        gcloud auth login --login-config=LOGIN_CONFIG_FILE_PATH

  - To use an environment variable to specify the location of the configuration file, set `CLOUDSDK_AUTH_LOGIN_CONFIG_FILE` to the configuration path.

To discontinue using the login configuration file, do the following:

  - If you used the `--activate` flag when you created the configuration file, or if you activated the configuration file with `gcloud config set auth/login_config_file` , you must run the following command to unset it:
    
        gcloud config unset auth/login_config_file

  - Clear the `CLOUDSDK_AUTH_LOGIN_CONFIG_FILE` environment variable, if it is set.

### gcloud CLI headless sign-in

To sign in to PingOne AIC with the gcloud CLI using the SAML protocol, do the following:

1.  Sign in a user to your PingOne AIC application and get the SAML response.

2.  Save the SAML response returned by PingOne AIC in a secure location on your local machine. Store the path in an environment variable—for example: `SAML_ASSERTION_PATH=/tmp/saml_assertion.xml` .

3.  Generate a configuration file:
    
        gcloud iam workforce-pools create-cred-config \
            locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID \
            --subject-token-type=urn:ietf:params:oauth:token-type:saml2 \
            --credential-source-file=SAML_ASSERTION_PATH \
            --workforce-pool-user-project=PROJECT_ID \
            --output-file=config.json
    
    Replace the following:
    
      - `  SAML_ASSERTION_PATH  ` : the path of the SAML assertion file.
      - `  PROJECT_ID  ` : the project ID.

4.  The configuration file that's generated looks similar to the following:
    
        {
          "type": "external_account",
          "audience": "//iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID",
          "subject_token_type": "urn:ietf:params:oauth:token-type:saml2",
          "token_url": "https://sts.googleapis.com/v1/token",
          "credential_source": {
            "file": "SAML_ASSERTION_PATH"
          },
          "workforce_pool_user_project": "PROJECT_ID"
        }

5.  To sign in to the gcloud CLI using token exchange, run the following command:
    
        gcloud auth login --cred-file=config.json
    
    `gcloud` then transparently exchanges your PingOne AIC credentials for temporary Google Cloud access tokens, allowing you to make other `gcloud` calls to Google Cloud. The output is similar to the following:
    
    `Authenticated with external account user credentials for: [principal://iam.googleapis.com/locations/global/workforcePools/ WORKFORCE_POOL_ID /subject/ USER_ID ].`

6.  To list the credentialed accounts and the active account, run the following command:
    
        gcloud auth list

### Test access

You can access the Google Cloud services that support Workforce Identity Federation that you're granted access to. Earlier in this guide, you granted the Storage Admin role to all identities within a specific department or group for project `  TEST_PROJECT_ID  ` . You can test that you have access by listing Cloud Storage buckets.

### console (federated) sign-in

To verify your access in the console (federated), do the following:

1.  Go to the [Cloud Storage](https://console.cloud.google.com/storage) page.
2.  Verify that you can see the list of existing buckets for the project `  TEST_PROJECT_ID  ` .

### gcloud CLI

To list Cloud Storage buckets and objects for the project that you have access to, run the following command:

    gcloud alpha storage ls --project="TEST_PROJECT_ID"

The principal must have the `serviceusage.services.use` permission on the project set in the gcloud CLI session: `  PROJECT_ID  ` .

## What's next

  - [Delete Workforce Identity Federation users and their data](https://docs.cloud.google.com/iam/docs/workforce-delete-user-data) .
  - Learn which Google Cloud products [support Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/federated-identity-supported-services) .
  - [Set up user access to console (federated)](https://docs.cloud.google.com/iam/docs/workforce-console-sso) .
