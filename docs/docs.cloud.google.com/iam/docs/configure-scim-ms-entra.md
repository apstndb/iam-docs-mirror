---
name: documents/docs.cloud.google.com/iam/docs/configure-scim-ms-entra
uri: https://docs.cloud.google.com/iam/docs/configure-scim-ms-entra
title: Configure SCIM in Microsoft Entra ID
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

> **Important:** SCIM is available only for Gemini Enterprise.

This document describes how to configure a SCIM tenant in a workforce identity pool. To learn more about SCIM, see [SCIM provisioning for Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/workforce-identity-federation-scim) .

Each workforce identity pool supports only one SCIM tenant. To configure a new SCIM tenant in a pool that already has one, you must first [hard-delete the existing tenant](https://docs.cloud.google.com/iam/docs/configure-scim-ms-entra#delete-scim-tenant) .

The `--claim-mapping` flag for a SCIM tenant can contain only specific Common Expression Language (CEL) expressions. To learn which expressions are supported, see [Map token and SCIM attributes](https://docs.cloud.google.com/iam/docs/configure-scim-ms-entra#token-scim-mapping) .

> **Important:** Make sure that your IdP provides unique values for the attributes that you map to `google.subject` and `google.group` using SCIM. To learn more, see [SCIM support](https://docs.cloud.google.com/iam/docs/workforce-identity-federation-scim) .

To configure [System for Cross-domain Identity Management (SCIM)](https://docs.cloud.google.com/iam/docs/workforce-identity-federation-scim) , do the following:

1.  [Configure a SCIM tenant and token in Google Cloud](https://docs.cloud.google.com/iam/docs/configure-scim-ms-entra#configure-scim-tenant-token-gcp)
2.  [Configure SCIM in Microsoft Entra ID](https://docs.cloud.google.com/iam/docs/configure-scim-ms-entra#configure-scim-idp)
3.  [Update the provider to enable SCIM](https://docs.cloud.google.com/iam/docs/configure-scim-ms-entra#update-provider-enable-scim)
4.  [Verify SCIM synchronization](https://docs.cloud.google.com/iam/docs/configure-scim-ms-entra#verify-sync)

## Configure a SCIM tenant and token in Google Cloud

To configure a SCIM tenant in Google Cloud, do the following:

1.  Create a SCIM tenant.
    
    ``` 
        gcloud iam workforce-pools providers scim-tenants create SCIM_TENANT_ID \
            --workforce-pool="WORKFORCE_POOL_ID" \
            --provider="PROVIDER_ID" \
            --display-name="SCIM_TENANT_DISPLAY_NAME" \
            --description="SCIM_TENANT_DESCRIPTION" \
            --claim-mapping="CLAIM_MAPPING" \
            --location="global"
        
    ```
    
    Replace the following:
    
      - `  SCIM_TENANT_ID  ` : an ID for your SCIM tenant.
    
      - `  WORKFORCE_POOL_ID  ` : the ID of the workforce pool that you created earlier in this document.
    
      - `  PROVIDER_ID  ` : the ID of the workforce identity pool provider that you created earlier in this document.
    
      - `  SCIM_TENANT_DISPLAY_NAME  ` : a display name for your SCIM tenant.
    
      - `  SCIM_TENANT_DESCRIPTION  ` : a description for your SCIM tenant.
    
      - `  CLAIM_MAPPING  ` : a comma-separated list of attribute mappings. For the extended list of mapping attributes, see [Map token and SCIM attributes](https://docs.cloud.google.com/iam/docs/configure-scim-ms-entra#token-scim-mapping) . The following mapping is recommended for Gemini Enterprise:
        
            google.subject=user.emails[0].value.lowerAscii(),google.group=group.externalId
        
        The `google.subject` attribute that you map in the SCIM tenant must uniquely refer to the same identities that are mapped in the `google.subject` attribute in the workforce identity pool provider by using the `--attribute-mapping` flag. After the SCIM tenant is created, you can't update the claim mapping. To replace it, you can [hard-delete the SCIM tenant](https://docs.cloud.google.com/iam/docs/configure-scim-ms-entra#delete-scim-tenant) and immediately create a new one. To learn more about considerations for using SCIM, see [SCIM support](https://docs.cloud.google.com/iam/docs/workforce-identity-federation-scim) .

2.  When the command completes, do the following:
    
    1.  In the `baseUri` field in the output, save the entire URI, which is formatted as ` https://iamscim.googleapis.com/v1alpha1/tenants/ SCIM_TENANT_UID  ` . You need to provide this URI to your IdP.
    2.  Additionally, from the URI, save only the `  SCIM_TENANT_UID  ` . You need this UID to set an IAM allow policy on the SCIM tenant later in this document.

3.  Create a SCIM token:
    
    ``` 
        gcloud iam workforce-pools providers scim-tenants tokens create SCIM_TOKEN_ID \
            --display-name DISPLAY_NAME \
            --scim-tenant SCIM_TENANT_ID \
            --workforce-pool WORKFORCE_POOL_ID \
            --provider PROVIDER_ID \
            --location global
        
    ```
    
    Replace the following:
    
      - `  SCIM_TOKEN_ID  ` : an ID for the SCIM token
      - `  DISPLAY_NAME  ` : the display name of the SCIM token
      - `  WORKFORCE_POOL_ID  ` : the ID of the workforce pool
      - `  SCIM_TENANT_ID  ` : the ID of the SCIM tenant
      - `  PROVIDER_ID  ` : the ID of the workforce identity pool provider

4.  
    
    <div id="create-scim-token-complete">
    
    When the `gcloud iam workforce-pools providers scim-tenants tokens create` command completes, do the following:
    
    1.  In the output, save the value of `  SCIM_TOKEN  ` in the `securityToken` field. You need to provide this security token to your IdP. The security token is displayed only in this output, and if it's lost, you must create a new SCIM token.
    
    2.  To check if `  SCIM_TOKEN  ` is rejected by your organization policy, run the following command:
        
            curl -v -H "Authorization: Bearer SCIM_TOKEN"  https://iamscim.googleapis.com/v1alpha1/tenants/SCIM_TENANT_UID/Users
        
        If the command fails with a permissions-related error, run `gcloud organizations add-iam-policy-binding` , described in a later step. If the command succeeds, you can skip that step.
    
    </div>

5.  Set an IAM allow policy on the SCIM tenant and token. If the [`curl` command](https://docs.cloud.google.com/iam/docs/configure-scim-ms-entra#create-scim-token-complete) in a previous step failed with a permissions-related error, you must run the following command:
    
    ``` 
        gcloud organizations add-iam-policy-binding ORGANIZATION_ID \
            --member=serviceAccount:SERVICE_AGENT_EMAIL \
            --role roles/iam.scimSyncer
        
    ```
    
    Replace the following:
    
      - ORGANIZATION\_ID : the ID of the organization.
      - SERVICE\_AGENT\_EMAIL : the email address of the service agent. The email address is in the following format: `o- ORGANIZATION_ID - SCIM_TENANT_UID @gcp-sa-iamscim.iam.gserviceaccount.com` . SCIM\_TENANT\_UID is returned when you create the SCIM tenant.

When you provision groups in your IdP, make sure that each group's display name, as provided in the `displayName` field, is unique within a SCIM tenant. To learn more about groups and SCIM in Microsoft Entra ID, see [Groups](https://learn.microsoft.com/en-us/entra/identity/app-provisioning/use-scim-to-provision-users-and-groups#groups) .

## Configure SCIM in Microsoft Entra ID

To configure SCIM in Microsoft Entra ID, do the following:

1.  Open the Azure portal and sign in as a user that has global administrator privileges.
2.  Select **Microsoft Entra ID** \> **Enterprise Apps** .
3.  Click **New application** .
4.  In **Browse Microsoft Entra App gallery** , click **Create your own application** .
5.  In the **Create your own application** panel that appears, do the following:
    1.  For **What's the name of your app** , enter the name of your app.
    2.  Select **Integrate any other application you don't find in gallery (Non-gallery)** .
    3.  To create the app, click **Create** .
6.  In your application, do the following:
    1.  In the **Manage** section, click **Provisioning** .
    
    2.  In the right pane that appears, click **New Configuration** .
    
    3.  Under the **Admin Credentials** , in the **Tenant URL** , enter the SCIM URL that you obtained when you created the SCIM tenant, appended with `?aadOptscim062020` . You must append `?aadOptscim062020` to the end of the base URI.
        
        This query parameter is required by Microsoft Entra ID to ensure that SCIM PATCH requests are compliant with SCIM RFC standards. For more details, see [Microsoft's documentation](https://learn.microsoft.com/en-us/entra/identity/app-provisioning/application-provisioning-config-problem-scim-compatibility#scim-20-compliance-issues-and-status) .
        
        The final Tenant URL in Microsoft Entra ID should be in the following format:
        
            https://iamscim.googleapis.com/v1alpha1/tenants/SCIM_TENANT_UID?aadOptscim062020
        
        Replace `  SCIM_TENANT_UID  ` with the SCIM tenant UID.
    
    4.  In **Secret token** , enter the secret token that you obtained when you created the SCIM token.
    
    5.  To test the SCIM configuration with Workforce Identity Federation, click **Test connection** .
    
    6.  To save the configuration, click **Create** .
7.  In the **Manage** section, do the following:
    1.  Click **Attribute mapping** .
    2.  Click **Provision Microsoft Entra ID Users** .
    3.  In the **Attribute Mapping** page, do the following:
        1.  In the **Attribute mappings** table, find the row for externalId and click **Edit** in that row. In the **Edit attributes** page, do the following:
            1.  In the **Source attribute** drop-down list, select `objectId` .
            2.  Click **Ok** .
        2.  To save the attribute mapping, click **Save** .

## Update the provider to enable SCIM

To enable SCIM for a provider, do the following:

### OIDC

``` 
      gcloud iam workforce-pools providers update-oidc PROVIDER_ID \
          --workforce-pool=WORKFORCE_POOL_ID \
          --location=LOCATION \
          --scim-usage=enabled-for-groups
    
```

Replace the following:

  - `  PROVIDER_ID  ` : the ID of the workforce identity pool provider
  - `  WORKFORCE_POOL_ID  ` : the ID of the workforce pool
  - `  LOCATION  ` : the location of the workforce pool

### SAML

``` 
      gcloud iam workforce-pools providers update-saml PROVIDER_ID \
          --workforce-pool=WORKFORCE_POOL_ID \
          --location=LOCATION \
          --scim-usage=enabled-for-groups
    
```

Replace the following:

  - `  PROVIDER_ID  ` : the ID of the workforce identity pool provider
  - `  WORKFORCE_POOL_ID  ` : the ID of the workforce pool
  - `  LOCATION  ` : the location of the workforce pool

To verify SCIM synchronization, see [Verify SCIM synchronization](https://docs.cloud.google.com/iam/docs/configure-scim-ms-entra#verify-sync) .

## Map token and SCIM attributes

You must consistently map attributes, both in the workforce identity pool provider and in the SCIM tenant that's configured for the provider. For the workforce identity pool provider, you use the `--attribute-mapping` flag, and for the SCIM tenant, you use the `--claim-mapping` flag. The IdP attribute that is mapped to `google.subject` for users must uniquely refer to the same identity, whether defined in a token or SCIM mapping. To learn more about mapping attributes when you use SCIM, see the [SCIM support](https://docs.cloud.google.com/iam/docs/workforce-identity-federation-scim) section. The following table shows you how to map attributes in token claims and SCIM attributes:

| Google attribute                                                                         | Workforce identity pool provider mapping                                                                     | SCIM tenant mapping                 |
| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ | ----------------------------------- |
| `google.subject`                                                                         | `assertion.oid`                                                                                              | `user.externalId`                   |
| `google.subject`                                                                         | `assertion.attributes['http://schemas.microsoft.com/identity/claims/objectidentifier'][0]`                   | `user.externalId`                   |
| `google.subject`                                                                         | `assertion.email`                                                                                            | `user.emails[0].value`              |
| `google.subject`                                                                         | `assertion.attributes['http://schemas.xmlsoap.org/ws/2005/05/identity/claims/emailaddress'][0]`              | `user.emails[0].value`              |
| `google.subject`                                                                         | `assertion.email.lowerAscii()`                                                                               | `user.emails[0].value.lowerAscii()` |
| `google.subject`                                                                         | `assertion.attributes['http://schemas.xmlsoap.org/ws/2005/05/identity/claims/emailaddress'][0].lowerAscii()` | `user.emails[0].value.lowerAscii()` |
| `google.subject`                                                                         | `assertion.preferred_username`                                                                               | `user.userName`                     |
| `google.subject`                                                                         | `assertion.attributes['http://schemas.xmlsoap.org/ws/2005/05/identity/claims/name'][0]`                      | `user.userName`                     |
| `google.subject`                                                                         | `assertion.preferred_username.lowerAscii()`                                                                  | `user.userName.lowerAscii()`        |
| `google.subject`                                                                         | `assertion.attributes['http://schemas.xmlsoap.org/ws/2005/05/identity/claims/name'][0].lowerAscii()`         | `user.userName.lowerAscii()`        |
| `google.group` make sure you update your provider with `--scim-usage=enabled-for-groups` | `N/A`                                                                                                        | `group.externalId`                  |

## Verify SCIM synchronization

After configuring SCIM, you can use `curl` to verify that users and groups are syncing correctly to Google Cloud. These commands require a valid SCIM token and your SCIM tenant ID.

### Verify user sync

To verify that a user synced correctly, search for the user's `userName` by using the following filter:

    curl -H "Authorization: Bearer SCIM_TOKEN" \
      "https://iamscim.googleapis.com/v1alpha1/tenants/SCIM_TENANT_UID/Users?filter=userName%20eq%20%22USER_NAME%22"

Example response:

    {
      "schemas": ["urn:ietf:params:scim:api:messages:2.0:ListResponse"],
      "totalResults": 1,
      "Resources": [
        {
          "id": "USER_ID",
          "userName": "USER_NAME",
          ...
        }
      ]
    }

### Verify group sync

To verify that a group synced correctly, search for the group's `displayName` by using the following filter:

    curl -H "Authorization: Bearer SCIM_TOKEN" \
      "https://iamscim.googleapis.com/v1alpha1/tenants/SCIM_TENANT_UID/Groups?filter=displayName%20eq%20%22GROUP_NAME%22"

Example response:

    {
      "schemas": ["urn:ietf:params:scim:api:messages:2.0:ListResponse"],
      "totalResults": 1,
      "Resources": [
        {
          "id": "GROUP_ID",
          "displayName": "GROUP_NAME",
          ...
        }
      ]
    }

### Verify group membership

To verify if a specific user is a member of a group, use a filter that specifies both the group ID and the user ID.

    curl -H "Authorization: Bearer SCIM_TOKEN" \
      "https://iamscim.googleapis.com/v1alpha1/tenants/SCIM_TENANT_UID/Groups?filter=id%20eq%20%22GROUP_ID%22%20and%20members%20eq%20%22USER_ID%22"

Example response if the user is a member:

    {
      "schemas": ["urn:ietf:params:scim:api:messages:2.0:ListResponse"],
      "totalResults": 1,
      "Resources": [
        {
          "id": "GROUP_ID",
          "displayName": "GROUP_NAME",
          ...
        }
      ]
    }

Example response if the user is not a member:

    {
      "schemas": ["urn:ietf:params:scim:api:messages:2.0:ListResponse"],
      "totalResults": 0,
      "Resources": []
    }

**Note:** To obtain the `GROUP_ID` and `USER_ID` , first find the group and user using the `displayName` and `userName` filters. The IDs are returned in the `id` field of the response. Replace `SCIM_TOKEN` , `SCIM_TENANT_UID` , `USER_NAME` , `GROUP_NAME` , `GROUP_ID` , and `USER_ID` with your actual values.

## Force delete a SCIM tenant

To force delete a SCIM tenant, do the following:

1.  If `--scim-usage=enabled-for-groups` is set for your provider, disable it from the provider configuration:
    
    ``` 
              gcloud iam workforce-pools providers update-oidc PROVIDER_ID \
                  --workforce-pool=WORKFORCE_POOL_ID \
                  --location=LOCATION \
                  --scim-usage=SCIM_USAGE_UNSPECIFIED
            
    ```
    
    Replace the following:
    
      - `  PROVIDER_ID  ` : the ID of the workforce identity pool provider
      - `  WORKFORCE_POOL_ID  ` : the ID of the workforce pool
      - `  LOCATION  ` : the location of the workforce pool

2.  Delete the SCIM tenant:
    
    ``` 
      gcloud iam workforce-pools providers scim-tenants delete SCIM_TENANT_ID \
          --workforce-pool=WORKFORCE_POOL_ID \
          --provider=PROVIDER_ID \
          --hard-delete \
          --location=global
    ```
    
    Replace the following:
    
      - `  SCIM_TENANT_ID  ` : the ID of the SCIM tenant to delete
      - `  WORKFORCE_POOL_ID  ` : the ID of the workforce pool
      - `  PROVIDER_ID  ` : the ID of the workforce identity pool provider
    
    To learn more about SCIM, including deleting SCIM tenants, see [SCIM support](https://docs.cloud.google.com/iam/docs/workforce-identity-federation-scim) .

## What's next

  - [Delete Workforce Identity Federation users and their data](https://docs.cloud.google.com/iam/docs/workforce-delete-user-data)
  - Learn which Google Cloud products [support Workforce Identity Federation](https://docs.cloud.google.com/iam/docs/federated-identity-supported-services)
  - [Set up user access to console (federated)](https://docs.cloud.google.com/iam/docs/workforce-console-sso)
