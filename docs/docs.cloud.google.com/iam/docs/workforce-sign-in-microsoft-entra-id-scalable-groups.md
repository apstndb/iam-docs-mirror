---
name: documents/docs.cloud.google.com/iam/docs/workforce-sign-in-microsoft-entra-id-scalable-groups
uri: https://docs.cloud.google.com/iam/docs/workforce-sign-in-microsoft-entra-id-scalable-groups
title: Configure Workforce Identity Federation with Microsoft Entra ID
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

You can configure Workforce Identity Federation with the Microsoft Entra ID identity provider (IdP) and map up to 400 groups from Microsoft Entra ID to Google Cloud by using Microsoft Graph. You can then grant IAM roles to those groups, which allows Microsoft Entra ID users that are members of the groups to sign into Google Cloud. The users can then access Google Cloud products to which they were granted IAM access that also [support Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/federated-identity-supported-services) .

To map fewer than 150 groups from Microsoft Entra ID to Google Cloud, see [Configure Workforce Identity Federation with Microsoft Entra ID and sign in users](https://docs.cloud.google.com/iam/docs/workforce-sign-in-microsoft-entra-id) .

## Key concepts

This section describes concepts that are used to configure Workforce Identity Federation, later in this document.

### Extra attributes

To map up to 400 groups, you use *extra attributes* by specifying `extra-attributes` flags when you create the workforce identity pool provider. You can use extra attributes with the following protocols:

  - OIDC with implicit flow
  - OIDC with code flow
  - SAML 2.0 protocol

The number of group email addresses that a Microsoft Entra ID application can emit in a token is limited to 150 for SAML and 200 for JWT. To learn more about this limit, see [Configure group claims for applications by using Microsoft Entra ID](https://learn.microsoft.com/en-us/entra/identity/hybrid/connect/how-to-connect-fed-group-claims) . To retrieve more groups, Workforce Identity Federation uses Microsoft Identity's [OAuth 2.0 client credentials flow](https://learn.microsoft.com/en-us/entra/identity-platform/v2-oauth2-client-creds-grant-flow) to obtain credentials that allow Workforce Identity Federation to query the Microsoft Graph API and fetch a user's groups.

To use extra attributes, at a high level, you do the following:

  - Create a new Microsoft Entra ID application or update your existing application to obtain users' group memberships from the Microsoft Graph API. To learn more about how Microsoft Graph retrieves a large number of groups from Microsoft Entra ID, see [Group overages](https://learn.microsoft.com/en-us/security/zero-trust/develop/configure-tokens-group-claims-app-roles#group-overages) .

  - When you create the workforce identity pool provider, you use `extra-attributes` flags to configure Workforce Identity Federation to retrieve users' group email addresses or display names from the Microsoft Graph API.

> **Important:** If extra attributes are configured, any groups provided in the SAML or OIDC assertion are ignored. Additionally, any configuration issue with extra attributes, such as an incorrect client ID or secret, causes the sign-in attempt to fail.

Workforce Identity Federation can retrieve a maximum of 999 groups from the Microsoft Graph API. If the Microsoft Graph API returns more than 999 groups, the sign-in fails.

To reduce the number of groups that the Microsoft Graph API returns, you can refine Workforce Identity Federation's query by using the `--extra-attributes-filter` flag, when you create the workforce identity pool provider.

After Workforce Identity Federation retrieves the groups from the Microsoft Graph API, it mints the access token. Workforce Identity Federation can add a maximum of 400 groups to the access token, so, to further filter the number of groups to 400 or fewer, you can specify an [attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) that contains common expression language (CEL) expressions, when you create the workforce identity pool provider.

## Before you begin

1.  Make sure that you have a Google Cloud organization set up.

2.  [Install](https://docs.cloud.google.com/sdk/docs/install) the Google Cloud CLI. After installation, [initialize](https://docs.cloud.google.com/sdk/docs/initializing) the Google Cloud CLI by running the following command:
    
        gcloud init
    
    If you're using an external identity provider (IdP), you must first [sign in to the gcloud CLI with your federated identity](https://docs.cloud.google.com/iam/docs/workforce-log-in-gcloud) .
    
    > **Note:** If you installed the gcloud CLI previously, make sure you have the latest version by running `gcloud components update` .

3.  In Microsoft Entra ID, make sure that ID tokens are enabled for implicit flow. For more information, see [Enable ID token implicit grant](https://learn.microsoft.com/en-us/azure/active-directory-b2c/tutorial-register-applications#enable-id-token-implicit-grant) .

4.  For sign-in, your IdP must provide signed authentication information: OIDC IdPs must provide a JWT, and SAML IdP responses must be signed.

5.  To receive important information about changes to your organization or Google Cloud products, you must provide [Essential Contacts](https://docs.cloud.google.com/resource-manager/docs/managing-notification-contacts) . For more information, see the [Workforce Identity Federation overview](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#essential-contacts) .

6.  All groups that you intend to map must be marked as security groups in Microsoft Entra ID.
    
    > **Important:** A maximum of 999 groups can be fetched.

## Costs

Workforce Identity Federation is available as a no-cost feature. However, Workforce Identity Federation detailed audit logging uses Cloud Logging. To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .

## Required roles

To get the permissions that you need to configure Workforce Identity Federation, ask your administrator to grant you the [IAM Workforce Pool Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin) ( `roles/iam.workforcePoolAdmin` ) IAM role on the organization. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

You might also be able to get the required permissions through [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

If you're configuring permissions in a development or test environment—but not a production environment—you can grant the IAM Owner ( `roles/owner` ) basic role, which also includes permissions for Workforce Identity Federation.

## Create a Microsoft Entra ID application

This section shows you how to create a Microsoft Entra ID application using the Microsoft Entra admin portal. Alternatively, you can update your existing application. For additional details, see [Establish applications in the Microsoft Entra ID ecosystem](https://learn.microsoft.com/en-us/entra/architecture/establish-applications) .

Workforce identity pools support federation using both OIDC and SAML protocols.

### OIDC

To create a Microsoft Entra ID application registration that uses the OIDC protocol, do the following:

1.  Sign in to the Microsoft Entra administrator center.

2.  Go to the **Overview** page of your Microsoft Entra ID application registration.

3.  Navigate to **Entra ID \> App registrations** .

4.  To begin configuring the application registration, do the following:
    
    1.  Click **New registration** .
    
    2.  Enter a name for your application.
    
    3.  In **Supported account types** , select an option.
    
    4.  In the **Redirect URI** section, in the **Select a platform** drop-down list, select **Web** .
    
    5.  In the text field, enter a redirect URL. Your users are redirected to this URL after they successfully sign in. If you are configuring access to the [console (federated)](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#google_cloud_workforce_identity_federation_console) , use the following URL format:
        
            https://auth.cloud.google/signin-callback/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID
        
        Replace the following:
        
          - `  WORKFORCE_POOL_ID  ` : a workforce identity pool ID that you will use when creating the workforce identity pool later in this document—for example: `entra-id-oidc-pool`
        
          - `  WORKFORCE_PROVIDER_ID  ` : a workforce identity pool provider ID that you will use when you create the workforce identity pool provider later in this document—for example: `entra-id-oidc-pool-provider`
            
            For information on formatting the ID, see the [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create#query-parameters) section in the API documentation.
    
    6.  To create the application registration, click **Register** .
    
    7.  To use the example attribute mapping that is provided later in this document, you must create a custom `department` attribute.

### SAML

To create a Microsoft Entra ID application registration that uses the SAML protocol, do the following:

1.  Sign in to the Microsoft Entra administrator portal.

2.  In the left-hand navigation menu, go to **Entra ID \> Enterprise Apps** .

3.  To begin configuring the enterprise application, do the following:
    
    1.  Click **New application** \> **Create your own application** .
    
    2.  In the **Create your own application** pane that appears, enter a name for your application.
    
    3.  Click **Create** .
    
    4.  Go to **Single sign-on** \> **SAML** .
    
    5.  Update the **Basic SAML Configuration** as follows:
        
        1.  In the **Identifier (Entity ID)** field, enter the following value:
            
                https://iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID
            
            Replace the following:
            
              - `  WORKFORCE_POOL_ID  ` : a workforce identity pool ID that you will use when creating the workforce identity pool later in this document—for example: `entra-id-saml-pool`
            
              - `  WORKFORCE_PROVIDER_ID  ` : a workforce identity pool provider ID that you will use when you create the workforce identity pool provider later in this document—for example: `entra-id-saml-pool-provider`
                
                For information on formatting the ID, see the [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create#query-parameters) section in the API documentation.
        
        2.  In the **Reply URL (Assertion Consumer Service URL)** field, enter a redirect URL. Your users are redirected to this URL after they successfully sign in. If you are configuring access to the [console (federated)](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#console-federated) , use the following URL format:
            
                https://auth.cloud.google/signin-callback/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID
            
            Replace the following:
            
              - `  WORKFORCE_POOL_ID  ` : the workforce identity pool ID
              - `  WORKFORCE_PROVIDER_ID  ` : the workforce identity provider ID
        
        3.  To enable IdP-initiated sign-on, set the **Relay State** field to the following value:
            
                https://console.cloud.google/
        
        4.  To save the SAML application configuration, click **Save** .
    
    6.  To use the example attribute mapping that is provided later in this document, you must create a custom `department` attribute.

## Configure large numbers of groups with Microsoft Entra ID

This section describes how to map up to 400 groups from Microsoft Entra ID to Workforce Identity Federation using the OIDC and SAML protocols.

### Configure large numbers of groups with Microsoft Entra ID with OIDC implicit flow

This section describes how to map up to 400 groups from Microsoft Entra ID to Workforce Identity Federation using the OpenID Connect (OIDC) protocol with implicit flow.

#### Configure your Microsoft Entra ID application

You can configure an existing Microsoft Entra ID application or create a new one. To configure your application, do the following:

1.  In the Microsoft Entra ID portal, do the following:
    
      - To register a new application, follow the instructions in [Register a new application](https://learn.microsoft.com/en-us/azure/healthcare-apis/register-application#register-a-new-application) .
      - To update an existing application, do the following:
          - Go to the **Overview** page of your Microsoft Entra ID application registration.
        
          - Navigate to **Entra ID \> App registrations** .
        
          - Select the application that you want to update.

2.  Create a new client secret in the application by following the instructions in [Certificates & secrets](https://learn.microsoft.com/en-us/azure/healthcare-apis/register-application#certificates--secrets) . Make sure that you record the client secret value because it's displayed only once.
    
    Note the following values from the application that you created or updated. You provide the values when you configure the workforce identity pool provider later in this document.
    
      - `Client ID`
      - `Issuer URI`
      - `Client Secret`
      - `Tenant ID`

3.  To retrieve the Microsoft Entra ID groups, add the API permission to let Workforce Identity Federation access users' information from Microsoft Entra ID using the Microsoft Graph API and grant admin consent. In Microsoft Entra ID, do the following:
    
    1.  Go to **API permissions** .
    2.  Click **Add a Permission** .
    3.  Select **Microsoft API** .
    4.  Select **Application permissions** .
    5.  In the search field, enter `User.ReadBasic.All` .
    6.  Click **Add permissions** .
    
    You can retrieve the Microsoft Entra ID groups using a group object identifier (ID), a group email address for email-enabled groups, or a group display name.
    
    If you choose to retrieve groups as group email addresses or display names, the next step is required.

4.  To retrieve the Microsoft Entra ID groups as group email addresses or display names, do the following. If you retrieve groups as group object identifiers, skip this step.
    
    1.  Go to **API permissions** .
    2.  Click **Add a Permission** .
    3.  Select **Microsoft API** .
    4.  Select **Application permissions** .
    5.  In the search field, enter `GroupMember.Read.All` .
    6.  Click **Add permissions** .
    
    Go to the **Overview** page of the Microsoft Entra ID application that you created or updated earlier. Click **Endpoints** . The issuer URI is the OIDC metadata document URI, omitting the path `/.well-known/openid-configuration` .
    
    For example, if the OIDC metadata document is `https://login.microsoftonline.com/d41ad248-019e-49e5-b3de-4bdfe1fapple/v2.0/.well-known/openid-configuration` , the issuer URI is `https://login.microsoftonline.com/d41ad248-019e-49e5-b3de-4bdfe1fapple/v2.0/` .

#### Create a workforce identity pool

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

#### Configure the OIDC implicit flow workforce identity pool provider

### gcloud

To create the OIDC workforce identity pool provider, run the following command:

``` 
gcloud iam workforce-pools providers create-oidc PROVIDER_ID \
    --workforce-pool=WORKFORCE_POOL_ID \
    --location=global \
    --display-name=DISPLAY_NAME \
    --issuer-uri=ISSUER_URI \
    --client-id=CLIENT_ID \
    --attribute-mapping=ATTRIBUTE_MAPPING \
    --web-sso-response-type=id-token \
    --web-sso-assertion-claims-behavior=only-id-token-claims \
    --extra-attributes-issuer-uri=EXTRA_ATTRIBUTES_ISSUER_URI \
    --extra-attributes-client-id=EXTRA_ATTRIBUTES_CLIENT_ID \
    --extra-attributes-client-secret-value=EXTRA_ATTRIBUTES_CLIENT_SECRET \
    --extra-attributes-type=EXTRA_ATTRIBUTES_TYPE  \
    --extra-attributes-filter=EXTRA_ATTRIBUTES_FILTER \
    --detailed-audit-logging
    
```

Replace the following:

  - `  PROVIDER_ID  ` : a unique provider ID. The prefix `gcp-` is reserved and can't be used in a pool or provider ID.

  - `  WORKFORCE_POOL_ID  ` : the workforce pool ID.

  - `  DISPLAY_NAME  ` : a display name for the provider.

  - `  ISSUER_URI  ` : the issuer URI from the Microsoft Entra ID application that you created earlier in this document.

  - `  CLIENT_ID  ` : the client ID from your Microsoft Entra ID application.

  - `  ATTRIBUTE_MAPPING  ` : the mapping of attributes from Microsoft Entra ID to Google Cloud. If you use `--extra-attributes` flags to query groups from Microsoft Entra ID, any `google.groups` mapping that uses standard SAML or OIDC claims is ignored. For example, to map `groups` and `subject` attributes from Microsoft Entra ID, use the following attribute mapping:
    
        --attribute-mapping="google.groups=assertion.groups, google.subject=assertion.oid"
    
    For more information, see [Attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mapping) .

  - `  EXTRA_ATTRIBUTES_ISSUER_URI  ` : the issuer URI from your Microsoft Entra ID application.
    
    > **Note:** If there is any configuration issue with extra attributes, such as an incorrect client ID or secret, the sign-in attempt fails.

  - `  EXTRA_ATTRIBUTES_CLIENT_ID  ` : the client ID from your Microsoft Entra ID application.

  - `  EXTRA_ATTRIBUTES_CLIENT_SECRET  ` : the extra client secret from your Microsoft Entra ID application.

  - `  EXTRA_ATTRIBUTES_TYPE  ` : use `azure-ad-groups-mail` to retrieve the email addresses of the groups. Use `azure-ad-groups-id` to retrieve the IDs of the groups. Use `azure-ad-groups-display-name` to retrieve the display names of the groups.

  - `  EXTRA_ATTRIBUTES_FILTER  ` : Optional. A filter expression that is used when querying the Microsoft Graph API for groups. You can use this parameter to ensure that the number of groups fetched from the IdP remains below the limit of 400 groups.
    
    The following example fetches the groups that have the prefix `sales` in their email ID:
    
        --extra-attributes-filter='"mail:sales"'
    
    The following expression fetches groups with a display name that contains the string `sales` .
    
        --extra-attributes-filter='"displayName:sales"'

  - Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
    
    To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .

### Console

1.  In the Google Cloud console, go to the **Workforce Identity Pools** page:

2.  In the **Workforce Identity Pools** table, select the pool for which you want to create the provider.

3.  In the **Providers** section, click **add Add Provider** .

4.  In the **Select a Provider vendor** list, select your identity provider (IdP).
    
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

10. In the **Flow type** list, select **ID Token** .

11. In the **Assertion claims behavior** list, **ID token** is selected.

12. Optional: If you selected **Okta** as your IdP, add any extra OIDC scopes in the **Additional scopes beyond openid, profile, and email** field.

Click **Continue** .

In **Configure provider** , you can configure an attribute mapping and an attribute condition. To create an [attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) , do the following. You can provide either the IdP field name or a [CEL-formatted](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) expression that returns a string.

1.  Required: In **OIDC 1** , enter the subject from the IdP— for example, `assertion.sub` .
2.  Optional: To add additional attribute mappings, do the following:
    1.  Click **Add mapping** .
    2.  In **Google *n*** , where *n* is a number, enter one of the [Google Cloud-supported keys](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) .
    3.  In the corresponding **OIDC *n*** field, enter the name of the IdP-specific field to map, in CEL format.
3.  If you selected **Microsoft Entra ID** as your IdP, you can increase the number of groups.
    1.  Select **Use Extra Attributes** .
    2.  In the **Extra Attributes Issuer URI** field, enter the issuer URL.
    3.  In the **Extra Attributes Client ID** field, enter the client ID.
    4.  In the **Extra Attributes Client Secret** field, enter the client secret.
    5.  In the **Extra Attributes Type** list, select an attribute type for extra attributes.
    6.  In the **Extra Attributes Filter** field, enter a filter expression that is used when querying the Microsoft Graph API for groups.
4.  To create an attribute condition, do the following:
    1.  Click **Add condition** .
    
    2.  In the **Attribute Conditions** field, enter a condition in [CEL format](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) — for example, `assertion.role == 'gcp-users'` . This example condition ensures that only users with the role `gcp-users` can sign in using this provider.
    
    3.  To turn on detailed audit logging, in **Detailed logging** , click the **Enable attribute value audit logging** toggle.
        
        Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
        
        To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .

To create the provider, click **Submit** .

### Configure large numbers of groups in Microsoft Entra ID with OIDC code flow

This section describes how to map up to 400 groups from Microsoft Entra ID to Workforce Identity Federation using the OIDC protocol with code flow.

#### Configure your Microsoft Entra ID application

You can configure an existing Microsoft Entra ID application or create a new one. To configure your application, do the following:

1.  In the Microsoft Entra ID portal, do the following:
    
      - To register a new application, follow the instructions in [Register a new application](https://learn.microsoft.com/en-us/azure/healthcare-apis/register-application#register-a-new-application) .
      - To update an existing application, do the following:
          - Go to the **Overview** page of your Microsoft Entra ID application registration.
        
          - Navigate to **Entra ID \> App registrations** .
        
          - Select the application that you want to update.

2.  Create a new client secret in the application by following the instructions in [Certificates & secrets](https://learn.microsoft.com/en-us/azure/healthcare-apis/register-application#certificates--secrets) . Make sure that you record the client secret value because it's displayed only once.
    
    Note the following values from the application that you created or updated. You provide the values when you configure the workforce identity pool provider later in this document.
    
      - `Client ID`
      - `Issuer URI`
      - `Client Secret`
      - `Tenant ID`

3.  To retrieve the Microsoft Entra ID groups, add the API permission to let Workforce Identity Federation access users' information from Microsoft Entra ID using the Microsoft Graph API and grant admin consent. In Microsoft Entra ID, do the following:
    
    1.  Go to **API permissions** .
    2.  Click **Add a Permission** .
    3.  Select **Microsoft API** .
    4.  Select **Delegated permissions** .
    5.  In the search field, enter `User.Read` .
    6.  Click **Add permissions** .
    
    You can retrieve the Microsoft Entra ID groups using a group object identifier (ID), a group email address for email-enabled groups, or a group display name.
    
    If you choose to retrieve groups as group email addresses or display names, the next step is required.

4.  To retrieve the Microsoft Entra ID groups as group email addresses or display names, do the following. If you retrieve groups as group object identifiers, skip this step.
    
    1.  Go to **API permissions** .
    2.  Click **Add a Permission** .
    3.  Select **Microsoft API** .
    4.  Select **Delegated permissions** .
    5.  In the search field, enter `GroupMember.Read.All` .
    6.  Click **Add permissions** .
    
    Go to the **Overview** page of the Microsoft Entra ID application that you created or updated earlier. Click **Endpoints** . The issuer URI is the OIDC metadata document URI, omitting the path `/.well-known/openid-configuration` .
    
    For example, if the OIDC metadata document is `https://login.microsoftonline.com/d41ad248-019e-49e5-b3de-4bdfe1fapple/v2.0/.well-known/openid-configuration` , the issuer URI is `https://login.microsoftonline.com/d41ad248-019e-49e5-b3de-4bdfe1fapple/v2.0/` .

#### Create a workforce identity pool

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

#### Configure the OIDC code flow workforce identity pool provider

### gcloud

To create the OIDC workforce identity pool provider, run the following command:

``` 
gcloud iam workforce-pools providers create-oidc PROVIDER_ID \
    --workforce-pool=WORKFORCE_POOL_ID \
    --location=global \
    --display-name=DISPLAY_NAME \
    --issuer-uri=ISSUER_URI \
    --client-id=CLIENT_ID \
    --client-secret-value="OIDC_CLIENT_SECRET" \
    --attribute-mapping=ATTRIBUTE_MAPPING \
    --web-sso-response-type=code \
    --web-sso-assertion-claims-behavior=merge-user-info-over-id-token-claims \
    --extra-attributes-issuer-uri=EXTRA_ATTRIBUTES_ISSUER_URI \
    --extra-attributes-client-id=EXTRA_ATTRIBUTES_CLIENT_ID \
    --extra-attributes-client-secret-value=EXTRA_ATTRIBUTES_CLIENT_SECRET \
    --extra-attributes-type=EXTRA_ATTRIBUTES_TYPE  \
    --extra-attributes-filter=EXTRA_ATTRIBUTES_FILTER \
    --detailed-audit-logging
    
```

Replace the following:

  - `  PROVIDER_ID  ` : a unique provider ID. The prefix `gcp-` is reserved and can't be used in a pool or provider ID.

  - `  WORKFORCE_POOL_ID  ` : the workforce pool ID.

  - `  DISPLAY_NAME  ` : a display name for the provider.

  - `  ISSUER_URI  ` : the issuer URI from the Microsoft Entra ID application that you created earlier in this document.

  - `  CLIENT_ID  ` : the client ID from your Microsoft Entra ID application.

  - `  ATTRIBUTE_MAPPING  ` : the mapping of attributes from Microsoft Entra ID to Google Cloud. If you use `--extra-attributes` flags to query groups from Microsoft Entra ID, any `google.groups` mapping that uses standard SAML or OIDC claims is ignored. For example, to map `groups` and `subject` attributes from Microsoft Entra ID, use the following attribute mapping:
    
        --attribute-mapping="google.groups=assertion.groups, google.subject=assertion.oid"
    
    For more information, see [Attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mapping) .

  - `  EXTRA_ATTRIBUTES_ISSUER_URI  ` : the issuer URI from your Microsoft Entra ID application.
    
    > **Note:** If there is any configuration issue with extra attributes, such as an incorrect client ID or secret, the sign-in attempt fails.

  - `  EXTRA_ATTRIBUTES_CLIENT_ID  ` : the client ID from your Microsoft Entra ID application.

  - `  EXTRA_ATTRIBUTES_CLIENT_SECRET  ` : the extra client secret from your Microsoft Entra ID application.

  - `  EXTRA_ATTRIBUTES_TYPE  ` : use `azure-ad-groups-mail` to retrieve the email addresses of the groups. Use `azure-ad-groups-id` to retrieve the IDs of the groups. Use `azure-ad-groups-display-name` to retrieve the display names of the groups.

  - `  EXTRA_ATTRIBUTES_FILTER  ` : Optional. A filter expression that is used when querying the Microsoft Graph API for groups. You can use this parameter to ensure that the number of groups fetched from the IdP remains below the limit of 400 groups.
    
    The following example fetches the groups that have the prefix `sales` in their email ID:
    
        --extra-attributes-filter='"mail:sales"'
    
    The following expression fetches groups with a display name that contains the string `sales` .
    
        --extra-attributes-filter='"displayName:sales"'

  - Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
    
    To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .

### Console

In the Google Cloud console, go to the **Workforce Identity Pools** page:

In the **Workforce Identity Pools** table, select the pool for which you want to create the provider.

In the **Providers** section, click **add Add Provider** .

In the **Select a Provider vendor** list, select your identity provider (IdP).

If your IdP isn't listed, then select **Generic Identity Provider** .

In **Select an authentication protocol** , select **OpenID Connect (OIDC)** .

In the **Create a provider** section, do the following:

1.  In **Name** , enter the name for the provider.

2.  In **Description** , enter the description for the provider.

3.  In **Issuer (URL)** , enter the issuer URI. The OIDC issuer URI must be in a valid URI format and start with `https` ; for example, `https://example.com/oidc` .

4.  In **Client ID** , enter the OIDC client ID that is registered with your OIDC IdP; the ID must match the `aud` claim of the JWT that is issued by your IdP.

5.  To create a provider that is enabled, make sure **Enable provider** is on.

6.  Click **Continue** .

In the **Share your provider information with IdP** section, copy the URL. In your IdP, configure this URL as the redirect URI, which informs your IdP where to send the assertion token after logging in.

Click **Continue** .

In the **Configure OIDC Web Sign-in** section, do the following:

In the **Flow type** list, select **Code** .

In the **Assertion claims behavior** list, select either of the following:

  - **User info and ID token**
  - **Only ID token**

In the **Client secret** field, enter the client secret from your IdP.

Optional: If you selected **Okta** as your IdP, add any extra OIDC scopes in the **Additional scopes beyond openid, profile, and email** field.

Click **Continue** .

In **Configure provider** , you can configure an attribute mapping and an attribute condition. To create an [attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) , do the following. You can provide either the IdP field name or a [CEL-formatted](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) expression that returns a string.

1.  Required: In **OIDC 1** , enter the subject from the IdP— for example, `assertion.sub` .
2.  Optional: To add additional attribute mappings, do the following:
    1.  Click **Add mapping** .
    2.  In **Google *n*** , where *n* is a number, enter one of the [Google Cloud-supported keys](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) .
    3.  In the corresponding **OIDC *n*** field, enter the name of the IdP-specific field to map, in CEL format.
3.  If you selected **Microsoft Entra ID** as your IdP, you can increase the number of groups.
    1.  Select **Use Extra Attributes** .
    2.  In the **Extra Attributes Issuer URI** field, enter the issuer URL.
    3.  In the **Extra Attributes Client ID** field, enter the client ID.
    4.  In the **Extra Attributes Client Secret** field, enter the client secret.
    5.  In the **Extra Attributes Type** list, select an attribute type for extra attributes.
    6.  In the **Extra Attributes Filter** field, enter a filter expression that is used when querying the Microsoft Graph API for groups.
4.  To create an attribute condition, do the following:
    1.  Click **Add condition** .
    
    2.  In the **Attribute Conditions** field, enter a condition in [CEL format](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) — for example, `assertion.role == 'gcp-users'` . This example condition ensures that only users with the role `gcp-users` can sign in using this provider.
    
    3.  To turn on detailed audit logging, in **Detailed logging** , click the **Enable attribute value audit logging** toggle.
        
        Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
        
        To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .

To create the provider, click **Submit** .

### Configure large numbers of groups in Microsoft Entra ID with SAML 2.0

This section describes how to map up to 400 groups from Microsoft Entra ID to Workforce Identity Federation using the SAML 2.0 protocol.

#### Configure your Microsoft Entra ID application

To configure your application, do the following:

1.  In the Microsoft Entra ID portal, do the following:
    
      - To register a new application, follow the instructions in [Register a new application](https://learn.microsoft.com/en-us/azure/healthcare-apis/register-application#register-a-new-application) .
      - To update an existing application, do the following:
          - Go to the **Overview** page of your Microsoft Entra ID application registration.
        
          - Navigate to **Entra ID \> App registrations** .
        
          - Select the application that you want to update.

2.  Create a new client secret in the application by following the instructions in [Certificates & secrets](https://learn.microsoft.com/en-us/azure/healthcare-apis/register-application#certificates--secrets) . Make sure that you record the client secret value because it's displayed only once.
    
    Note the following values from the application that you created or updated. You provide the values when you configure the workforce identity pool provider later in this document.
    
      - `Client ID`
      - `Issuer URI`
      - `Client Secret`
      - `Tenant ID`

3.  To retrieve the Microsoft Entra ID groups, add the API permission to let Workforce Identity Federation access users' information from Microsoft Entra ID using the Microsoft Graph API and grant admin consent. In Microsoft Entra ID, do the following:
    
    1.  Go to **API permissions** .
    2.  Click **Add a Permission** .
    3.  Select **Microsoft API** .
    4.  Select **Application permissions** .
    5.  In the search field, enter `User.ReadBasic.All` .
    6.  Click **Add permissions** .
    
    You can retrieve the Microsoft Entra ID groups using a group object identifier (ID), a group email address for email-enabled groups, or a group display name.
    
    If you choose to retrieve groups as group email addresses or display names, the next step is required.

4.  To retrieve the Microsoft Entra ID groups as group email addresses or display names, do the following. If you retrieve groups as group object identifiers, skip this step.
    
    1.  Go to **API permissions** .
    2.  Click **Add a Permission** .
    3.  Select **Microsoft API** .
    4.  Select **Application permissions** .
    5.  In the search field, enter `GroupMember.Read.All` .
    6.  Click **Add permissions** .
    
    Go to the **Overview** page of the Microsoft Entra ID application that you created or updated earlier. Click **Endpoints** . The issuer URI is the OIDC metadata document URI, omitting the path `/.well-known/openid-configuration` .
    
    For example, if the OIDC metadata document is `https://login.microsoftonline.com/d41ad248-019e-49e5-b3de-4bdfe1fapple/v2.0/.well-known/openid-configuration` , the issuer URI is `https://login.microsoftonline.com/d41ad248-019e-49e5-b3de-4bdfe1fapple/v2.0/` .

#### Create a workforce identity pool

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

#### Configure the SAML 2.0 workforce identity pool provider

### gcloud

To create the SAML workforce identity pool provider, run the following command:

``` 
gcloud iam workforce-pools providers create-saml PROVIDER_ID \
    --workforce-pool=WORKFORCE_POOL_ID \
    --location=global \
    --display-name=DISPLAY_NAME \
    --idp-metadata-path=XML_METADATA_PATH \
    --attribute-mapping=ATTRIBUTE_MAPPING \
    --extra-attributes-issuer-uri=EXTRA_ATTRIBUTES_ISSUER_URI \
    --extra-attributes-client-id=EXTRA_ATTRIBUTES_CLIENT_ID \
    --extra-attributes-client-secret-value=EXTRA_ATTRIBUTES_CLIENT_SECRET \
    --extra-attributes-type=EXTRA_ATTRIBUTES_TYPE  \
    --extra-attributes-filter=EXTRA_ATTRIBUTES_FILTER \
    --detailed-audit-logging
    
```

Replace the following:

  - `  PROVIDER_ID  ` : a unique provider ID. The prefix `gcp-` is reserved and can't be used in a pool or provider ID.

  - `  WORKFORCE_POOL_ID  ` : the workforce pool ID.

  - `  DISPLAY_NAME  ` : a display name for the provider.

  - `  XML_METADATA_PATH  ` : the path to the SAML 2.0 XML metadata file.

  - `  ATTRIBUTE_MAPPING  ` : the mapping of attributes from Microsoft Entra ID to Google Cloud. If you use `--extra-attributes` flags to query groups from Microsoft Entra ID, any `google.groups` mapping that uses standard SAML or OIDC claims is ignored. For example, to map `groups` and `subject` attributes from Microsoft Entra ID, use the following attribute mapping:
    
        --attribute-mapping="google.groups=assertion.groups, google.subject=assertion.oid"
    
    For more information, see [Attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mapping) .

  - `  EXTRA_ATTRIBUTES_ISSUER_URI  ` : the issuer URI from your Microsoft Entra ID application.
    
    > **Note:** If there is any configuration issue with extra attributes, such as an incorrect client ID or secret, the sign-in attempt fails.

  - `  EXTRA_ATTRIBUTES_CLIENT_ID  ` : the client ID from your Microsoft Entra ID application.

  - `  EXTRA_ATTRIBUTES_CLIENT_SECRET  ` : the extra client secret from your Microsoft Entra ID application.

  - `  EXTRA_ATTRIBUTES_TYPE  ` : use `azure-ad-groups-mail` to retrieve the email addresses of the groups. Use `azure-ad-groups-id` to retrieve the IDs of the groups. Use `azure-ad-groups-display-name` to retrieve the display names of the groups.

  - `  EXTRA_ATTRIBUTES_FILTER  ` : Optional. A filter expression that is used when querying the Microsoft Graph API for groups. You can use this parameter to ensure that the number of groups fetched from the IdP remains below the limit of 400 groups.
    
    The following example fetches the groups that have the prefix `sales` in their email ID:
    
        --extra-attributes-filter='"mail:sales"'
    
    The following expression fetches groups with a display name that contains the string `sales` .
    
        --extra-attributes-filter='"displayName:sales"'

  - Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
    
    To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .

### Console

1.  In the Google Cloud console, go to the **Workforce Identity Pools** page:

2.  In the **Workforce Identity Pools** table, select the pool for which you want to create the provider.

3.  In the **Providers** section, click **add Add Provider** .

4.  In the **Select a Provider vendor** list, select your identity provider (IdP).
    
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
    
    3.  If you selected **Microsoft Entra ID** as your IdP, you can increase the number of groups.
        
        1.  Select **Use Extra Attributes** .
        2.  In the **Extra Attributes Issuer URI** field, enter the issuer URL.
        3.  In the **Extra Attributes Client ID** field, enter the client ID.
        4.  In the **Extra Attributes Client Secret** field, enter the client secret.
        5.  In the **Extra Attributes Type** list, select an attribute type for extra attributes.
        6.  In the **Extra Attributes Filter** field, enter a filter expression that is used when querying the Microsoft Graph API for groups.
    
    4.  Optional: To add an attribute condition, click **Add condition** and enter a CEL expression representing an attribute condition. For example, to limit the `ipaddr` attribute to a certain IP range you can set the condition `assertion.attributes.ipaddr.startsWith('98.11.12.')` . This example condition ensures that only users with an IP address that starts with `98.11.12.` can sign in using this workforce provider.
    
    5.  Click **Continue** .
    
    6.  To turn on detailed audit logging, in **Detailed logging** , click the **Enable attribute value audit logging** toggle.
        
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

## Grant IAM roles to groups

In this section you grant roles to groups on Google Cloud resources. To learn more about Workforce Identity Federation principal identifiers, see [Represent workforce pool users in IAM policies](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#representing-workforce-users) .

The following example grants the Storage Admin role ( `roles/storage.admin` ) to users in a Microsoft Entra ID group.

    gcloud projects add-iam-policy-binding PROJECT_ID \
        --role="roles/storage.admin" \
        --member="principalSet://iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/group/GROUP_ID"

Replace the following:

  - `  PROJECT_ID  ` : the project ID
  - `  WORKFORCE_POOL_ID  ` : the workforce identity pool ID
  - `  GROUP_ID  ` : the group identifier, which depends on the value of `--extra-attributes-type` that was used to create the workforce identity pool provider, as follows:
      - `azure-ad-groups-mail` : the group identifier is an email address—for example: `admin-group@altostrat.com`
      - `azure-ad-groups-id` : the group identifier is a UUID for the group—for example: `abcdefgh-0123-0123-abcdef`

## Sign in and test access

In this section, you sign in as a workforce identity pool user and test that you have access to Google Cloud resources.

### Sign in

This section shows you how to sign in as a federated user and access Google Cloud resources.

### Console (federated) sign-in

To sign in to the Google Cloud Workforce Identity Federation console, also known as the console (federated), do the following:

1.  Go to the console (federated) sign-in page.

2.  Enter the provider name, which is formatted as follows:
    
        locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID

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

### gcloud CLI headless sign-in

To sign in to Microsoft Entra ID with the gcloud CLI, do the following:

### OIDC

1.  Follow the steps in [Send the sign-in request](https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-implicit-grant-flow#send-the-sign-in-request) . Sign the user into your application with Microsoft Entra ID using OIDC.

2.  Copy the ID token from the `id_token` parameter of the redirect URL and save it to a file in a secure location on your local machine. In a later step, you set PATH\_TO\_OIDC\_ID\_TOKEN to the path to this file.

3.  Generate a configuration file similar to the example later in this step by running the following command:
    
        gcloud iam workforce-pools create-cred-config \
            locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID \
            --subject-token-type=urn:ietf:params:oauth:token-type:id_token \
            --credential-source-file=PATH_TO_OIDC_ID_TOKEN \
            --workforce-pool-user-project=WORKFORCE_POOL_USER_PROJECT \
            --output-file=config.json
    
    Replace the following:
    
      - `  WORKFORCE_POOL_ID  ` : the workforce identity pool ID.
      - `  WORKFORCE_PROVIDER_ID  ` : the workforce identity pool provider ID.
      - `  PATH_TO_OIDC_ID_TOKEN  ` : the path to the file location where the IdP token is stored.
      - `  WORKFORCE_POOL_USER_PROJECT  ` : the project number or ID used for quota and billing. The principal must have `serviceusage.services.use` permission on this project.
    
    When the command completes, the following config file is created by Microsoft Entra ID:
    
        {
          "type": "external_account",
          "audience": "//iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID",
          "subject_token_type": "urn:ietf:params:oauth:token-type:id_token",
          "token_url": "https://sts.googleapis.com/v1/token",
          "workforce_pool_user_project": "WORKFORCE_POOL_USER_PROJECT",
          "credential_source": {
            "file": "PATH_TO_OIDC_CREDENTIALS"
          }
        }

4.  Open the gcloud CLI and run the following command:
    
        gcloud auth login --cred-file=PATH_TO_OIDC_CREDENTIALS
    
    Replace PATH\_TO\_OIDC\_CREDENTIALS with the path to the output file from a previous step.
    
    The gcloud CLI transparently posts your credentials to the Security Token Service endpoint. In the endpoint, it is exchanged for temporary Google Cloud access tokens.
    
    You can now run gcloud CLI commands to Google Cloud.

### SAML

1.  Sign in a user to your Microsoft Entra ID application and get the SAML response.

2.  Save the SAML response returned by Microsoft Entra ID in a secure location on your local machine, then store the path as follows:
    
        SAML_ASSERTION_PATH=SAML_ASSERTION_PATH

3.  To generate a credential configuration file, run the following command:
    
        gcloud iam workforce-pools create-cred-config \
            locations/global/workforcePools/WORKFORCE_POOL_ID/providers/WORKFORCE_PROVIDER_ID \
            --subject-token-type=urn:ietf:params:oauth:token-type:saml2 \
            --credential-source-file=SAML_ASSERTION_PATH  \
            --workforce-pool-user-project=PROJECT_ID  \
            --output-file=config.json
    
    Replace the following:
    
      - `  WORKFORCE_PROVIDER_ID  ` : the ID of the workforce identity pool provider that you created earlier in this guide
      - `  WORKFORCE_POOL_ID  ` : the ID of the workforce identity pool that you created earlier in this guide
      - `  SAML_ASSERTION_PATH  ` : the path of the SAML assertion file
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

4.  To login to the gcloud CLI using Workforce Identity Federation token exchange, run the following command:
    
        gcloud auth login --cred-file=config.json
    
    The gcloud CLI then transparently exchanges your Microsoft Entra ID credentials for temporary Google Cloud access tokens. The access tokens let you access Google Cloud.
    
    You see output similar to the following:
    
        Authenticated with external account user credentials for:
        [principal://iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID/subject/USER_ID].

5.  To list the credentialed accounts and your active account, run the following command:
    
        gcloud auth list

### Test Access

You now have access to the Google Cloud products that support Workforce Identity Federation and to which you are granted access. Earlier in this document, you [granted the Storage Admin role ( `roles/storage.admin` )](https://docs.cloud.google.com/iam/docs/workforce-sign-in-microsoft-entra-id-scalable-groups#grant-roles) to all of the identities within the group identifier that you specified in the `gcloud projects add-iam-policy-binding` for project `  TEST_PROJECT_ID  ` .

You can now test that you have access by listing Cloud Storage buckets.

### Console (federated)

To test that you have access using the console (federated), do the following:

  - Go to the Cloud Storage page.

  - Verify that you can see a list of existing buckets for the `  TEST_PROJECT_ID  ` .

### gcloud CLI

To test that you have access using the gcloud CLI, you can list Cloud Storage buckets and objects for the project that you have access to. To do this, run the following command. The principal must have the `serviceusage.services.use` permission on the specified project.

    gcloud storage ls --project="TEST_PROJECT_ID"

## Delete users

Workforce Identity Federation creates user metadata and resources for federated user identities. If you choose to delete users in your IdP you must also explicitly delete these resources in Google Cloud. To do so, see [Delete Workforce Identity Federation users and their data](https://docs.cloud.google.com/iam/docs/workforce-delete-user-data) .

You might see resources continue to be associated with a user that was deleted. This is because deleting user metadata and resources requires a long-running operation. After you initiate a deletion of a user's identity, processes that the user initiated before the deletion can continue to run until the processes complete or are canceled.

## What's next

  - [Configure SCIM in Microsoft Entra ID](https://docs.cloud.google.com/iam/docs/configure-scim-ms-entra)
  - [Delete Workforce Identity Federation users and their data](https://docs.cloud.google.com/iam/docs/workforce-delete-user-data)
  - Learn which Google Cloud products [support Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/federated-identity-supported-services)
  - [Set up user access to console (federated)](https://docs.cloud.google.com/iam/docs/workforce-console-sso)
