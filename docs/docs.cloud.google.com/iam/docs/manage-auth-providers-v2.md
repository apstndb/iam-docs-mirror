---
name: documents/docs.cloud.google.com/iam/docs/manage-auth-providers-v2
uri: https://docs.cloud.google.com/iam/docs/manage-auth-providers-v2
title: Manage Agent Identity auth providers
description: Manage Agent Identity auth providers, including editing details, enabling or disabling instances, and deleting or restoring them.
data_source: docs.cloud.google.com
---

> **Preview**
> 
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

In Agent Identity auth manager, you manage auth providers by editing their details, enabling or disabling them, or deleting and restoring them as needed.

> **Important:** This document shows how to manage auth providers by using the Agent Identity API. We recommend using the Agent Identity API because the [IAM Connectors API](https://docs.cloud.google.com/iam/docs/manage-auth-providers) [(preview)](https://docs.cloud.google.com/products#product-launch-stages) will not be [generally available](https://docs.cloud.google.com/products#product-launch-stages) . If you are using the IAM Connectors API, then [migrate to the Agent Identity API](https://docs.cloud.google.com/iam/docs/migrate-to-agent-identity-api) .

## Before you begin

1.  [Verify that you have chosen the correct authentication method](https://docs.cloud.google.com/iam/docs/agent-identity-overview#auth-models) .
2.  [Verify that you have the roles required to complete this task](https://docs.cloud.google.com/iam/docs/manage-auth-providers-v2#req-roles) .

### Required roles

To get the permissions that you need to manage Agent Identity auth providers, ask your administrator to grant you the [Agent Identity Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor) ( `roles/agentidentity.editor` ) IAM role on the project. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

This predefined role contains the permissions required to manage Agent Identity auth providers. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to manage Agent Identity auth providers:

  - `agentidentity.authProviders.update`
  - `agentidentity.authProviders.delete`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Edit an auth provider

To update the description or authentication details of an auth provider, use the Google Cloud console or the Google Cloud CLI.

To update an auth provider, run the following command:

    gcloud alpha agent-identity authProviders update AUTH_PROVIDER_NAME \    --location="LOCATION" \    --description="NEW_DESCRIPTION" \    --three-legged-oauth-client-id="NEW_CLIENT_ID" \    --three-legged-oauth-client-secret="NEW_CLIENT_SECRET" \    --three-legged-oauth-authorization-url="NEW_ENDPOINT"

Replace the following:

  - `  AUTH_PROVIDER_NAME  ` : The name of the auth provider.
  - `  LOCATION  ` : The location of the auth provider.
  - `  NEW_DESCRIPTION  ` : A new description for the auth provider.
  - `  NEW_CLIENT_ID  ` : A new client ID from your third-party application.
  - `  NEW_CLIENT_SECRET  ` : A new client secret from your third-party application.
  - `  NEW_ENDPOINT  ` : A new URL of the third-party authorization server.

## Enable or disable an auth provider

If you want to temporarily stop an agent from using an auth provider without deleting the auth provider, you can disable the auth provider. You can enable it again at any time.

1.  To enable an auth provider, run the following command:
    
        gcloud alpha agent-identity authProviders enable AUTH_PROVIDER_NAME \    --location="LOCATION"

2.  To disable an auth provider, run the following command:
    
        gcloud alpha agent-identity authProviders disable AUTH_PROVIDER_NAME \    --location="LOCATION"

Replace the following:

  - `  AUTH_PROVIDER_NAME  ` : The name of the auth provider.
  - `  LOCATION  ` : The location of the auth provider.

## Delete an auth provider

When you no longer need an auth provider, you can delete it. Deleting an auth provider disables it and places it in a soft-delete state for 30 days. During this period, you can restore the auth provider if you want to. After 30 days, it takes one additional day for its policy to be purged, at which point you can create an auth provider with the same name.

To delete an auth provider, run the following command:

    gcloud alpha agent-identity authProviders delete AUTH_PROVIDER_NAME \    --location="LOCATION"

Replace the following:

  - `  AUTH_PROVIDER_NAME  ` : The name of the auth provider.
  - `  LOCATION  ` : The location of the auth provider.

## Restore a deleted auth provider

If you accidentally delete an auth provider, you can restore it from its soft-delete state within 30 days of deletion. During this period, you can restore the auth provider if you want to. After 30 days, it takes one additional day for its policy to be purged, at which point you can create an auth provider with the same name.

To restore an auth provider, run the following command:

    gcloud alpha agent-identity authProviders undelete AUTH_PROVIDER_NAME \    --location="LOCATION"

Replace the following:

  - `  AUTH_PROVIDER_NAME  ` : The name of the auth provider.
  - `  LOCATION  ` : The location of the auth provider.

## What's next

  - [Authenticate using 2-legged OAuth with auth manager](https://docs.cloud.google.com/iam/docs/auth-with-2lo-v2)
  - [Authenticate using 3-legged OAuth with auth manager](https://docs.cloud.google.com/iam/docs/auth-with-3lo-v2)
  - [Authenticate using API key with auth manager](https://docs.cloud.google.com/iam/docs/auth-with-api-key-v2)
  - [Agent Identity overview](https://docs.cloud.google.com/iam/docs/agent-identity-overview)
  - [Troubleshoot Agent Identity auth manager](https://docs.cloud.google.com/iam/docs/troubleshoot-auth-manager)
