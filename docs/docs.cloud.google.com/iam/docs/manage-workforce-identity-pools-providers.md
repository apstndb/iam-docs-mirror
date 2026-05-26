---
name: documents/docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers
uri: https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers
title: Manage workforce identity pool providers
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This guide describes how you can perform common operations with Workforce Identity Federation. To set up Workforce Identity Federation, see the following guides:

  - [Configure Workforce Identity Federation with Microsoft Entra ID and sign in users](https://docs.cloud.google.com/iam/docs/workforce-sign-in-microsoft-entra-id)
  - [Configure Workforce Identity Federation with Okta and sign in users](https://docs.cloud.google.com/iam/docs/workforce-sign-in-okta)
  - [Configure Workforce Identity Federation on an IdP that supports OIDC or SAML](https://docs.cloud.google.com/iam/docs/configuring-workforce-identity-federation)

## Before you begin

1.  You must have a Google Cloud organization set up.

2.  [Install](https://docs.cloud.google.com/sdk/docs/install) the Google Cloud CLI. After installation, [initialize](https://docs.cloud.google.com/sdk/docs/initializing) the Google Cloud CLI by running the following command:
    
        gcloud init
    
    If you're using an external identity provider (IdP), you must first [sign in to the gcloud CLI with your federated identity](https://docs.cloud.google.com/iam/docs/workforce-log-in-gcloud) .
    
    > **Note:** If you installed the gcloud CLI previously, make sure you have the latest version by running `gcloud components update` .

## Manage pools

This section shows you how to manage workforce identity pools.

### Create a pool

To create a workforce pool, execute the following command:

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

### Describe a pool

### gcloud

To describe a specific workforce pool using the gcloud CLI, execute the following command:

    gcloud iam workforce-pools describe WORKFORCE_POOL_ID \
        --location=global

Replace `  WORKFORCE_POOL_ID  ` with the workforce pool ID that you chose when you created the pool.

### Console

To describe a specific workforce pool using the Google Cloud console, do the following:

1.  Go to the **Workforce Identity Pools** page:

2.  In **Workforce pools** , select the pool

### List pools

### gcloud

To list the workforce pools in the organization, execute the following command:

    gcloud iam workforce-pools list \
        --organization=ORGANIZATION_ID \
        --location=global

Replace ORGANIZATION\_ID with your organization ID.

### Console

To list workforce pools using the Google Cloud console, do the following:

1.  Go to the **Workforce Identity Pools** page:

2.  In the table, view the list of pools.

### Update a pool

### gcloud

To update a specific workforce pool, execute the following command:

    gcloud iam workforce-pools update WORKFORCE_POOL_ID \
        --description=DESCRIPTION \
        --location=global

Replace the following:

  - `  WORKFORCE_POOL_ID  ` : the workforce pool ID
  - `  DESCRIPTION  ` : the description of the pool

### Console

To update a specific workforce pool using the Google Cloud console, do the following:

1.  Go to the **Workforce Identity Pools** page:

2.  In the table, select the pool.

3.  Update the pool parameters.

4.  Click **Save Pool** .

### Delete a pool

### gcloud

To delete a workforce identity pool, execute the following command:

    gcloud iam workforce-pools delete WORKFORCE_POOL_ID \
        --location=global

Replace `  WORKFORCE_POOL_ID  ` with the workforce pool ID.

### Console

To delete a specific workforce pool using the Google Cloud console, do the following:

1.  Go to the **Workforce Identity Pools** page:

2.  In **Workforce pools** , click more\_vert **Delete** on the pool you want to delete.

3.  Follow additional instructions.

### Undelete a pool

You can undelete a workforce identity pool that was deleted within the last 30 days.

To undelete a pool, execute the following command:

    gcloud iam workforce-pools undelete WORKFORCE_POOL_ID \
        --location=global

Replace `  WORKFORCE_POOL_ID  ` with the workforce pool ID.

## Configure a provider within the workforce pool

This section explains how you can use `gcloud` commands to configure workforce identity pool providers:

### Create an OIDC provider

This section describes how to create a workforce identity pool provider for an OIDC IdP.

### gcloud

### Code flow

To create an OIDC provider that uses [authorization code flow](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#oidc-flow-types) for web sign-in, run the following command:

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

  - `  WEB_SSO_ADDITIONAL_SCOPES  ` : Optional additional scopes to send to the OIDC IdP for console (federated) or gcloud CLI browser-based sign-in.

  - `  ATTRIBUTE_MAPPING  ` : An [attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) . The following is an example of an attribute mapping:
    
        google.subject=assertion.oid
        google.groups=assertion.groups,
        attribute.costcenter=assertion.costcenter
    
    This example maps the IdP attributes `assertion.oid` , `assertion.groups` , and `assertion.costcenter` in the OIDC assertion to the Google Cloud attributes `google.subject` , `google.groups` , and `attribute.costcenter` , respectively.

  - `  ATTRIBUTE_CONDITION  ` : An [attribute condition](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) ; for example, `assertion.role == 'gcp-users'` . This example condition ensures that only users with the role `gcp-users` can sign in using this provider.
    
    > **Warning:** If your multi-tenant IdP has a single issuer URI, you must use [attribute conditions](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) to ensure that access is restricted to the correct tenant. For more information, see [Use attribute conditions when federating with GitHub or other multi-tenant identity providers](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#use-attribute-conditions-multitenant) .

  - `  JWK_JSON_PATH  ` : An optional path to a [locally uploaded OIDC JWKs](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#json-web-keys) . If this parameter isn't supplied, Google Cloud instead uses your IdP's `/.well-known/openid-configuration` path to source the JWKs containing the public keys. For more information about locally uploaded OIDC JWKs, see [manage OIDC JWKs](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#manage-oidc-keys) .
    
    > **Note:** Local OIDC JWKs can be uploaded through [implicit flow or code flow](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#oidc-flow-types) , but can only be used in [programmatic flow](https://docs.cloud.google.com/iam/docs/workforce-obtaining-short-lived-credentials) , in which you directly call the STS `/token` endpoint with a credential from the third-party IdP to exchange for a Google Cloud access token for your workforce pool. You can't use local OIDC JWKs when signing in to the console (federated).

  - Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
    
    To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .

In the command response, POOL\_RESOURCE\_NAME is the name of the pool; for example, `locations/global/workforcePools/enterprise-example-organization-employees` .

### Implicit flow

To create an OIDC workforce identity pool provider that uses the [implicit flow](https://openid.net/specs/openid-connect-core-1_0.html#ImplicitFlowAuth) for web sign-in, run the following command:

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

  - `  WEB_SSO_ADDITIONAL_SCOPES  ` : Optional additional scopes to send to the OIDC IdP for console (federated) or gcloud CLI browser-based sign-in.

  - `  ATTRIBUTE_MAPPING  ` : An [attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) . The following is an example of an attribute mapping:
    
        google.subject=assertion.oid
        google.groups=assertion.groups,
        attribute.costcenter=assertion.costcenter
    
    This example maps the IdP attributes `assertion.oid` , `assertion.groups` , and `assertion.costcenter` in the OIDC assertion to the Google Cloud attributes `google.subject` , `google.groups` , and `attribute.costcenter` , respectively.

  - `  ATTRIBUTE_CONDITION  ` : An [attribute condition](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) ; for example, `assertion.role == 'gcp-users'` . This example condition ensures that only users with the role `gcp-users` can sign in using this provider.
    
    > **Warning:** If your multi-tenant IdP has a single issuer URI, you must use [attribute conditions](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) to ensure that access is restricted to the correct tenant. For more information, see [Use attribute conditions when federating with GitHub or other multi-tenant identity providers](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#use-attribute-conditions-multitenant) .

  - `  JWK_JSON_PATH  ` : An optional path to a [locally uploaded OIDC JWKs](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#json-web-keys) . If this parameter isn't supplied, Google Cloud instead uses your IdP's `/.well-known/openid-configuration` path to source the JWKs containing the public keys. For more information about locally uploaded OIDC JWKs, see [manage OIDC JWKs](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#manage-oidc-keys) .
    
    > **Note:** Local OIDC JWKs can be uploaded through [implicit flow or code flow](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#oidc-flow-types) , but can only be used in [programmatic flow](https://docs.cloud.google.com/iam/docs/workforce-obtaining-short-lived-credentials) , in which you directly call the STS `/token` endpoint with a credential from the third-party IdP to exchange for a Google Cloud access token for your workforce pool. You can't use local OIDC JWKs when signing in to the console (federated).

  - Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
    
    To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .

In the command response, POOL\_RESOURCE\_NAME is the name of the pool; for example, `locations/global/workforcePools/enterprise-example-organization-employees` .

### Console

### Code flow

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
        2.  In the **Attribute Conditions** field, enter a condition in [CEL format](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) ; for example, `assertion.role == 'gcp-users'` . This example condition ensures that only users with the role `gcp-users` can sign in using this provider.
    
    4.  To turn on detailed audit logging, in **Detailed logging** , click the **Enable attribute value audit logging** toggle.
        
        Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
        
        To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .

12. To create the provider, click **Submit** .

### Implicit flow

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
        2.  In the **Attribute Conditions** field, enter a condition in [CEL format](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) ; for example, `assertion.role == 'gcp-users'` . This example condition ensures that only users with the role `gcp-users` can sign in using this provider.
    
    4.  To turn on detailed audit logging, in **Detailed logging** , click the **Enable attribute value audit logging** toggle.
        
        Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .
        
        To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .

12. To create the provider, click **Submit** .

### Create a SAML provider

This section describes how to create a workforce identity pool provider for a SAML IdP.

### gcloud

To create the provider, run the following command:

    gcloud iam workforce-pools providers create-saml WORKFORCE_PROVIDER_ID \
        --workforce-pool="WORKFORCE_POOL_ID" \
        --attribute-mapping="ATTRIBUTE_MAPPING" \
        --attribute-condition="ATTRIBUTE_CONDITION" \
        --idp-metadata-path="XML_METADATA_PATH" \
        --detailed-audit-logging \
        --location="global"

Replace the following:

  - `  WORKFORCE_PROVIDER_ID  ` : the workforce provider ID

  - `  WORKFORCE_POOL_ID  ` : the workforce pool ID

  - `  ATTRIBUTE_MAPPING  ` : an [attribute mapping](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-mappings) ; for example, to map a subject, the attribute mapping is as follows:
    
        google.subject=assertion.subject,
        google.groups=assertion.attributes['https://example.com/aliases'],
        attribute.department=assertion.attributes.department[0]

  - `  ATTRIBUTE_CONDITION  ` : an optional [attribute condition](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#attribute-conditions) ; for example, `assertion.subject.endsWith("@example.com")`

  - `  XML_METADATA_PATH  ` : the path to the XML-formatted metadata file from your IdP

> **Note:** To map a large number of groups (up to 400), you can use [extra attributes](https://docs.cloud.google.com/iam/docs/workforce-sign-in-microsoft-entra-id-scalable-groups) .

The prefix `gcp-` is reserved and can't be used in a workforce identity pool or workforce identity pool provider ID.

This command assigns the subject and department in the SAML assertion to `google.subject` and `attribute.department` attributes, respectively. Additionally, the attribute condition ensures that only users with a subject ending in `@example.com` can sign in using this workforce provider.

Workforce Identity Federation *detailed audit logging* logs information received from your IdP to Logging. Detailed audit logging can help you troubleshoot your workforce identity pool provider configuration. To learn how to troubleshoot attribute mapping errors with detailed audit logging, see [General attribute mapping errors](https://docs.cloud.google.com/iam/docs/troubleshooting-workforce-identity-federation#general-attribute-mapping-errors) . To learn about Logging pricing, see [Google Cloud Observability pricing](https://docs.cloud.google.com/stackdriver/pricing#logs-costs) .

To disable detailed audit logging for a workforce identity pool provider, omit the `--detailed-audit-logging` flag when you run `gcloud iam workforce-pools providers create` . To disable detailed audit logging, you can also [update the provider](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) .

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

### Describe a provider

### gcloud

To describe a provider, run the following command:

    gcloud iam workforce-pools providers describe PROVIDER_ID \
        --workforce-pool=WORKFORCE_POOL_ID \
        --location=global

Replace the following:

  - `  PROVIDER_ID  ` : the provider ID
  - `  WORKFORCE_POOL_ID  ` : the workforce pool ID

### Console

To view a provider, do the following:

1.  Go to the **Workforce Identity Pools** page:

<!-- end list -->

1.  In the table, select the pool for which you want to view the provider.

2.  In the **Providers** table, select the provider.

### List providers

### gcloud

To list providers, execute the following command:

    gcloud iam workforce-pools providers list \
        --workforce-pool=WORKFORCE_POOL_ID \
        --location=global

Replace `  WORKFORCE_POOL_ID  ` with the workforce pool ID.

### Console

To view a provider, do the following:

1.  Go to the **Workforce Identity Pools** page:

<!-- end list -->

1.  In the table, select the pool for which you want to list the providers.

2.  In the **Providers** table you can see a list of providers.

### Update a provider

### gcloud

To update an OIDC provider after creation, execute the following command:

    gcloud iam workforce-pools providers update-oidc PROVIDER_ID \
        --workforce-pool=WORKFORCE_POOL_ID \
        --description="DESCRIPTION" \
        --detailed-audit-logging \
        --location=global

Replace the following:

  - `  PROVIDER_ID  ` : the provider ID
  - `  WORKFORCE_POOL_ID  ` : the workforce pool ID
  - `  DESCRIPTION  ` : the description
  - To enable [detailed audit logging](https://docs.cloud.google.com/iam/docs/workforce-identity-federation#detailed-audit-logging) , add the `--detailed-audit-logging` flag to `gcloud iam workforce-pools providers update` . To disable detailed audit logging, add the `--no-detailed-audit-logging` flag to the update command.

### Console

To view a provider, do the following:

1.  Go to the **Workforce Identity Pools** page:

<!-- end list -->

1.  In the table, select the pool for which you want to view the provider.

2.  In the **Providers** table, click more\_vert **Edit** .

3.  Update the provider.

4.  To save the updated provider, click **Save** .

### Delete a provider

To delete a provider, execute the following command:

    gcloud iam workforce-pools providers delete PROVIDER_ID \
        --workforce-pool=WORKFORCE_POOL_ID \
        --location=global

Replace the following:

  - `  PROVIDER_ID  ` : the provider ID
  - `  WORKFORCE_POOL_ID  ` : the workforce pool ID

### Undelete a provider

To undelete a provider deleted within the last 30 days, execute the following command:

    gcloud iam workforce-pools providers undelete PROVIDER_ID \
        --workforce-pool=WORKFORCE_POOL_ID \
        --location=global

Replace the following:

  - `  PROVIDER_ID  ` : the provider ID
  - `  WORKFORCE_POOL_ID  ` : the workforce pool ID

## Manage OIDC JWKs

This section shows you how to manage OIDC JWKs in workforce pool providers.

### Create a provider and upload OIDC JWKs

To create OIDC JWKs, see [JWT, JWS, JWE, JWK, and JWA Implementations](https://openid.net/developers/jwt/) .

To upload an OIDC JWK file when you create a workforce pool provider, run the [gcloud iam workforce-pools providers create-oidc](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#create-oidc-provider) command with `--jwk-json-path=" JWK_JSON_PATH "` . Replace `  JWK_JSON_PATH  ` with the path to the JWKs JSON file.

This operation uploads the keys from the file.

### Update OIDC JWKs

To update OIDC JWKs, run the [gcloud iam workforce-pools providers update-oidc](https://docs.cloud.google.com/iam/docs/manage-workforce-identity-pools-providers#update-oidc-provider) command with `--jwk-json-path=" JWK_JSON_PATH "` . Replace `  JWK_JSON_PATH  ` with the path to the JWKs JSON file.

This operation replaces any existing uploaded keys with the ones in the file.

### Delete all uploaded OIDC JWKs

To delete all of the uploaded OIDC JWKs and instead use the issuer URI to fetch the keys, run the [gcloud iam workforce-pools providers update-oidc](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workforce-pools/providers/update-oidc) command with `--jwk-json-path=" JWK_JSON_PATH "` . Replace `  JWK_JSON_PATH  ` with the path to an empty file. Use the `--issuer-uri` flag to set the issuer URI.

This operation deletes all of your existing uploaded keys.

## What's next

  - [Configure Workforce Identity Federation with Microsoft Entra ID and sign in users](https://docs.cloud.google.com/iam/docs/workforce-sign-in-microsoft-entra-id)
  - [Configure Workforce Identity Federation with Okta and sign in users](https://docs.cloud.google.com/iam/docs/workforce-sign-in-okta)
  - [Delete Workforce Identity Federation users and their data](https://docs.cloud.google.com/iam/docs/workforce-delete-user-data)
  - Learn which Google Cloud products [support Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/federated-identity-supported-services)
