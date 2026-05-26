---
name: documents/docs.cloud.google.com/iam/docs/workforce-sign-in-okta
uri: https://docs.cloud.google.com/iam/docs/workforce-sign-in-okta
title: Configure Workforce Identity Federation with Okta and sign in users
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This guide shows you how configure Workforce Identity Federation using Okta as an identity provider (IdP), manage access, and sign in users to access Google Cloud services that [support Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/federated-identity-supported-services) .

## Before you begin

1.  Make sure that you have a Google Cloud organization set up.

2.  [Install](https://docs.cloud.google.com/sdk/docs/install) the Google Cloud CLI. After installation, [initialize](https://docs.cloud.google.com/sdk/docs/initializing) the Google Cloud CLI by running the following command:
    
        gcloud init
    
    If you're using an external identity provider (IdP), you must first [sign in to the gcloud CLI with your federated identity](https://docs.cloud.google.com/iam/docs/workforce-log-in-gcloud) .
    
    > **Note:** If you installed the gcloud CLI previously, make sure you have the latest version by running `gcloud components update` .

3.  For sign-in, your IdP must provide signed authentication information: OIDC IdPs must provide a JWT, and SAML IdP responses must be signed.

4.  To receive important information about changes to your organization or Google Cloud products, you must provide [Essential Contacts](https://docs.cloud.google.com/resource-manager/docs/managing-notification-contacts) . For more information, see the [Workforce Identity Federation overview](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#essential-contacts) .

## Costs

Workforce Identity Federation is available as a no-cost feature. However, Workforce Identity Federation detailed audit logging uses Cloud Logging. To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .

## Required roles

To get the permissions that you need to configure Workforce Identity Federation, ask your administrator to grant you the [IAM Workforce Pool Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin) ( `roles/iam.workforcePoolAdmin` ) IAM role on the organization. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

You might also be able to get the required permissions through [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

Alternatively, the IAM Owner ( `roles/owner` ) basic role also includes permissions to configure Workforce Identity Federation. You should not grant basic roles in a production environment, but you can grant them in a development or test environment.

## Create a workforce identity pool

### gcloud

To create the workforce identity pool, run the following command:

    gcloud iam workforce-pools create WORKFORCE_POOL_ID \
        --organization=ORGANIZATION_ID \
        --display-name="DISPLAY_NAME" \
        --description="DESCRIPTION" \
        --session-duration=SESSION_DURATION \
        --location=global

Replace the following:

  - `  WORKFORCE_POOL_ID  ` : an ID that you choose to represent your Google Cloud workforce pool. The pool ID must be globally unique across all workforce identity pools in Google Cloud. For information on formatting the ID, see the [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create#query-parameters) section in the API documentation.
  - `  ORGANIZATION_ID  ` : the numeric organization ID of your Google Cloud organization for the workforce identity pool. Workforce identity pools are available across all projects and folders in the organization.
  - `  DISPLAY_NAME  ` : Optional. A display name for your workforce identity pool.
  - `  DESCRIPTION  ` : Optional. A workforce identity pool description.
  - `  SESSION_DURATION  ` : Optional. The session duration, expressed as a number appended with `s` —for example, `3600s` . Session duration determines how long the Google Cloud access tokens, [console (federated)](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#console-federated) sign-in sessions, and gcloud CLI sign-in sessions from this workforce pool are valid. Session duration defaults to one hour (3600s). The session duration value must be between 15 minutes (900s) and 12 hours (43200s).

> **Tip:** Run `gcloud iam workforce-pools create --help` to find other parameters you can customize for this command.

### Console

To create the workforce identity pool, do the following:

1.  In the Google Cloud console, go to the **Workforce Identity Pools** page:

2.  Select the organization for your workforce identity pool. Workforce identity pools are available across all projects and folders in an organization.

3.  Click **Create pool** and do the following:
    
    1.  In the **Name** field, enter the display name of the pool. The pool ID is automatically derived from the name as you type, and it is displayed under the **Name** field. You can update the pool ID by clicking **Edit** next to the pool ID.
    
    2.  Optional: In **Description** , enter a description of the pool.
    
    3.  To create the workforce identity pool, click **Next** .

The workforce identity pool's session duration defaults to one hour (3600s). The session duration determines how long the Google Cloud access tokens, [console (federated)](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#console-federated) , and gcloud CLI sign-in sessions from this workforce pool are valid. After you create the pool, you can [update the pool](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-pool) to set a custom session duration. The session duration must be from 15 minutes (900s) to 12 hours (43200s).

## Create an Okta app integration

This section provides the steps to create an Okta app integration using the Okta Admin Console. For additional details, see [Create custom app integrations](https://help.okta.com/en/prod/Content/Topics/Apps/Apps_App_Integration_Wizard.htm) .

> **Note:** In this guide, you create a custom attribute called `department` to demonstrate attribute mapping. This task is for illustrative purposes only.

Workforce identity pools support federation using both OIDC and SAML protocols.

For more details, see the integration documentation for [OIDC](https://help.okta.com/en/prod/Content/Topics/Apps/Apps_App_Integration_Wizard_OIDC.htm) and [SAML](https://help.okta.com/en/prod/Content/Topics/Apps/Apps_App_Integration_Wizard_SAML.htm) . The basic configuration is described in this section.

### OIDC using App Catalog

To create an Okta app integration from the App Catalog using the OIDC protocol, perform the following steps:

> **Important:** By default, an Okta application created from the App Catalog sends up to 100 groups. If you expect that your number of groups will exceed 100, consider a non-App-Catalog application.

1.  Sign in to the **Okta Admin Console** .

2.  Go to **Applications \> Applications** .

3.  Click **Browse App Catalog** .

4.  In the **Search** field, enter **Google Cloud Workforce Identity Federation** , and then select **Google Cloud Workforce Identity Federation integration** from the results.

5.  Click **Add Integration** .

6.  In the **Application label** field, enter a name for your app.

7.  In the **Workforce Pool** field, enter the workforce pool name obtained from gcloud CLI.

8.  In the **Provider** field, enter a name for the provider.
    
    > **Important:** Later in this document, when you create the workforce identity pool provider, you must use the same workforce identity provider ID that you used here.

9.  Click **Next** .

10. Select the **OpenID Connect** option.

11. Click **Done** .

### OIDC

To create an Okta app integration that uses the OIDC protocol, perform the following steps:

1.  Sign in to the Okta Admin Console.

2.  Go to **Applications \> Applications** .

3.  To begin configuring the app integration, do the following:
    
    1.  Click **Create App Integration** .
    
    2.  In **Sign-in method** , select **OIDC - OpenID Connect** .
    
    3.  In **Application type** , select an application type; for example, **Web Application** .
    
    4.  To create the app, click **Next** .
    
    5.  In **App integration name** , enter a name for your app.
    
    6.  In the **Grant type** section, select the **Implicit (hybrid)** checkbox.
    
    7.  In the **Sign-in redirect URIs** section, in the text field, enter a redirect URL. Your users are redirected to this URL after they successfully sign in. If you are configuring access to the [console (federated)](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#google_cloud_workforce_identity_federation_console) , use the following URL format:
        
            https://auth.cloud.google/signin-callback/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID
        
        Replace the following:
        
          - `  WORKFORCE_POOL_ID  ` : the ID of the workforce pool that you created earlier in this guide.
          - `  WORKFORCE_PROVIDER_ID  ` : a workforce identity provider ID of your choice; for example: `okta-oidc-provider` . For information on formatting the ID, see the [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create#query-parameters) section in the API documentation.
        
        > **Important:** Later in this document, when you create the workforce identity pool provider, you must use the same workforce identity provider ID that you used here.
    
    8.  Select the **Skip group assignment for now** checkbox.
    
    9.  To save the app integration, click **Save** .

4.  [Assign an app integration to a user](https://help.okta.com/en-us/Content/Topics/Provisioning/lcm/lcm-assign-app-user.htm) .

5.  Optional: To add custom attributes for an Okta user profile, do the following:
    
    1.  In **Data Type** , select `string` .
    2.  In **Display name** , enter `Department` .
    3.  In **Variable name** , enter `department` .
    4.  To save the mapping, click **Save** .
    
    To learn more about adding custom attributes, see [Add custom attributes to an Okta user profile](https://help.okta.com/en-us/Content/Topics/users-groups-profiles/usgp-add-custom-user-attributes.htm) .

6.  Optional: To create mappings for the attributes that are sent in the OIDC token, in **Directory** , click **Profile Editor** , and do the following:
    
    1.  Find the OIDC application that you created earlier in this guide.
    2.  Click **Mappings** .
    3.  Select the **Okta User to App** tab.
    4.  In the **Okta User User Profile** tab, in an available combo box, enter `department` . Okta auto-completes to `user.department` .
    5.  To save the mappings, click **Save Mappings** . For more details, refer to [Add attribute mapping](https://help.okta.com/en-us/Content/Topics/users-groups-profiles/usgp-map-attributes.htm) .
    
    To learn more about mappings, see refer to [Map Okta attributes to app attributes in the Profile Editor](https://help.okta.com/en-us/Content/Topics/users-groups-profiles/usgp-map-attributes.htm) .

7.  Optional: To configure a groups claim, do the following:
    
    1.  If you use an org authorization server, do the following:
        
        1.  Go to **Applications** \> **Applications**
        
        2.  Select the OpenID Connect client application that you created earlier in this section.
        
        3.  Go to the **Sign On** tab
        
        4.  In the **OpenID Connect ID Token** section, click **Edit** .
        
        5.  In the **Groups claim type** section, you can select either of the following options:
            
              - Select **Expression** .
              - Select **Matches regex** and enter `.*` .
        
        6.  To save the groups claim, click **Save** .
        
        7.  If you want users to sign in using the console (federated) or gcloud CLI browser-based sign-in flow, do the following when you create your workforce identity pool provider, later in this document:
            
            1.  Make sure to use the gcloud CLI instructions so that you can use the `--web-sso-additional-scopes` flag.
            
            2.  When you create the workforce identity pool provider, pass `groups` as an additional scope in `--web-sso-additional-scopes` . Doing so requests the groups claim from Okta during sign-in.
    
    2.  If you use a Custom Authorization Server, do the following:
        
        1.  In the Admin Console, from the **Security** menu, select **API** .
        2.  Select the custom authorization server that you want to configure.
        3.  Go to the **Claims** tab and click **Add Claim** .
        4.  Enter a name for the claim. For this example, name it `groups` .
        5.  In your claim, in **Include in token type** , select **ID Token** and select **Always** .
        6.  Select **Groups** as the **Value type** .
        7.  In the Filter drop-down box, select **Matches regex** and then enter the following expression as the Value: `.*`
        8.  Click **Create** .

For more details on groups claims, refer to [Add a Groups claim](https://developer.okta.com/docs/guides/customize-tokens-groups-claim/main/) .

### SAML

To create an Okta app integration that uses the SAML protocol, perform the following steps:

1.  Sign in to the Okta Admin Console.

2.  Go to **Applications \> Applications** .

3.  Click **Browse App Catalog** .

4.  In the **Search** field, enter **Google Cloud Workforce Identity Federation** , and then select **Google Cloud Workforce Identity Federation integration** from the results.

5.  Click **Add Integration** .

6.  In the **Application label** field, enter a name for your app.

7.  In the **Workforce Pool** field, enter the workforce pool name obtained from gcloud CLI.

8.  In the **Provider** field, enter a name for the provider.
    
    > **Important:** Later in this document, when you create the workforce identity pool provider, you must use the same workforce identity provider ID that you used here.

9.  Click **Next** .

10. Optional: To access application through IDP-initiated sign-in flow using **Embed Link** , enter `https://console.cloud.google/` in **Default Relay State** .

11. Optional: To specify any custom attributes that you want to send in the SAML assertion, expand the **Attributes(Optional)** section. After setup, these attributes can be used in Google Cloud to create access management policies or in the [attribute\_condition](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) ;
    
      - In the **Name** field, enter an attribute name.
      - From the **Name format** list, select an option.
      - From the **Value** list, select an attribute value.

12. Optional: In the **user.getGroups** field, select an option such as **Starts with** .
    
      - Provide a condition that matches the option that you selected in the **Value** field. To receive all groups, enter " **.\*** ".

13. Download the content from the displayed **Metadata URL** into a local file. You will upload it to Google Cloud console.

14. Click **Done** to finish creating the application.

## Create a workforce identity pool provider

This section describes how to create a [workforce identity pool provider](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#workforce-identity-pool-providers) to enable your IdP users to access Google Cloud. You can configure the provider to use either the OIDC or SAML protocol.

### Create an OIDC workforce identity pool provider

To create a workforce identity pool provider for your Okta app integration, using the OIDC protocol, do the following:

1.  To get the client ID for your Okta app integration, do the following:
    
    1.  Go to your Okta app integration.
    2.  Click the **General** tab.
    3.  Copy the contents of the **Client ID** field.

2.  To create an OIDC workforce identity pool provider for web-based sign-in, do the following:
    
    ### gcloud
    
    ### Code flow
    
    In Okta, do the following:
    
    1.  In **Client authentication** , select **Client secret** .
    
    2.  In the **Client Secrets** table, locate the secret and click *content\_copy* **Copy** .
    
    In Google Cloud, to create an OIDC provider that uses [authorization code flow](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#oidc-flow-types) for web sign-in, run the following command:
    
        gcloud iam workforce-pools providers create-oidc WORKFORCE_PROVIDER_ID \
            --workforce-pool=WORKFORCE_POOL_ID \
            --display-name="DISPLAY_NAME" \
            --description="DESCRIPTION" \
            --issuer-uri="ISSUER_URI" \
            --client-id="OIDC_CLIENT_ID" \
            --client-secret-value="OIDC_CLIENT_SECRET" \
            --web-sso-response-type="code" \
            --web-sso-assertion-claims-behavior="merge-user-info-over-id-token-claims" \
            --web-sso-additional-scopes="WEB_SSO_ADDITIONAL_SCOPES" \
            --attribute-mapping="ATTRIBUTE_MAPPING" \
            --attribute-condition="ATTRIBUTE_CONDITION" \
            --jwk-json-path="JWK_JSON_PATH" \
            --detailed-audit-logging \
            --location=global
    
    Replace the following:
    
      - `  WORKFORCE_PROVIDER_ID  ` : A unique workforce identity pool provider ID. The prefix `gcp-` is reserved and can't be used in a workforce identity pool or workforce identity pool provider ID.
    
      - `  WORKFORCE_POOL_ID  ` : The workforce identity pool ID to connect your IdP to.
    
      - `  DISPLAY_NAME  ` : An optional user-friendly display name for the provider; for example, `idp-eu-employees` .
    
      - `  DESCRIPTION  ` : An optional workforce provider description; for example, `IdP for Partner Example Organization employees` .
    
      - `  ISSUER_URI  ` : The OIDC issuer URI, in a valid URI format, that starts with `https` ; for example, `https://example.com/oidc` . Note: For security reasons, `  ISSUER_URI  ` must use the HTTPS scheme.
    
      - `  OIDC_CLIENT_ID  ` : The OIDC client ID that is registered with your OIDC IdP; the ID must match the `aud` claim of the JWT that is issued by your IdP.
    
      - `  OIDC_CLIENT_SECRET  ` : The OIDC client secret.
    
      - `  WEB_SSO_ADDITIONAL_SCOPES  ` : Optional additional scopes to send to the OIDC IdP for console (federated) or gcloud CLI browser-based sign-in; for example, `groups` to request the groups claim from Okta if using Okta's org authorization server.
    
      - `  ATTRIBUTE_MAPPING  ` : An [attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) . The following is an example of an attribute mapping:
        
            google.subject=assertion.oid
            google.groups=assertion.groups,
            attribute.costcenter=assertion.costcenter
        
        This example maps the IdP attributes `assertion.oid` , `assertion.groups` , and `assertion.costcenter` in the OIDC assertion to the Google Cloud attributes `google.subject` , `google.groups` , and `attribute.costcenter` , respectively.
    
      - `  ATTRIBUTE_CONDITION  ` : An [attribute condition](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) ; for example, `assertion.subject.endsWith('@example.com')` when the value of `subject` mapped earlier contains an email address that ends with `@example.com` .
        
        > **Warning:** If your multi-tenant IdP has a single issuer URI, you must use [attribute conditions](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) to ensure that access is restricted to the correct tenant. For more information, see [Use attribute conditions when federating with GitHub or other multi-tenant identity providers](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#use-attribute-conditions-multitenant) .
    
      - `  JWK_JSON_PATH  ` : An optional path to a [locally uploaded OIDC JWKs](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#json-web-keys) . If this parameter isn't supplied, Google Cloud instead uses your IdP's `/.well-known/openid-configuration` path to source the JWKs containing the public keys. For more information about locally uploaded OIDC JWKs, see [manage OIDC JWKs](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#manage-oidc-keys) .
        
        > **Note:** Local OIDC JWKs can be uploaded through [implicit flow or code flow](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#oidc-flow-types) , but can only be used in [programmatic flow](https://docs.cloud.google.com/iam/docs/workforce-obtaining-short-lived-credentials) , in which you directly call the STS `/token` endpoint with a credential from the third-party IdP to exchange for a Google Cloud access token for your workforce pool. You can't use local OIDC JWKs when signing in to the console (federated).
    
      - Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
        
        To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .
    
    In the command response, POOL\_RESOURCE\_NAME is the name of the pool; for example, `locations/global/workforcePools/enterprise-example-organization-employees` .
    
    ### Implicit flow
    
    To create an OIDC provider that uses the [implicit flow](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#oidc-flow-types) for web sign-in, run the following command:
    
        gcloud iam workforce-pools providers create-oidc WORKFORCE_PROVIDER_ID \
            --workforce-pool=WORKFORCE_POOL_ID \
            --display-name="DISPLAY_NAME" \
            --description="DESCRIPTION" \
            --issuer-uri="ISSUER_URI" \
            --client-id="OIDC_CLIENT_ID" \
            --web-sso-response-type="id-token" \
            --web-sso-assertion-claims-behavior="only-id-token-claims" \
            --web-sso-additional-scopes="WEB_SSO_ADDITIONAL_SCOPES" \
            --attribute-mapping="ATTRIBUTE_MAPPING" \
            --attribute-condition="ATTRIBUTE_CONDITION" \
            --jwk-json-path="JWK_JSON_PATH" \
            --detailed-audit-logging \
            --location=global
    
    Replace the following:
    
      - `  WORKFORCE_PROVIDER_ID  ` : A unique workforce identity pool provider ID. The prefix `gcp-` is reserved and can't be used in a workforce identity pool or workforce identity pool provider ID.
    
      - `  WORKFORCE_POOL_ID  ` : The workforce identity pool ID to connect your IdP to.
    
      - `  DISPLAY_NAME  ` : An optional user-friendly display name for the provider; for example, `idp-eu-employees` .
    
      - `  DESCRIPTION  ` : An optional workforce provider description; for example, `IdP for Partner Example Organization employees` .
    
      - `  ISSUER_URI  ` : The OIDC issuer URI, in a valid URI format, that starts with `https` ; for example, `https://example.com/oidc` . Note: For security reasons, `  ISSUER_URI  ` must use the HTTPS scheme.
    
      - `  OIDC_CLIENT_ID  ` : The OIDC client ID that is registered with your OIDC IdP; the ID must match the `aud` claim of the JWT that is issued by your IdP.
    
      - `  WEB_SSO_ADDITIONAL_SCOPES  ` : Optional additional scopes to send to the OIDC IdP for console (federated) or gcloud CLI browser-based sign-in; for example, `groups` to request the groups claim from Okta if using Okta's org authorization server.
    
      - `  ATTRIBUTE_MAPPING  ` : An [attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) . The following is an example of an attribute mapping:
        
            google.subject=assertion.oid
            google.groups=assertion.groups,
            attribute.costcenter=assertion.costcenter
        
        This example maps the IdP attributes `assertion.oid` , `assertion.groups` , and `assertion.costcenter` in the OIDC assertion to the Google Cloud attributes `google.subject` , `google.groups` , and `attribute.costcenter` , respectively.
    
      - `  ATTRIBUTE_CONDITION  ` : An [attribute condition](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) ; for example, `assertion.subject.endsWith('@example.com')` when the value of `subject` mapped earlier contains an email address that ends with `@example.com` .
        
        > **Warning:** If your multi-tenant IdP has a single issuer URI, you must use [attribute conditions](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) to ensure that access is restricted to the correct tenant. For more information, see [Use attribute conditions when federating with GitHub or other multi-tenant identity providers](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#use-attribute-conditions-multitenant) .
    
      - `  JWK_JSON_PATH  ` : An optional path to a [locally uploaded OIDC JWKs](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#json-web-keys) . If this parameter isn't supplied, Google Cloud instead uses your IdP's `/.well-known/openid-configuration` path to source the JWKs containing the public keys. For more information about locally uploaded OIDC JWKs, see [manage OIDC JWKs](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#manage-oidc-keys) .
        
        > **Note:** Local OIDC JWKs can be uploaded through [implicit flow or code flow](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#oidc-flow-types) , but can only be used in [programmatic flow](https://docs.cloud.google.com/iam/docs/workforce-obtaining-short-lived-credentials) , in which you directly call the STS `/token` endpoint with a credential from the third-party IdP to exchange for a Google Cloud access token for your workforce pool. You can't use local OIDC JWKs when signing in to the console (federated).
    
      - Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
        
        To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .
    
    In the command response, POOL\_RESOURCE\_NAME is the name of the pool; for example, `locations/global/workforcePools/enterprise-example-organization-employees` .
    
    ### Console
    
    ### Code flow
    
    1.  In Okta, do the following:
        
        1.  In **Client authentication** , select **Client secret** .
        
        2.  In the **Client Secrets** table, locate the secret and click *content\_copy* **Copy** .
    
    2.  In the Google Cloud console, to create an OIDC provider that uses [authorization code flow](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#oidc-flow-types) , do the following:
        
        1.  In the Google Cloud console, go to the **Workforce Identity Pools** page:
        
        2.  In the **Workforce Identity Pools** table, select the pool for which you want to create the provider.
        
        3.  In the **Providers** section, click **add Add Provider** .
        
        4.  In the **Select a Provider vendor** list, select your IdP.
            
            If your IdP isn't listed, then select **Generic Identity Provider** .
        
        5.  In **Select an authentication protocol** , select **OpenID Connect (OIDC)** .
        
        6.  In the **Create a provider** section, do the following:
            
            1.  In **Name** , enter the name for the provider.
            2.  In **Description** , enter the description for the provider.
            3.  In **Issuer (URL)** , enter the issuer URI. The OIDC issuer URI must be in a valid URI format and start with `https` ; for example, `https://example.com/oidc` .
            4.  In **Client ID** , enter the OIDC client ID that is registered with your OIDC IdP; the ID must match the `aud` claim of the JWT that is issued by your IdP.
            5.  To create a provider that is enabled, make sure **Enable provider** is on.
            6.  Click **Continue** .
        
        7.  In the **Share your provider information with IdP** section, copy the URL. In your IdP, configure this URL as the redirect URI, which informs your IdP where to send the assertion token after logging in.
        
        8.  Click **Continue** .
        
        9.  In the **Configure OIDC Web Sign-in** section, do the following:
            
            1.  In the **Flow type** list, select **Code** .
            2.  In the **Assertion claims behavior** list, select either of the following:
                  - **User info and ID token**
                  - **Only ID token**
            3.  In the **Client secret** field, enter the client secret from your IdP.
            4.  Optional: If you selected **Okta** as your IdP, add any extra OIDC scopes in the **Additional scopes beyond openid, profile, and email** field.
        
        10. Click **Continue** .
        
        11. In **Configure provider** , you can configure an attribute mapping and an attribute condition. To create an [attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) , do the following. You can provide either the IdP field name or a [CEL-formatted](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) expression that returns a string.
            
            1.  Required: In **OIDC 1** , enter the subject from the IdP— for example, `assertion.sub` .
            
            2.  Optional: To add additional attribute mappings, do the following:
                
                1.  Click **Add mapping** .
                2.  In **Google *n*** , where *n* is a number, enter one of the [Google Cloud-supported keys](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) .
                3.  In the corresponding **OIDC *n*** field, enter the name of the IdP-specific field to map, in CEL format.
            
            3.  To create an attribute condition, do the following:
                
                > **Warning:** If your multi-tenant IdP has a single issuer URI, you must use [attribute conditions](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) to ensure that access is restricted to the correct tenant. For more information, see [Use attribute conditions when federating with GitHub or other multi-tenant identity providers](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#use-attribute-conditions-multitenant) .
                
                1.  Click **Add condition** .
                2.  In the **Attribute Conditions** field, enter a condition in [CEL format](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) ; for example, `assertion.subject.endsWith('@example.com')` when the value of `subject` mapped earlier contains an email address that ends with `@example.com` .
            
            4.  To turn on detailed audit logging, in **Detailed logging** , click the **Enable attribute value audit logging** toggle.
                
                Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
                
                To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .
        
        12. To create the provider, click **Submit** .
    
    ### Implicit flow
    
    1.  In the Google Cloud Google Cloud console, do the following:
        
        1.  In the Google Cloud console, go to the **Workforce Identity Pools** page:
        
        2.  In the **Workforce Identity Pools** table, select the pool for which you want to create the provider.
        
        3.  In the **Providers** section, click **add Add Provider** .
        
        4.  In the **Select a Provider vendor** list, select your IdP.
            
            If your IdP isn't listed, then select **Generic Identity Provider** .
        
        5.  In **Select an authentication protocol** , select **OpenID Connect (OIDC)** .
        
        6.  In the **Create a provider** section, do the following:
            
            1.  In **Name** , enter the name for the provider.
            2.  In **Description** , enter the description for the provider.
            3.  In **Issuer (URL)** , enter the issuer URI. The OIDC issuer URI must be in a valid URI format and start with `https` ; for example, `https://example.com/oidc` .
            4.  In **Client ID** , enter the OIDC client ID that is registered with your OIDC IdP; the ID must match the `aud` claim of the JWT that is issued by your IdP.
            5.  To create a provider that is enabled, make sure **Enable provider** is on.
            6.  Click **Continue** .
        
        7.  In the **Share your provider information with IdP** section, copy the URL. In your IdP, configure this url as the redirect URI, which informs your IdP where to send the assertion token after logging in.
        
        8.  Click **Continue** .
        
        9.  In the **Configure OIDC Web Sign-in** section, do the following:
            
            1.  In the **Flow type** list, select **ID Token** .
            2.  In the **Assertion claims behavior** list, **ID token** is selected.
            3.  Optional: If you selected **Okta** as your IdP, add any extra OIDC scopes in the **Additional scopes beyond openid, profile, and email** field.
        
        10. Click **Continue** .
        
        11. In **Configure provider** , you can configure an attribute mapping and an attribute condition. To create an [attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) , do the following. You can provide either the IdP field name or a [CEL-formatted](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) expression that returns a string.
            
            1.  Required: In **OIDC 1** , enter the subject from the IdP; for example, `assertion.sub` .
            
            2.  Optional: To add additional attribute mappings, do the following:
                
                1.  Click **Add mapping** .
                2.  In **Google *n*** , where *n* is a number, enter one of the [Google Cloud-supported keys](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) .
                3.  In the corresponding **OIDC *n*** field, enter the name of the IdP-specific field to map, in CEL format.
            
            3.  To create an attribute condition, do the following:
                
                > **Warning:** If your multi-tenant IdP has a single issuer URI, you must use [attribute conditions](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) to ensure that access is restricted to the correct tenant. For more information, see [Use attribute conditions when federating with GitHub or other multi-tenant identity providers](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#use-attribute-conditions-multitenant) .
                
                1.  Click **Add condition** .
                2.  In the **Attribute Conditions** field, enter a condition in [CEL format](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) ; for example, `assertion.subject.endsWith('@example.com')` when the value of `subject` mapped earlier contains an email address that ends with `@example.com` .
            
            4.  To turn on detailed audit logging, in **Detailed logging** , click the **Enable attribute value audit logging** toggle.
                
                Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
                
                To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .
        
        12. To create the provider, click **Submit** .

### Create a SAML workforce identity pool provider

1.  In your SAML IdP, register a new application for Google Cloud Workforce Identity Federation.

2.  Set the audience for SAML assertions. It is usually the `SP Entity ID` field in your IdP configuration. You must set it to the following URL:
    
        https://iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID

3.  Set the redirect URL, also known as the Assertion Consumer Service (ACS) URL. To set the redirect URL, locate the redirect URL field in your SAML IdP, and do one of the following:
    
      - To set up browser-based sign-in through the Google Cloud console or another browser-based sign-in method, enter following URL:
        
            https://auth.cloud.google/signin-callback/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID
        
        Replace the following:
        
          - `  WORKFORCE_POOL_ID  ` : the workforce identity pool ID
        
          - `  WORKFORCE_PROVIDER_ID  ` : the ID of the workforce identity pool provider that you create later in this document.
    
      - To set up programmatic sign-in through your IdP, enter the following URL:
        
            localhost
    
    See [Set up user access to the console](https://docs.cloud.google.com/iam/docs/workforce-console-sso) for more details on configuring console sign-in.

4.  In Google Cloud, create a SAML workforce identity pool provider using your IdP's SAML metadata document. You can download the SAML metadata XML document from your IdP. The document must include at least the following:
    
      - A SAML entity ID for your IdP.
      - The single-sign-on URL for your IdP.
      - At least one signing public key. See [Key requirements](https://docs.cloud.google.com/iam/docs/workforce-sign-in-okta#key-requirements) later in this guide for details on signing keys.

### gcloud

To create a workforce identity pool provider for your Okta app integration, using the SAML protocol, do the following:

To save the SAML metadata for your Okta app, do the following:

1.  Go to your Okta App.
2.  Click the **Sign On** tab.
3.  In the **SAML Signing Certificates** section, click **Actions \> View IdP metadata** for the active certificate.
4.  In the new page that opens, copy the XML metadata.
5.  Save the metadata as a local XML file.

To create a workforce provider for your Okta app, run the following command:

    gcloud iam workforce-pools providers create-saml WORKFORCE_PROVIDER_ID \
        --workforce-pool="WORKFORCE_POOL_ID" \
        --attribute-mapping="ATTRIBUTE_MAPPING" \
        --attribute-condition="ATTRIBUTE_CONDITION" \
        --idp-metadata-path="XML_METADATA_PATH" \
        --detailed-audit-logging \
        --location="global"

Replace the following:

  - `  WORKFORCE_PROVIDER_ID  ` : The workforce provider ID that you created earlier in this guide.

  - `  WORKFORCE_POOL_ID  ` : The workforce identity pool ID that you created earlier in this guide.

  - `  ATTRIBUTE_MAPPING  ` : An [attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) —for example:
    
        google.subject=assertion.oid
        attribute.costcenter=assertion.attributes.costcenter[0]
    
    This example maps the IdP attributes `assertion.oid` and `assertion.attributes.costcenter[0]` to the Google Cloud attributes `google.subject` and `attribute.costcenter` , respectively.

  - `  ATTRIBUTE_CONDITION  ` : An optional [attribute condition](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) . For example, to limit the `ipaddr` attribute to a certain IP range you can set the condition `assertion.attributes.ipaddr.startsWith('98.11.12.')` . This example condition ensures that only users with an IP address that starts with `98.11.12.` can sign in using this workforce provider.

  - `  XML_METADATA_PATH  ` : The path to the XML-formatted metadata file for the Okta App that you created earlier in this guide.

The prefix `gcp-` is reserved and can't be used in a workforce identity pool or workforce identity pool provider ID.

  - Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
    
    To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .

### Optional: Accept encrypted SAML assertions from your IdP

To enable your SAML 2.0 IdP to produce encrypted SAML assertions that can be accepted by workforce identity federation, do the following:

In workforce identity federation, do the following:

  - Create an asymmetric key pair for your workforce identity pool provider.
  - Download a certificate file that contains the public key.
  - Configure your SAML IdP to use the public key to encrypt SAML assertions it issues.

In your IdP, do the following:

  - Enable assertion encryption, also known as token encryption.
  - Upload the public key that you created in workforce identity federation.
  - Confirm that your IdP produces encrypted SAML assertions.

Note that, even with SAML encryption provider keys configured, workforce identity federation can still process a plaintext assertion.

#### Create workforce identity federation SAML assertion encryption keys

This section guides you through creating an asymmetric key pair that enables workforce identity federation to accept encrypted SAML assertions.

Google Cloud uses the private key to decrypt the SAML assertions that your IdP issues. To create an asymmetric key pair for use with SAML encryption, run the following command. To learn more, see [Supported SAML encryption algorithms](https://docs.cloud.google.com/iam/docs/workforce-sign-in-okta#supported-saml-encryption-algorithms) .

    gcloud iam workforce-pools providers keys create KEY_ID \
        --workforce-pool WORKFORCE_POOL_ID \
        --provider WORKFORCE_PROVIDER_ID \
        --location global \
        --use encryption \
        --spec KEY_SPECIFICATION

Replace the following:

  - `  KEY_ID  ` : a key name of your choice
  - `  WORKFORCE_POOL_ID  ` : the pool ID
  - `  WORKFORCE_PROVIDER_ID  ` : the workforce identity pool provider ID
  - `  KEY_SPECIFICATION  ` : the key specification, which can be one of `rsa-2048` , `rsa-3072` , and `rsa-4096` .

After the key pair is created, to download the public key into a certificate file, execute the following command. Only workforce identity federation has access to the private key.

    gcloud iam workforce-pools providers keys describe KEY_ID \
        --workforce-pool WORKFORCE_POOL_ID \
        --provider WORKFORCE_PROVIDER_ID \
        --location global \
        --format "value(keyData.key)" \
        > CERTIFICATE_PATH

Replace the following:

  - `  KEY_ID  ` : the key name
  - `  WORKFORCE_POOL_ID  ` : the pool ID
  - `  WORKFORCE_PROVIDER_ID  ` : the workforce identity pool provider ID
  - `  CERTIFICATE_PATH  ` : the path to write the certificate to—for example, `saml-certificate.cer` or `saml-certificate.pem`

#### Configure your SAML 2.0-compliant IdP to issue encrypted SAML assertions

To configure Okta to encrypt SAML assertions, do the following:

Go to your Okta dashboard and sign in.

Go to **Applications** \> **Applications** .

Click on your app.

In the **General** tab, in the **SAML Settings** section, click **Edit** .

Click **Next** to view **SAML Settings** .

Click **Show advanced settings** .

In **SAML Settings** , do the following:

In either of **Response** (preferred) or **Assertion Signature** , select `Signed` .

In **Signature Algorithm** and **Digest Algorithm** , select any option.

Set the following values:

  - **Assertion Encryption:** Encrypted.
  - **Encryption Algorithm:** Any algorithm that you choose.
  - **Encryption Certificate:** Upload the certificate file that you generated earlier in this guide.

To save the configuration, click **Next** and then **Finish**

After you configure your IdP to encrypt SAML assertions, we recommend that you check to make sure that the assertions it generates are actually encrypted. Even with SAML assertion encryption configured, workforce identity federation can still process plaintext assertions.

#### Delete workforce identity federation encryption keys

To delete SAML encryption keys run the following command:

``` 
  gcloud iam workforce-pools providers keys delete KEY_ID \
      --workforce-pool WORKFORCE_POOL_ID \
      --provider WORKFORCE_PROVIDER_ID \
      --location global
```

Replace the following:

  - `  KEY_ID  ` : the key name
  - `  WORKFORCE_POOL_ID  ` : the pool ID
  - `  WORKFORCE_PROVIDER_ID  ` : the workforce identity pool provider ID

#### Supported SAML encryption algorithms

Workforce identity federation supports the following key transport algorithms:

  - <http://www.w3.org/2001/04/xmlenc#rsa-oaep-mgf1p>
  - [http://www.w3.org/2009/xmlenc11\#rsa-oaep"](http://www.w3.org/2009/xmlenc11#rsa-oaep)
  - [http://www.w3.org/2001/04/xmlenc\#rsa-1\_5"](http://www.w3.org/2001/04/xmlenc#rsa-1_5)

Workforce identity federation supports the following block encryption algorithms:

  - <http://www.w3.org/2001/04/xmlenc#aes128-cbc>
  - <http://www.w3.org/2001/04/xmlenc#aes192-cbc>
  - <http://www.w3.org/2001/04/xmlenc#aes256-cbc>
  - <http://www.w3.org/2009/xmlenc11#aes128-gcm>
  - <http://www.w3.org/2009/xmlenc11#aes256-gcm>

### Console

To configure the SAML provider using the Google Cloud console, do the following:

1.  In the Google Cloud console, go to the **Workforce Identity Pools** page:

2.  In the **Workforce Identity Pools** table, select the pool for which you want to create the provider.

3.  In the **Providers** section, click **add Add Provider** .

4.  In the **Select a Provider vendor** list, select your IdP.
    
    If your IdP isn't listed, then select **Generic Identity Provider** .

5.  In **Select an authentication protocol** , select **SAML** .

6.  In the **Create a provider** section, do the following:
    
    1.  In **Name** , enter a name for the provider.
    2.  Optional: In **Description** , enter a description for the provider.
    3.  In **IDP metadata file (XML)** , select the metadata XML file that you generated earlier in this guide.
    4.  To create a provider that is enabled, make sure **Enable provider** is on.
    5.  Click **Continue** .

7.  In the **Share your provider information** section, copy the URLs. In your IdP, configure the first URL as the entity ID, which identifies your application to IdP. Configure the other URL as the redirect URI, which informs your IdP where to send the assertion token after logging in.

8.  Click **Continue** .

9.  In the **Configure provider** section, do the following:
    
    1.  In **Attribute mapping** , enter a CEL expression for `google.subject` .
    
    2.  Optional: To enter other mappings, click **Add mapping** and enter other mappings—for example:
        
            google.subject=assertion.oid
            attribute.costcenter=assertion.attributes.costcenter[0]
        
        This example maps the IdP attributes `assertion.oid` and `assertion.attributes.costcenter[0]` to the Google Cloud attributes `google.subject` and `attribute.costcenter` , respectively.
    
    3.  Optional: To add an attribute condition, click **Add condition** and enter a CEL expression representing an attribute condition. For example, to limit the `ipaddr` attribute to a certain IP range you can set the condition `assertion.attributes.ipaddr.startsWith('98.11.12.')` . This example condition ensures that only users with an IP address that starts with `98.11.12.` can sign in using this workforce provider.
        
        > **Warning:** If your multi-tenant IdP has a single issuer URI, you must use [attribute conditions](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) to ensure that access is restricted to the correct tenant. For more information, see [Use attribute conditions when federating with GitHub or other multi-tenant identity providers](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#use-attribute-conditions-multitenant) .
    
    4.  Click **Continue** .
    
    5.  To turn on detailed audit logging, in **Detailed logging** , click the **Enable attribute value audit logging** toggle.
        
        Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
        
        To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .

10. To create the provider, click **Submit** .

## Verify your provider configuration

Before testing the end-user sign-in flow, you can verify that your provider configuration is correct and that Google Cloud can exchange tokens with your IdP.

The **Validate your provider attributes** page in the Google Cloud console includes an attributes viewer that lets you interactively test your configuration and debug Common Expression Language (CEL) expressions. You can use the attributes viewer to do the following:

  - View the raw attributes sent in the IdP assertion.
  - Verify that your attribute mappings and conditions correctly transform those attributes.
  - Debug complex CEL expressions in real time.

To verify your provider configuration, do the following:

1.  To enable the browser-based sign-in flow for Workforce Identity Federation, add ` https://auth.cloud.google/signin-callback/locations/global/workforcePools/ POOL_ID /providers/ PROVIDER_ID  ` to your IdP's list of allowed redirect URIs.

2.  In the Google Cloud console, go to **Workforce Identity Pools** .

3.  From the list of pools, click the name of the pool you want to verify.

4.  In the **Workforce pool details** page, click the name of the IdP you want to verify.

5.  In the **Provider Details** page, click **Debug IdP token** .

6.  In the **Sign in** dialog, sign in to your IdP as a test user.

The **Validate your provider attributes** page displays the mapped attributes and the result of your attribute condition.

The **Mapped attributes from your IdP token** section displays how Google attributes, such as `google.subject` , are populated from your IdP's token based on your mapping configuration. An error icon appears if a mapping is incorrect.

The **Attribute condition** section shows the boolean result of your condition. If the condition evaluates to `false` , the sign-in is blocked.

To view the full assertion token, click **View full token** . This shows the raw JSON object from your IdP. Reference a top-level property in your mappings using the format `assertion.PROPERTY_NAME` .

### Edit your provider configuration

To correct any errors, you can edit the configuration:

1.  In the **Validate your provider attributes** page, click **edit Edit** .
2.  Make the necessary changes.
3.  To start a new test and see the updated results, click **Save and refetch token** .

## Manage access to Google Cloud resources

This section provides an example that shows you how to manage access to Google Cloud resources by Workforce Identity Federation users.

In this example, you grant an Identity and Access Management (IAM) role on a sample project. Users can then [sign in](https://docs.cloud.google.com/iam/docs/workforce-sign-in-okta#sign_in) and use this project to access Google Cloud products.

> **Note:** The sample project used here can be different from the project you used to set up Workforce Identity Federation.

You can manage IAM roles for single identities, group of identities, or an entire pool. For more information, see [Represent workforce identity pool users in IAM policies](https://docs.cloud.google.com/iam/docs/configuring-workforce-identity-federation#representing-workforce-users) .

> **Note:** You must grant the Browser role ( `roles/browser` ) to all Workforce Identity Federation users that access the Google Cloud Workforce Identity Federation console, also known as the console (federated). You don't need to grant the role if the user accesses Google Cloud resources through the Google Cloud CLI.

### For single identity

To grant the Storage Admin ( `roles/storage.admin` ) role to a single identity for project `  TEST_PROJECT_ID  ` , run the following command:

    gcloud projects add-iam-policy-binding TEST_PROJECT_ID \
        --role="roles/storage.admin" \
        --member="principal://iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/subject/SUBJECT_VALUE"

Replace the following:

  - `  TEST_PROJECT_ID  ` : ID of the project
  - `  WORKFORCE_POOL_ID  ` : the workforce identity pool ID
  - `  SUBJECT_VALUE  ` : the user identity

### Using mapped department attribute

To grant the Storage Admin ( `roles/storage.admin` ) role to all identities within a specific department for project `  TEST_PROJECT_ID  ` , run the following command:

    gcloud projects add-iam-policy-binding TEST_PROJECT_ID \
        --role="roles/storage.admin" \
        --member="principalSet://iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/attribute.department/DEPARTMENT_VALUE"

Replace the following:

  - `  TEST_PROJECT_ID  ` : ID of the project
  - `  WORKFORCE_POOL_ID  ` : the workforce identity pool ID
  - `  DEPARTMENT_VALUE  ` : the mapped `attribute.department` value

### Using mapped groups

To grant the Storage Admin ( `roles/storage.admin` ) role to all identities within a specific group for project `  TEST_PROJECT_ID  ` , run the following command:

    gcloud projects add-iam-policy-binding TEST_PROJECT_ID \
        --role="roles/storage.admin" \
        --member="principalSet://iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/group/GROUP_ID"

Replace the following:

  - `  TEST_PROJECT_ID  ` : ID of the project
  - `  WORKFORCE_POOL_ID  ` : the workforce identity pool ID
  - `  GROUP_ID  ` : a group in the mapped `google.groups` claim.

## Sign in and test access

In this section, you sign in as a workforce identity pool user and test that you have access to a Google Cloud product.

### Sign in

This section shows you how to sign in as a federated user and access Google Cloud resources.

### gcloud CLI browser-based sign-in

To sign in to gcloud CLI using a browser-based sign-in flow, do the following:

**Create a configuration file**

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

**Sign in using browser-based authentication**

To authenticate using browser-based sign-in authentication, you can use one of the following methods:

  - If you used the `--activate` flag when you created the configuration file, or if you activated the configuration file with `gcloud config set auth/login_config_file` , the gcloud CLI uses your configuration file automatically:
    
        gcloud auth login

  - To sign in by specifying the location of the configuration file, run the following command:
    
        gcloud auth login --login-config=LOGIN_CONFIG_FILE_PATH

  - To use an environment variable to specify the location of the configuration file, set `CLOUDSDK_AUTH_LOGIN_CONFIG_FILE` to the configuration path.

**Disable browser-based sign-in**

To discontinue using the login configuration file, do the following:

  - If you used the `--activate` flag when you created the configuration file, or if you activated the configuration file with `gcloud config set auth/login_config_file` , you must run the following command to unset it:
    
        gcloud config unset auth/login_config_file

  - Clear the `CLOUDSDK_AUTH_LOGIN_CONFIG_FILE` environment variable, if it is set.

> **Note:** If you start an IdP-initiated sign-in, use the following URL in SAML Settings for the nested [**Default RelayState**](https://saml-doc.okta.com/SAML_Docs/Configure-SAML-2.0-for-Org2Org.html) parameter: `https://console.cloud.google/` .

### gcloud CLI headless sign-in

To sign in to gcloud CLI, using a headless flow, do the following:

### OIDC

1.  Sign in a user to your Okta app and get the [OIDC token](https://developer.okta.com/docs/reference/api/oidc/) from Okta.

2.  Save the OIDC token returned by Okta in a secure location on your local machine.

3.  To generate a configuration file like the example later in this step, run the following command:
    
        gcloud iam workforce-pools create-cred-config \
            locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID \
            --subject-token-type="urn:ietf:params:oauth:token-type:id_token" \
            --credential-source-file="PATH_TO_OIDC_ID_TOKEN" \
            --workforce-pool-user-project="WORKFORCE_POOL_USER_PROJECT" \
            --output-file="config.json"

Replace the following:

  - `  WORKFORCE_POOL_ID  ` : the workforce identity pool ID
  - `  WORKFORCE_PROVIDER_ID  ` : the provider ID
  - `  PATH_TO_OIDC_TOKEN  ` : the path to the OIDC IdP credential file
  - `  WORKFORCE_POOL_USER_PROJECT  ` : the project number associated with the [workforce pools user project](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#workforce-pools-user-project)

The principal must have `serviceusage.services.use` permission on this project.

When you run the command, it produces an OIDC IdP config file that is formatted similar to the following:

    {
      "type": "external_account",
      "audience": "//iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID",
      "subject_token_type": "urn:ietf:params:oauth:token-type:id_token",
      "token_url": "https://sts.googleapis.com/v1/token",
      "workforce_pool_user_project": "WORKFORCE_POOL_USER_PROJECT",
      "credential_source": {
        "file": "PATH_TO_OIDC_CREDENTIALS_FILE"
      }
    }

### SAML

1.  Sign in a user to your Okta app and get the [SAML Response](https://developer.okta.com/docs/concepts/saml/#planning-for-saml) from Okta.

2.  Save the SAML Response returned by Okta in a secure location on your local machine, then store the path, as follows:
    
        SAML_ASSERTION_PATH=SAML_ASSERTION_PATH

3.  To generate a configuration file, run the following command:
    
        gcloud iam workforce-pools create-cred-config \
            locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID \
            --subject-token-type="urn:ietf:params:oauth:token-type:saml2" \
            --credential-source-file="SAML_ASSERTION_PATH"  \
            --workforce-pool-user-project="PROJECT_ID"  \
            --output-file="config.json"
    
    Replace the following:
    
      - `  WORKFORCE_PROVIDER_ID  ` : the workforce provide ID you created earlier in this guide.
      - `  WORKFORCE_POOL_ID  ` : the workforce identity pool ID that you created earlier in this guide.
      - `  SAML_ASSERTION_PATH  ` : the path of the SAML assertion file.
      - `  PROJECT_ID  ` : the project ID
    
    The configuration file that is generated looks similar to the following:
    
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

To login to `gcloud` using token exchange, run the following command:

    gcloud auth login --cred-file="config.json"

`gcloud` then transparently exchanges your Okta credentials for temporary Google Cloud access tokens, allowing you to make other `gcloud` calls to Google Cloud.

You see output similar to the following:

    Authenticated with external account user credentials for:
    [principal://iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/subject/USER_ID].

To list the credentialed accounts and the currently active account, run the following command:

    gcloud auth list

### Console (federated) sign-in

To sign in to the Google Cloud Workforce Identity Federation console, also known as the console (federated), do the following:

Go to the console (federated) sign-in page.

Enter the provider name, which is formatted as follows:

    locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID

1.  Enter user credentials in the Okta app integration, if prompted.

If you start an IdP-initiated sign-in, use the following URL in **SAML Settings** for the nested [**Default RelayState**](https://saml-doc.okta.com/SAML_Docs/Configure-SAML-2.0-for-Org2Org.html) parameter: `https://console.cloud.google/` .

### Test access

You now have access to Google Cloud services that support Workforce Identity Federation and to which you are granted access. Earlier in this guide, you granted the Storage Admin ( `roles/storage.admin` ) role to all identities within a specific department for project `  TEST_PROJECT_ID  ` . You can now test that you have access by listing Cloud Storage buckets.

### gcloud CLI

To list Cloud Storage buckets and objects for the project that you have access to, run the following command:

    gcloud storage ls --project="TEST_PROJECT_ID"

The principal must have the `serviceusage.services.use` permission on the specified project.

### Console (federated)

To list Cloud Storage buckets using the console (federated), do the following:

  - Go to the Cloud Storage page.
  - Verify that you can see list of existing buckets for the `  TEST_PROJECT_ID  `

## Delete users

Workforce Identity Federation creates user metadata and resources for federated user identities. If you choose to delete users in your IdP you must also explicitly delete these resources in Google Cloud. To do so, see [Delete Workforce Identity Federation users and their data](https://docs.cloud.google.com/iam/docs/workforce-delete-user-data) .

You might see resources continue to be associated with a user that was deleted. This is because deleting user metadata and resources requires a long-running operation. After you initiate a deletion of a user's identity, processes that the user initiated before the deletion can continue to run until the processes complete or are canceled.

## What's next

  - [Configure SCIM in Okta](https://docs.cloud.google.com/iam/docs/configure-scim-okta)
  - [Delete Workforce Identity Federation users and their data](https://docs.cloud.google.com/iam/docs/workforce-delete-user-data)
  - Learn which Google Cloud products [support Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/federated-identity-supported-services)
  - [Set up user access to console (federated)](https://docs.cloud.google.com/iam/docs/workforce-console-sso)
