---
name: documents/docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers
uri: https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers
title: Manage workload identity pools and providers
description: Manage workload identity pools and providers. Create, list, get, update, delete, and restore them. Use the {{dynamic_data.site_values.cloud_name_short}} console, Google Cloud CLI, or the REST API.
data_source: docs.cloud.google.com
---

Workload Identity Federation lets you grant external workloads access to Google Cloud resources through [workload identity pools](https://docs.cloud.google.com/iam/docs/workload-identity-federation) and connected identity providers (IdPs). As your requirements change, you can create, view, update, delete, or undelete pools and providers by using the Google Cloud console, the [Google Cloud CLI](https://docs.cloud.google.com/sdk/gcloud) , or the [REST API](https://docs.cloud.google.com/iam/docs/reference/rest) .

## Before you begin

Create a workload identity pool. For instructions, see the [Workload Identity Federation configuration guides](https://docs.cloud.google.com/iam/docs/workload-identity-federation#providers) .

### Required roles

To get the permissions that you need to manage workload identity pools and providers, ask your administrator to grant you the following IAM roles on the project:

- To view pools and providers: [IAM Workload Identity Pool Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer) ( `roles/iam.workloadIdentityPoolViewer` )
- To view, create, update, and delete pools and providers: [IAM Workload Identity Pool Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin) ( `roles/iam.workloadIdentityPoolAdmin` )

For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

These predefined roles contain the permissions required to manage workload identity pools and providers. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to manage workload identity pools and providers:

- To view workload identity pools and providers:
  - `iam.googleapis.com/workloadIdentityPoolProviders.get`
  - `iam.googleapis.com/workloadIdentityPoolProviders.list`
  - `iam.googleapis.com/workloadIdentityPools.get`
  - `iam.googleapis.com/workloadIdentityPools.list`
- To create, update, and delete pools and providers:
  - `iam.googleapis.com/workloadIdentityPoolProviders.create`
  - `iam.googleapis.com/workloadIdentityPoolProviders.delete`
  - `iam.googleapis.com/workloadIdentityPoolProviders.undelete`
  - `iam.googleapis.com/workloadIdentityPoolProviders.update`
  - `iam.googleapis.com/workloadIdentityPools.create`
  - `iam.googleapis.com/workloadIdentityPools.delete`
  - `iam.googleapis.com/workloadIdentityPools.undelete`
  - `iam.googleapis.com/workloadIdentityPools.update`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Manage workload identity pools

This section shows you how to manage workload identity pools.

### Create pools

To create workload identity pools in a project, do the following:

> **Note:** The prefix `gcp-` is reserved and can't be used in a pool or provider ID.

### Console

1.  In the Google Cloud console, go to the **New workload provider and pool** page.

2.  In the **Create an identity pool** section, enter a name for the pool.

    The Google Cloud console uses the name to create a pool ID. To change the pool ID, click **Edit** . You can't change the pool ID later.

3.  Optional: In the **Description** field, enter a description for the pool.

4.  Optional: To create the pool in a disabled state, click the **Enabled pool** toggle.

5.  Click **Continue** .

6.  In the **Add a provider to pool** and **Configure provider attributes** sections, configure an identity provider for the pool. For instructions, see [Create a provider](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#create-provider) .

7.  Click **Save** .

### gcloud

The [`gcloud iam workload-identity-pools create`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/create) command creates a workload identity pool in a project.

Before using any of the command data below, make the following replacements:

- `POOL_ID` : A unique ID for the workload identity pool—for example, `my-pool` . Must be 4-32 lowercase alphanumeric characters or hyphens, and can't start with `gcp-` .
- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `DISPLAY_NAME` : Optional. A display name for the workload identity pool, up to 32 characters—for example, `My workload pool` .
- `DESCRIPTION` : Optional. A description of the workload identity pool, up to 256 characters.

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools create POOL_ID \
    --project=PROJECT_ID \
    --location="global" \
    --display-name="DISPLAY_NAME" \
    --description="DESCRIPTION"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools create POOL_ID `
    --project=PROJECT_ID `
    --location="global" `
    --display-name="DISPLAY_NAME" `
    --description="DESCRIPTION"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools create POOL_ID ^
    --project=PROJECT_ID ^
    --location="global" ^
    --display-name="DISPLAY_NAME" ^
    --description="DESCRIPTION"
```

You should receive a response similar to the following:

```
Create request issued for: [my-pool]
Waiting for operation [projects/123456789012/locations/global/workloadIdentityPools/my-pool/operations/operation-1700000000000-0123456789abcdef] to complete...done.
Created workloadIdentityPool [my-pool].
```

### REST

The [`projects.locations.workloadIdentityPools.create`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/create) method creates a workload identity pool in a project.

Before using any of the request data, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : A unique ID for the workload identity pool—for example, `my-pool` . Must be 4-32 lowercase alphanumeric characters or hyphens, and can't start with `gcp-` .
- `DISPLAY_NAME` : Optional. A display name for the workload identity pool, up to 32 characters—for example, `My workload pool` .
- `DESCRIPTION` : Optional. A description of the workload identity pool, up to 256 characters.

HTTP method and URL:

```
POST https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools?workloadIdentityPoolId=POOL_ID
```

Request JSON body:

```
{
  "displayName": "DISPLAY_NAME",
  "description": "DESCRIPTION"
}
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
curl -X POST \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     -H "Content-Type: application/json; charset=utf-8" \
     -d @request.json \
     "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools?workloadIdentityPoolId=POOL_ID"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method POST `
    -Headers $headers `
    -ContentType: "application/json; charset=utf-8" `
    -InFile request.json `
    -Uri "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools?workloadIdentityPoolId=POOL_ID" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Copy the request body and open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/create) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Paste the request body in this tool, complete any other required fields, and click **Execute** .

The response contains a long-running operation that represents your request. To check whether the pool creation is complete, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#check-operation-status) on this page.

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/operations/operation-1700000000000-0123456789abcdef",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v1.WorkloadIdentityPoolOperationMetadata"
  },
  "done": false
}
```

### List pools

To list all the workload identity pools in a project, do the following:

### Console

1.  In the Google Cloud console, go to the **Workload Identity Pools** page.

2.  In the table, view the list of workload identity pools.

3.  Optional: To include deleted pools and providers in the list, click the **Show deleted pools and providers** toggle.

### gcloud

The [`gcloud iam workload-identity-pools list`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/list) command lists the workload identity pools in a project.

Before using any of the command data below, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` . To include soft-deleted pools in the output, add the `--show-deleted` flag.

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools list \
    --project=PROJECT_ID \
    --location="global" \
    --format="json"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools list `
    --project=PROJECT_ID `
    --location="global" `
    --format="json"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools list ^
    --project=PROJECT_ID ^
    --location="global" ^
    --format="json"
```

You should receive a response similar to the following:

```
[
  {
    "description": "Workload identity pool for external workloads.",
    "displayName": "My workload pool",
    "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool",
    "state": "ACTIVE"
  }
]
```

### REST

The [`projects.locations.workloadIdentityPools.list`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/list) method lists the workload identity pools in a project.

Before using any of the request data, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` . To include soft-deleted pools in the response, append `?showDeleted=true` to the request URL.

HTTP method and URL:

```
GET https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X GET \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method GET `
    -Headers $headers `
    -Uri "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/list) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Complete any required fields and click **Execute** .

You should receive a JSON response similar to the following:

```
{
  "workloadIdentityPools": [
    {
      "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool",
      "displayName": "My workload pool",
      "description": "Workload identity pool for external workloads.",
      "state": "ACTIVE"
    }
  ]
}
```

### Get a pool

To get details for a specific workload identity pool, do the following:

### Console

1.  In the Google Cloud console, go to the **Workload Identity Pools** page.

2.  Find the workload identity pool that you want to view, and then click its display name. The Google Cloud console shows details about the workload identity pool.

### gcloud

The [`gcloud iam workload-identity-pools describe`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/describe) command gets details about a workload identity pool.

Before using any of the command data below, make the following replacements:

- `POOL_ID` : The ID of the workload identity pool—for example, `my-pool` .
- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools describe POOL_ID \
    --project=PROJECT_ID \
    --location="global" \
    --format="json"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools describe POOL_ID `
    --project=PROJECT_ID `
    --location="global" `
    --format="json"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools describe POOL_ID ^
    --project=PROJECT_ID ^
    --location="global" ^
    --format="json"
```

You should receive a response similar to the following:

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool",
  "displayName": "My workload pool",
  "description": "Workload identity pool for external workloads.",
  "state": "ACTIVE"
}
```

### REST

The [`projects.locations.workloadIdentityPools.get`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/get) method gets details about a workload identity pool.

Before using any of the request data, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool—for example, `my-pool` .

HTTP method and URL:

```
GET https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X GET \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method GET `
    -Headers $headers `
    -Uri "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/get) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Complete any required fields and click **Execute** .

You should receive a JSON response similar to the following:

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool",
  "displayName": "My workload pool",
  "description": "Workload identity pool for external workloads.",
  "state": "ACTIVE"
}
```

### Update a pool

You can enable or disable a workload identity pool. You can also change its display name or description.

To update an existing workload identity pool, do the following:

### Console

1.  In the Google Cloud console, go to the **Workload Identity Pools** page.

2.  Find the workload identity pool that you want to edit.

3.  Click the workload identity pool's display name.

4.  To edit the workload identity pool's display name, do the following:

    1.  In the **Pool details** page, next to the display name, click the edit **Edit** icon.
    2.  In the **Edit pool display name** dialog that appears, update the display name.
    3.  Click **Save** .

5.  To disable or enable the workload identity pool, click the **Status** toggle, then click **Disable** or **Enable** .

6.  To edit the description, do the following:

    1.  In **Description** , next to your description text, click edit **Edit** .
    2.  Update the description.
    3.  Click **Save** .

### gcloud

The [`gcloud iam workload-identity-pools update`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/update) command updates an existing workload identity pool.

Before using any of the command data below, make the following replacements:

- `POOL_ID` : The ID of the workload identity pool—for example, `my-pool` .
- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `DISPLAY_NAME` : A display name for the workload identity pool, up to 32 characters—for example, `My updated pool` .
- `DESCRIPTION` : A description of the workload identity pool, up to 256 characters. To disable or enable the pool, also pass the `--disabled` or `--no-disabled` flag.

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools update POOL_ID \
    --project=PROJECT_ID \
    --location="global" \
    --display-name="DISPLAY_NAME" \
    --description="DESCRIPTION"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools update POOL_ID `
    --project=PROJECT_ID `
    --location="global" `
    --display-name="DISPLAY_NAME" `
    --description="DESCRIPTION"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools update POOL_ID ^
    --project=PROJECT_ID ^
    --location="global" ^
    --display-name="DISPLAY_NAME" ^
    --description="DESCRIPTION"
```

You should receive a response similar to the following:

```
Update request issued for: [my-pool]
Waiting for operation [projects/123456789012/locations/global/workloadIdentityPools/my-pool/operations/operation-1700000000001-0123456789abcdef] to complete...done.
Updated workloadIdentityPool [my-pool].
```

### REST

The [`projects.locations.workloadIdentityPools.patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/patch) method updates an existing workload identity pool.

Before using any of the request data, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool—for example, `my-pool` .
- `UPDATE_MASK` : A comma-separated list of fields to update—for example, `displayName,description,disabled` .
- `DISPLAY_NAME` : A display name for the workload identity pool, up to 32 characters—for example, `My updated pool` .
- `DESCRIPTION` : A description of the workload identity pool, up to 256 characters.
- `DISABLED` : Whether the pool is disabled. Set to `true` to disable the pool or `false` to enable it.

HTTP method and URL:

```
PATCH https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID?updateMask=UPDATE_MASK
```

Request JSON body:

```
{
  "displayName": "DISPLAY_NAME",
  "description": "DESCRIPTION",
  "disabled": DISABLED
}
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
curl -X PATCH \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     -H "Content-Type: application/json; charset=utf-8" \
     -d @request.json \
     "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID?updateMask=UPDATE_MASK"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method PATCH `
    -Headers $headers `
    -ContentType: "application/json; charset=utf-8" `
    -InFile request.json `
    -Uri "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID?updateMask=UPDATE_MASK" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Copy the request body and open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/patch) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Paste the request body in this tool, complete any other required fields, and click **Execute** .

The response contains a long-running operation that represents your request. To check whether the pool update is complete, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#check-operation-status) on this page.

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/operations/operation-1700000000001-0123456789abcdef",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v1.WorkloadIdentityPoolOperationMetadata"
  },
  "done": false
}
```

### Delete a pool

When you delete a workload identity pool, you also delete its workload identity pool providers. As a result, the identities in the pool lose access to Google Cloud resources.

> **Caution:** Before you delete a workload identity pool, consider [disabling the pool](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#update-pool) or [disabling its IdPs](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#update-provider) . If one of your workloads loses access to Google Cloud resources as a result, you can re-enable the pool and its providers at any time. If your workloads don't lose access, then it is safe to delete the pool.

You can [undelete a pool](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#undelete-pool) for up to 30 days after you delete it. After 30 days, the deletion is permanent. Until a pool is permanently deleted, you cannot reuse its name when creating a new workload identity pool.

To delete a workload identity pool and its IdPs, do the following:

### Console

1.  In the Google Cloud console, go to the **Workload Identity Pools** page.

2.  Find the workload identity pool that you want to delete, and then click its display name.

3.  Click delete **Delete pool** , then click **Delete** . The workload identity pool and its IdPs are deleted.

### gcloud

The [`gcloud iam workload-identity-pools delete`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/delete) command deletes a workload identity pool.

Before using any of the command data below, make the following replacements:

- `POOL_ID` : The ID of the workload identity pool to delete—for example, `my-pool` .
- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools delete POOL_ID \
    --project=PROJECT_ID \
    --location="global"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools delete POOL_ID `
    --project=PROJECT_ID `
    --location="global"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools delete POOL_ID ^
    --project=PROJECT_ID ^
    --location="global"
```

You should receive a response similar to the following:

```
Delete request issued for: [my-pool]
Waiting for operation [projects/123456789012/locations/global/workloadIdentityPools/my-pool/operations/operation-1700000000002-0123456789abcdef] to complete...done.
Deleted workloadIdentityPool [my-pool].
```

### REST

The [`projects.locations.workloadIdentityPools.delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/delete) method deletes a workload identity pool.

Before using any of the request data, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool to delete—for example, `my-pool` .

HTTP method and URL:

```
DELETE https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X DELETE \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method DELETE `
    -Headers $headers `
    -Uri "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/delete) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Complete any required fields and click **Execute** .

The response contains a long-running operation that represents your request. To check whether the pool deletion is complete, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#check-operation-status) on this page.

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/operations/operation-1700000000002-0123456789abcdef",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v1.WorkloadIdentityPoolOperationMetadata"
  },
  "done": false
}
```

### Undelete a pool

You can recover a deleted workload identity pool for up to 30 days after deletion.

To undelete a pool, do the following:

### Console

1.  In the Google Cloud console, go to the **Workload Identity Pools** page.

2.  Click the **Show deleted pools and providers** toggle.

3.  Find the workload identity pool that you want to undelete, then click its undo **Restore** icon.

4.  Click **Restore** . The pool and its providers are restored.

### gcloud

The [`gcloud iam workload-identity-pools undelete`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/undelete) command restores a soft-deleted workload identity pool.

Before using any of the command data below, make the following replacements:

- `POOL_ID` : The ID of the deleted workload identity pool to restore—for example, `my-pool` .
- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools undelete POOL_ID \
    --project=PROJECT_ID \
    --location="global"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools undelete POOL_ID `
    --project=PROJECT_ID `
    --location="global"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools undelete POOL_ID ^
    --project=PROJECT_ID ^
    --location="global"
```

You should receive a response similar to the following:

```
Undelete request issued for: [my-pool]
Waiting for operation [projects/123456789012/locations/global/workloadIdentityPools/my-pool/operations/operation-1700000000003-0123456789abcdef] to complete...done.
Undeleted workloadIdentityPool [my-pool].
```

### REST

The [`projects.locations.workloadIdentityPools.undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/undelete) method restores a soft-deleted workload identity pool.

Before using any of the request data, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the deleted workload identity pool to restore—for example, `my-pool` .

HTTP method and URL:

```
POST https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID:undelete
```

Request JSON body:

```
{}
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
curl -X POST \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     -H "Content-Type: application/json; charset=utf-8" \
     -d @request.json \
     "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID:undelete"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method POST `
    -Headers $headers `
    -ContentType: "application/json; charset=utf-8" `
    -InFile request.json `
    -Uri "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID:undelete" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Copy the request body and open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools/undelete) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Paste the request body in this tool, complete any other required fields, and click **Execute** .

The response contains a long-running operation that represents your request. To check whether the pool restoration is complete, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#check-operation-status) on this page.

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/operations/operation-1700000000003-0123456789abcdef",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v1.WorkloadIdentityPoolOperationMetadata"
  },
  "done": false
}
```

## Manage workload identity pool providers

This section shows you how to manage workload identity pool providers.

### Create a provider

To create a workload identity pool provider in an existing workload identity pool, do the following:

### Console

1.  In the Google Cloud console, go to the **Workload Identity Pools** page.

2.  Find the workload identity pool that you want to add a provider to, and then click its **Display name** .

3.  Click add_box **Add provider** .

4.  Select the type of provider to create:

    - **AWS** : An Amazon Web Services (AWS) IdP.
    - **OpenID Connect (OIDC)** : An OIDC-compatible IdP. This includes Microsoft Azure.

5.  Enter a name for the provider.

    The Google Cloud console uses the name to create a provider ID. To change the provider ID, click **Edit** . You can't change the provider ID later.

6.  Complete the remaining fields for your provider:

    - **AWS** : Enter your AWS account ID.
    - **OIDC** : Enter the issuer URL. For Azure, the issuer URL uses the format `https://sts.windows.net/ `` AZURE_TENANT_ID` . For other providers, consult the provider's documentation.

    When you are done, click **Continue** .

7.  To configure the attribute mapping, click **Edit mapping** . Attribute mapping lets you use information about external identities to grant access to a subset of those identities.

    - **AWS** : This step is optional. You can use the default mapping.

      For details, see [Identity provider settings for AWS and Azure](https://docs.cloud.google.com/iam/docs/workload-identity-federation-with-other-clouds#mappings-and-conditions) .

    - **OIDC** : We recommend mapping `google.subject` to `assertion.sub` . Other mappings are optional.

      For details, see IdP settings for [Azure](https://docs.cloud.google.com/iam/docs/workload-identity-federation-with-other-clouds#mappings-and-conditions) or [other OIDC providers](https://docs.cloud.google.com/iam/docs/workload-identity-federation-with-other-providers#mappings-and-conditions) .

8.  Optional: To provide an attribute condition, which specifies the identities that can authenticate, click **Add condition** and enter a valid Common Expression Language (CEL) expression. For details, see [Attribute conditions](https://docs.cloud.google.com/iam/docs/workload-identity-federation#conditions) .

9.  Click **Save** . The workload identity pool provider is created.

### gcloud

#### Create an AWS provider

The [`gcloud iam workload-identity-pools providers create-aws`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/providers/create-aws) command creates an AWS workload identity pool provider.

Before using any of the command data below, make the following replacements:

- `PROVIDER_ID` : A unique ID for the provider—for example, `my-aws-provider` . Must be 4-32 lowercase alphanumeric characters or hyphens, and can't start with `gcp-` .
- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool to add the provider to—for example, `my-pool` .
- `DISPLAY_NAME` : Optional. A display name for the provider, up to 32 characters—for example, `My AWS provider` .
- `AWS_ACCOUNT_ID` : Your 12-digit AWS account ID—for example, `123456789012` .
- `ATTRIBUTE_CONDITION` : Optional. A Common Expression Language (CEL) expression that restricts which identities can authenticate—for example, `attribute.aws_role == 'arn:aws:sts::123456789012:assumed-role/my-role'` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools providers create-aws PROVIDER_ID \
    --project=PROJECT_ID \
    --location="global" \
    --workload-identity-pool="POOL_ID" \
    --display-name="DISPLAY_NAME" \
    --account-id="AWS_ACCOUNT_ID" \
    --attribute-condition="ATTRIBUTE_CONDITION"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools providers create-aws PROVIDER_ID `
    --project=PROJECT_ID `
    --location="global" `
    --workload-identity-pool="POOL_ID" `
    --display-name="DISPLAY_NAME" `
    --account-id="AWS_ACCOUNT_ID" `
    --attribute-condition="ATTRIBUTE_CONDITION"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools providers create-aws PROVIDER_ID ^
    --project=PROJECT_ID ^
    --location="global" ^
    --workload-identity-pool="POOL_ID" ^
    --display-name="DISPLAY_NAME" ^
    --account-id="AWS_ACCOUNT_ID" ^
    --attribute-condition="ATTRIBUTE_CONDITION"
```

You should receive a response similar to the following:

```
Create request issued for: [my-aws-provider]
Waiting for operation [projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-aws-provider/operations/operation-1700000000010-0123456789abcdef] to complete...done.
Created workloadIdentityPoolProvider [my-aws-provider].
```

#### Create an OIDC provider

The [`gcloud iam workload-identity-pools providers create-oidc`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/providers/create-oidc) command creates an OIDC workload identity pool provider.

Before using any of the command data below, make the following replacements:

- `PROVIDER_ID` : A unique ID for the provider—for example, `my-oidc-provider` . Must be 4-32 lowercase alphanumeric characters or hyphens, and can't start with `gcp-` .
- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool to add the provider to—for example, `my-pool` .
- `DISPLAY_NAME` : Optional. A display name for the provider, up to 32 characters—for example, `My OIDC provider` .
- `ISSUER_URI` : The OIDC issuer HTTPS URL—for example, `https://idp.example.com` or `https://sts.windows.net/ `` AZURE_TENANT_ID` .
- `DISCOVERY_URI` : Optional. The URL to fetch the OIDC discovery document from, overriding the default `ISSUER_URI `` /.well-known/openid-configuration` URL—for example, `https://idp.example.com/.well-known/custom-openid-configuration` . The scheme, host, and port must match `ISSUER_URI` , and the path must contain a `/.well-known/` segment followed by a non-empty suffix.
- `ATTRIBUTE_CONDITION` : Optional. A Common Expression Language (CEL) expression that restricts which identities can authenticate—for example, `assertion.sub.startsWith('repo:my-org/')` .
- `ACTOR_PROVIDERS` : Optional. The full resource names of up to three workload identity pool providers in the same pool that are authorized to issue actor tokens for this provider—for example, `projects/my-project/locations/global/workloadIdentityPools/my-pool/providers/my-actor-provider` . The project identifier in each resource name must match the project ID or project number format that you use for this provider. For more information, see [Configure identity delegation and actor tokens](https://docs.cloud.google.com/iam/docs/workload-identity-federation-with-other-providers#delegation) .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools providers create-oidc PROVIDER_ID \
    --project=PROJECT_ID \
    --location="global" \
    --workload-identity-pool="POOL_ID" \
    --display-name="DISPLAY_NAME" \
    --issuer-uri="ISSUER_URI" \
    --discovery-uri="DISCOVERY_URI" \
    --attribute-mapping="google.subject=assertion.sub" \
    --attribute-condition="ATTRIBUTE_CONDITION" \
    --actor-providers="ACTOR_PROVIDERS"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools providers create-oidc PROVIDER_ID `
    --project=PROJECT_ID `
    --location="global" `
    --workload-identity-pool="POOL_ID" `
    --display-name="DISPLAY_NAME" `
    --issuer-uri="ISSUER_URI" `
    --discovery-uri="DISCOVERY_URI" `
    --attribute-mapping="google.subject=assertion.sub" `
    --attribute-condition="ATTRIBUTE_CONDITION" `
    --actor-providers="ACTOR_PROVIDERS"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools providers create-oidc PROVIDER_ID ^
    --project=PROJECT_ID ^
    --location="global" ^
    --workload-identity-pool="POOL_ID" ^
    --display-name="DISPLAY_NAME" ^
    --issuer-uri="ISSUER_URI" ^
    --discovery-uri="DISCOVERY_URI" ^
    --attribute-mapping="google.subject=assertion.sub" ^
    --attribute-condition="ATTRIBUTE_CONDITION" ^
    --actor-providers="ACTOR_PROVIDERS"
```

You should receive a response similar to the following:

```
Create request issued for: [my-oidc-provider]
Waiting for operation [projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-oidc-provider/operations/operation-1700000000011-0123456789abcdef] to complete...done.
Created workloadIdentityPoolProvider [my-oidc-provider].
```

### REST

#### Create an AWS provider

The [`projects.locations.workloadIdentityPools.providers.create`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/create) method creates an AWS workload identity pool provider.

Before using any of the request data, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool to add the provider to—for example, `my-pool` .
- `PROVIDER_ID` : A unique ID for the provider—for example, `my-aws-provider` . Must be 4-32 lowercase alphanumeric characters or hyphens, and can't start with `gcp-` .
- `DISPLAY_NAME` : Optional. A display name for the provider, up to 32 characters—for example, `My AWS provider` .
- `AWS_ACCOUNT_ID` : Your 12-digit AWS account ID—for example, `123456789012` .
- `ATTRIBUTE_CONDITION` : Optional. A Common Expression Language (CEL) expression that restricts which identities can authenticate—for example, `attribute.aws_role == 'arn:aws:sts::123456789012:assumed-role/my-role'` .

HTTP method and URL:

```
POST https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers?workloadIdentityPoolProviderId=PROVIDER_ID
```

Request JSON body:

```
{
  "displayName": "DISPLAY_NAME",
  "aws": {
    "accountId": "AWS_ACCOUNT_ID"
  },
  "attributeCondition": "ATTRIBUTE_CONDITION"
}
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
curl -X POST \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     -H "Content-Type: application/json; charset=utf-8" \
     -d @request.json \
     "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers?workloadIdentityPoolProviderId=PROVIDER_ID"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method POST `
    -Headers $headers `
    -ContentType: "application/json; charset=utf-8" `
    -InFile request.json `
    -Uri "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers?workloadIdentityPoolProviderId=PROVIDER_ID" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Copy the request body and open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/create) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Paste the request body in this tool, complete any other required fields, and click **Execute** .

The response contains a long-running operation that represents your request. To check whether the provider creation is complete, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#check-operation-status) on this page.

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-aws-provider/operations/operation-1700000000010-0123456789abcdef",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v1.WorkloadIdentityPoolProviderOperationMetadata"
  },
  "done": false
}
```

#### Create an OIDC provider

The [`projects.locations.workloadIdentityPools.providers.create`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/create) method creates an OIDC workload identity pool provider.

Before using any of the request data, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool to add the provider to—for example, `my-pool` .
- `PROVIDER_ID` : A unique ID for the provider—for example, `my-oidc-provider` . Must be 4-32 lowercase alphanumeric characters or hyphens, and can't start with `gcp-` .
- `DISPLAY_NAME` : Optional. A display name for the provider, up to 32 characters—for example, `My OIDC provider` .
- `ISSUER_URI` : The OIDC issuer HTTPS URL—for example, `https://idp.example.com` or `https://sts.windows.net/ `` AZURE_TENANT_ID` .
- `DISCOVERY_URI` : Optional. The URL to fetch the OIDC discovery document from, overriding the default `ISSUER_URI `` /.well-known/openid-configuration` URL—for example, `https://idp.example.com/.well-known/custom-openid-configuration` . The scheme, host, and port must match `ISSUER_URI` , and the path must contain a `/.well-known/` segment followed by a non-empty suffix.
- `ATTRIBUTE_CONDITION` : Optional. A Common Expression Language (CEL) expression that restricts which identities can authenticate—for example, `assertion.sub.startsWith('repo:my-org/')` .
- `ACTOR_PROVIDERS` : Optional. The full resource names of up to three workload identity pool providers in the same pool that are authorized to issue actor tokens for this provider—for example, `projects/my-project/locations/global/workloadIdentityPools/my-pool/providers/my-actor-provider` . The project identifier in each resource name must match the project ID or project number format that you use for this provider. For more information, see [Configure identity delegation and actor tokens](https://docs.cloud.google.com/iam/docs/workload-identity-federation-with-other-providers#delegation) .

HTTP method and URL:

```
POST https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers?workloadIdentityPoolProviderId=PROVIDER_ID
```

Request JSON body:

```
{
  "displayName": "DISPLAY_NAME",
  "oidc": {
    "issuerUri": "ISSUER_URI",
    "discoveryUri": "DISCOVERY_URI"
  },
  "attributeMapping": {
    "google.subject": "assertion.sub"
  },
  "attributeCondition": "ATTRIBUTE_CONDITION",
  "actorProviders": [
    "ACTOR_PROVIDERS"
  ]
}
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
curl -X POST \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     -H "Content-Type: application/json; charset=utf-8" \
     -d @request.json \
     "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers?workloadIdentityPoolProviderId=PROVIDER_ID"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method POST `
    -Headers $headers `
    -ContentType: "application/json; charset=utf-8" `
    -InFile request.json `
    -Uri "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers?workloadIdentityPoolProviderId=PROVIDER_ID" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Copy the request body and open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/create) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Paste the request body in this tool, complete any other required fields, and click **Execute** .

The response contains a long-running operation that represents your request. To check whether the provider creation is complete, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#check-operation-status) on this page.

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-oidc-provider/operations/operation-1700000000011-0123456789abcdef",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v1.WorkloadIdentityPoolProviderOperationMetadata"
  },
  "done": false
}
```

### List providers

To list the workload identity pool providers in a project, do the following:

### Console

1.  In the Google Cloud console, go to the **Workload Identity Pools** page.

2.  To view the providers for a workload identity pool, click the arrow_right **Expand node** icon for the pool.

### gcloud

The [`gcloud iam workload-identity-pools providers list`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/providers/list) command lists the providers in a workload identity pool.

Before using any of the command data below, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool whose providers you want to list—for example, `my-pool` . To include soft-deleted providers in the output, add the `--show-deleted` flag.

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools providers list \
    --project=PROJECT_ID \
    --location="global" \
    --workload-identity-pool="POOL_ID" \
    --format="json"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools providers list `
    --project=PROJECT_ID `
    --location="global" `
    --workload-identity-pool="POOL_ID" `
    --format="json"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools providers list ^
    --project=PROJECT_ID ^
    --location="global" ^
    --workload-identity-pool="POOL_ID" ^
    --format="json"
```

You should receive a response similar to the following:

```
[
  {
    "attributeMapping": {
      "google.subject": "assertion.sub"
    },
    "displayName": "My OIDC provider",
    "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-oidc-provider",
    "oidc": {
      "issuerUri": "https://idp.example.com"
    },
    "state": "ACTIVE"
  }
]
```

### REST

The [`projects.locations.workloadIdentityPools.providers.list`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/list) method lists the providers in a workload identity pool.

Before using any of the request data, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool whose providers you want to list—for example, `my-pool` . To include soft-deleted providers in the response, append `?showDeleted=true` to the request URL.

HTTP method and URL:

```
GET https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X GET \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method GET `
    -Headers $headers `
    -Uri "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/list) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Complete any required fields and click **Execute** .

You should receive a JSON response similar to the following:

```
{
  "workloadIdentityPoolProviders": [
    {
      "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-oidc-provider",
      "displayName": "My OIDC provider",
      "state": "ACTIVE",
      "attributeMapping": {
        "google.subject": "assertion.sub"
      },
      "oidc": {
        "issuerUri": "https://idp.example.com"
      }
    }
  ]
}
```

### Get a provider

To get details for a specific workload identity pool provider, do the following:

### Console

1.  In the Google Cloud console, go to the **Workload Identity Pools** page.

2.  Find the workload identity pool that contains the provider, then click the arrow_right **Expand node** icon for the pool.

3.  Find the workload identity pool provider that you want to view, then click its edit **Edit** icon. The Google Cloud console shows detailed information about the provider.

### gcloud

The [`gcloud iam workload-identity-pools providers describe`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/providers/describe) command gets details about a workload identity pool provider.

Before using any of the command data below, make the following replacements:

- `PROVIDER_ID` : The ID of the workload identity pool provider—for example, `my-oidc-provider` .
- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool that contains the provider—for example, `my-pool` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools providers describe PROVIDER_ID \
    --project=PROJECT_ID \
    --location="global" \
    --workload-identity-pool="POOL_ID" \
    --format="json"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools providers describe PROVIDER_ID `
    --project=PROJECT_ID `
    --location="global" `
    --workload-identity-pool="POOL_ID" `
    --format="json"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools providers describe PROVIDER_ID ^
    --project=PROJECT_ID ^
    --location="global" ^
    --workload-identity-pool="POOL_ID" ^
    --format="json"
```

You should receive a response similar to the following:

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-oidc-provider",
  "displayName": "My OIDC provider",
  "state": "ACTIVE",
  "attributeMapping": {
    "google.subject": "assertion.sub"
  },
  "oidc": {
    "issuerUri": "https://idp.example.com"
  }
}
```

### REST

The [`projects.locations.workloadIdentityPools.providers.get`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/get) method gets details about a workload identity pool provider.

Before using any of the request data, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool that contains the provider—for example, `my-pool` .
- `PROVIDER_ID` : The ID of the workload identity pool provider—for example, `my-oidc-provider` .

HTTP method and URL:

```
GET https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers/PROVIDER_ID
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X GET \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers/PROVIDER_ID"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method GET `
    -Headers $headers `
    -Uri "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers/PROVIDER_ID" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/get) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Complete any required fields and click **Execute** .

You should receive a JSON response similar to the following:

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-oidc-provider",
  "displayName": "My OIDC provider",
  "state": "ACTIVE",
  "attributeMapping": {
    "google.subject": "assertion.sub"
  },
  "oidc": {
    "issuerUri": "https://idp.example.com"
  }
}
```

### Update a provider

You can enable or disable a workload identity pool provider. You can also update its account information and its attribute mapping, as well as its display name and description.

To update an existing workload identity pool provider, do the following:

### Console

1.  In the Google Cloud console, go to the **Workload Identity Pools** page.

2.  Find the workload identity pool that contains the provider, then click the arrow_right **Expand node** icon for the pool.

3.  Find the workload identity pool provider that you want to edit, then click its edit **Edit** icon.

4.  Edit the provider's information, then click **Save** .

### gcloud

#### Update an AWS provider

The [`gcloud iam workload-identity-pools providers update-aws`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/providers/update-aws) command updates an existing AWS workload identity pool provider.

Before using any of the command data below, make the following replacements:

- `PROVIDER_ID` : The ID of the provider to update—for example, `my-aws-provider` .
- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool that contains the provider—for example, `my-pool` .
- `DISPLAY_NAME` : A display name for the provider, up to 32 characters—for example, `Updated AWS provider` .
- `DESCRIPTION` : A description of the provider, up to 256 characters. To disable or enable the provider, also pass the `--disabled` or `--no-disabled` flag.

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools providers update-aws PROVIDER_ID \
    --project=PROJECT_ID \
    --location="global" \
    --workload-identity-pool="POOL_ID" \
    --display-name="DISPLAY_NAME" \
    --description="DESCRIPTION"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools providers update-aws PROVIDER_ID `
    --project=PROJECT_ID `
    --location="global" `
    --workload-identity-pool="POOL_ID" `
    --display-name="DISPLAY_NAME" `
    --description="DESCRIPTION"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools providers update-aws PROVIDER_ID ^
    --project=PROJECT_ID ^
    --location="global" ^
    --workload-identity-pool="POOL_ID" ^
    --display-name="DISPLAY_NAME" ^
    --description="DESCRIPTION"
```

You should receive a response similar to the following:

```
Update request issued for: [my-aws-provider]
Waiting for operation [projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-aws-provider/operations/operation-1700000000012-0123456789abcdef] to complete...done.
Updated workloadIdentityPoolProvider [my-aws-provider].
```

#### Update an OIDC provider

The [`gcloud iam workload-identity-pools providers update-oidc`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/providers/update-oidc) command updates an existing AWS workload identity pool provider.

Before using any of the command data below, make the following replacements:

- `PROVIDER_ID` : The ID of the OIDC provider to update—for example, `my-oidc-provider` .
- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool that contains the provider—for example, `my-pool` .
- `DISPLAY_NAME` : A display name for the provider, up to 32 characters—for example, `Updated OIDC provider` .
- `DESCRIPTION` : A description of the provider, up to 256 characters.
- `ISSUER_URI` : The OIDC issuer HTTPS URL—for example, `https://idp.example.com` . To disable or enable the provider, also pass the `--disabled` or `--no-disabled` flag.

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools providers update-oidc PROVIDER_ID \
    --project=PROJECT_ID \
    --location="global" \
    --workload-identity-pool="POOL_ID" \
    --display-name="DISPLAY_NAME" \
    --description="DESCRIPTION" \
    --issuer-uri="ISSUER_URI"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools providers update-oidc PROVIDER_ID `
    --project=PROJECT_ID `
    --location="global" `
    --workload-identity-pool="POOL_ID" `
    --display-name="DISPLAY_NAME" `
    --description="DESCRIPTION" `
    --issuer-uri="ISSUER_URI"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools providers update-oidc PROVIDER_ID ^
    --project=PROJECT_ID ^
    --location="global" ^
    --workload-identity-pool="POOL_ID" ^
    --display-name="DISPLAY_NAME" ^
    --description="DESCRIPTION" ^
    --issuer-uri="ISSUER_URI"
```

You should receive a response similar to the following:

```
Update request issued for: [my-oidc-provider]
Waiting for operation [projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-oidc-provider/operations/operation-1700000000013-0123456789abcdef] to complete...done.
Updated workloadIdentityPoolProvider [my-oidc-provider].
```

### REST

The [`projects.locations.workloadIdentityPools.providers.patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/patch) method updates an existing workload identity pool provider.

Before using any of the request data, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool that contains the provider—for example, `my-pool` .
- `PROVIDER_ID` : The ID of the provider to update—for example, `my-aws-provider` .
- `UPDATE_MASK` : A comma-separated list of fields to update—for example, `displayName,description,disabled` .
- `DISPLAY_NAME` : A display name for the provider, up to 32 characters—for example, `Updated AWS provider` .
- `DESCRIPTION` : A description of the provider, up to 256 characters.
- `DISABLED` : Whether the provider is disabled. Set to `true` to disable the provider or `false` to enable it.

HTTP method and URL:

```
PATCH https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers/PROVIDER_ID?updateMask=UPDATE_MASK
```

Request JSON body:

```
{
  "displayName": "DISPLAY_NAME",
  "description": "DESCRIPTION",
  "disabled": DISABLED
}
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
curl -X PATCH \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     -H "Content-Type: application/json; charset=utf-8" \
     -d @request.json \
     "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers/PROVIDER_ID?updateMask=UPDATE_MASK"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method PATCH `
    -Headers $headers `
    -ContentType: "application/json; charset=utf-8" `
    -InFile request.json `
    -Uri "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers/PROVIDER_ID?updateMask=UPDATE_MASK" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Copy the request body and open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/patch) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Paste the request body in this tool, complete any other required fields, and click **Execute** .

The response contains a long-running operation that represents your request. To check whether the provider update is complete, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#check-operation-status) on this page.

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-aws-provider/operations/operation-1700000000012-0123456789abcdef",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v1.WorkloadIdentityPoolProviderOperationMetadata"
  },
  "done": false
}
```

### Delete a provider

When you delete a workload identity pool provider, the provider's identities lose access to Google Cloud resources.

> **Caution:** Before you delete a workload identity pool provider, consider [disabling the provider](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#update-provider) . If one of your workloads loses access to Google Cloud resources as a result, you can re-enable the provider at any time. If your workloads don't lose access, then it is safe to delete the provider.

You can [undelete a provider](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#undelete-provider) for up to 30 days after you delete it. After 30 days, the deletion is permanent. Until a provider is permanently deleted, you cannot reuse its name when creating a new provider.

To delete a workload identity pool provider, do the following:

### Console

1.  In the Google Cloud console, go to the **Workload Identity Pools** page.

2.  Find the workload identity pool that contains the provider, and then click its **Display name** .

3.  In the **Providers** pane, find the provider that you want to delete, then click its delete **Delete** icon.

4.  Click **Delete** to delete the provider.

### gcloud

The [`gcloud iam workload-identity-pools providers delete`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/providers/delete) command deletes a workload identity pool provider.

Before using any of the command data below, make the following replacements:

- `PROVIDER_ID` : The ID of the workload identity pool provider to delete—for example, `my-oidc-provider` .
- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool that contains the provider—for example, `my-pool` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools providers delete PROVIDER_ID \
    --project=PROJECT_ID \
    --location="global" \
    --workload-identity-pool="POOL_ID"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools providers delete PROVIDER_ID `
    --project=PROJECT_ID `
    --location="global" `
    --workload-identity-pool="POOL_ID"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools providers delete PROVIDER_ID ^
    --project=PROJECT_ID ^
    --location="global" ^
    --workload-identity-pool="POOL_ID"
```

You should receive a response similar to the following:

```
Delete request issued for: [my-oidc-provider]
Waiting for operation [projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-oidc-provider/operations/operation-1700000000014-0123456789abcdef] to complete...done.
Deleted workloadIdentityPoolProvider [my-oidc-provider].
```

### REST

The [`projects.locations.workloadIdentityPools.providers.delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/delete) method deletes a workload identity pool provider.

Before using any of the request data, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool that contains the provider—for example, `my-pool` .
- `PROVIDER_ID` : The ID of the workload identity pool provider to delete—for example, `my-oidc-provider` .

HTTP method and URL:

```
DELETE https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers/PROVIDER_ID
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X DELETE \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers/PROVIDER_ID"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method DELETE `
    -Headers $headers `
    -Uri "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers/PROVIDER_ID" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/delete) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Complete any required fields and click **Execute** .

The response contains a long-running operation that represents your request. To check whether the provider deletion is complete, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#check-operation-status) on this page.

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-oidc-provider/operations/operation-1700000000014-0123456789abcdef",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v1.WorkloadIdentityPoolProviderOperationMetadata"
  },
  "done": false
}
```

### Undelete a provider

You can recover a deleted workload identity pool provider for up to 30 days after you delete it. To undelete a provider, follow these steps:

### Console

1.  In the Google Cloud console, go to the **Workload Identity Pools** page.

2.  Click the **Show deleted pools and providers** toggle.

3.  Find the workload identity pool that contains the provider, then click the arrow_right **Expand node** icon for the pool.

4.  Find the provider that you want to undelete, then click its undo **Restore** icon.

5.  Click **Restore** . The provider is restored.

### gcloud

The [`gcloud iam workload-identity-pools providers undelete`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/providers/undelete) command restores a soft-deleted workload identity pool provider.

Before using any of the command data below, make the following replacements:

- `PROVIDER_ID` : The ID of the deleted workload identity pool provider to restore—for example, `my-oidc-provider` .
- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool that contains the provider—for example, `my-pool` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools providers undelete PROVIDER_ID \
    --project=PROJECT_ID \
    --location="global" \
    --workload-identity-pool="POOL_ID"
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools providers undelete PROVIDER_ID `
    --project=PROJECT_ID `
    --location="global" `
    --workload-identity-pool="POOL_ID"
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools providers undelete PROVIDER_ID ^
    --project=PROJECT_ID ^
    --location="global" ^
    --workload-identity-pool="POOL_ID"
```

You should receive a response similar to the following:

```
Undelete request issued for: [my-oidc-provider]
Waiting for operation [projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-oidc-provider/operations/operation-1700000000015-0123456789abcdef] to complete...done.
Undeleted workloadIdentityPoolProvider [my-oidc-provider].
```

### REST

The [`projects.locations.workloadIdentityPools.providers.undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/undelete) method restores a soft-deleted workload identity pool provider.

Before using any of the request data, make the following replacements:

- `PROJECT_ID` : Your Google Cloud project ID. Project IDs are alphanumeric strings, like `my-project` .
- `POOL_ID` : The ID of the workload identity pool that contains the provider—for example, `my-pool` .
- `PROVIDER_ID` : The ID of the deleted workload identity pool provider to restore—for example, `my-oidc-provider` .

HTTP method and URL:

```
POST https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers/PROVIDER_ID:undelete
```

Request JSON body:

```
{}
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
curl -X POST \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     -H "Content-Type: application/json; charset=utf-8" \
     -d @request.json \
     "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers/PROVIDER_ID:undelete"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method POST `
    -Headers $headers `
    -ContentType: "application/json; charset=utf-8" `
    -InFile request.json `
    -Uri "https://iam.googleapis.com/v1/projects/PROJECT_ID/locations/global/workloadIdentityPools/POOL_ID/providers/PROVIDER_ID:undelete" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Copy the request body and open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.providers/undelete) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Paste the request body in this tool, complete any other required fields, and click **Execute** .

The response contains a long-running operation that represents your request. To check whether the provider restoration is complete, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/manage-workload-identity-pools-providers#check-operation-status) on this page.

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/providers/my-oidc-provider/operations/operation-1700000000015-0123456789abcdef",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v1.WorkloadIdentityPoolProviderOperationMetadata"
  },
  "done": false
}
```

## Check the status of a long-running operation

When you use the REST API, any method that creates, updates, deletes, or restores a workload identity pool or provider returns a long-running operation (LRO). The long-running operation tracks the status of the request and indicates whether the change is complete.

> **Note:** When you modify a workload identity pool or provider by using the gcloud CLI, the gcloud CLI waits for the operation to complete by default unless you pass the `--async` flag.

### gcloud

The [`gcloud iam workload-identity-pools operations describe`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/operations/describe) command returns the status of a long-running operation.

Before using any of the command data below, make the following replacements:

- `OPERATION_NAME` : The full resource name of the operation from the `name` field of the original response:

  - Pool operations: `projects/ `` PROJECT_NUMBER `` /locations/global/workloadIdentityPools/ `` POOL_ID `` /operations/ `` OPERATION_ID`
  - Provider operations: `projects/ `` PROJECT_NUMBER `` /locations/global/workloadIdentityPools/ `` POOL_ID `` /providers/ `` PROVIDER_ID `` /operations/ `` OPERATION_ID`

  For provider operations, run the [`gcloud iam workload-identity-pools providers operations describe`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/workload-identity-pools/providers/operations/describe) command instead.

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam workload-identity-pools operations describe OPERATION_NAME
```

#### Windows (PowerShell)

```
gcloud iam workload-identity-pools operations describe OPERATION_NAME
```

#### Windows (cmd.exe)

```
gcloud iam workload-identity-pools operations describe OPERATION_NAME
```

You should receive a response similar to the following:

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/operations/operation-1700000000000-0123456789abcdef",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v1.WorkloadIdentityPoolOperationMetadata"
  },
  "done": true,
  "response": {
    "@type": "type.googleapis.com/google.iam.v1.WorkloadIdentityPool",
    "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool",
    "displayName": "My workload pool",
    "description": "Workload identity pool for external workloads.",
    "state": "ACTIVE"
  }
}
```

### REST

The [`projects.locations.workloadIdentityPools.operations.get`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.operations/get) method returns the status of a long-running operation.

Before using any of the request data, make the following replacements:

- `OPERATION_NAME` : The full resource name of the operation from the `name` field of the original response:

  - Pool operations: `projects/ `` PROJECT_NUMBER `` /locations/global/workloadIdentityPools/ `` POOL_ID `` /operations/ `` OPERATION_ID`
  - Provider operations: `projects/ `` PROJECT_NUMBER `` /locations/global/workloadIdentityPools/ `` POOL_ID `` /providers/ `` PROVIDER_ID `` /operations/ `` OPERATION_ID`

HTTP method and URL:

```
GET https://iam.googleapis.com/v1/OPERATION_NAME
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X GET \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v1/OPERATION_NAME"
```

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
$cred = gcloud auth print-access-token
$headers = @{ "Authorization" = "Bearer $cred" }

Invoke-WebRequest `
    -Method GET `
    -Headers $headers `
    -Uri "https://iam.googleapis.com/v1/OPERATION_NAME" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.operations/get) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Complete any required fields and click **Execute** .

You should receive a JSON response similar to the following:

```
{
  "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool/operations/operation-1700000000000-0123456789abcdef",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v1.WorkloadIdentityPoolOperationMetadata"
  },
  "done": true,
  "response": {
    "@type": "type.googleapis.com/google.iam.v1.WorkloadIdentityPool",
    "name": "projects/123456789012/locations/global/workloadIdentityPools/my-pool",
    "displayName": "My workload pool",
    "description": "Workload identity pool for external workloads.",
    "state": "ACTIVE"
  }
}
```

If the operation's `done` field is `false` or omitted, continue to monitor its status by getting the operation repeatedly. Use [truncated exponential backoff](https://docs.cloud.google.com/iam/docs/retry-strategy#algorithm) to introduce a delay between requests. When the `done` field is set to `true` , the operation is complete.

## Manage constraints for Workload Identity Federation

You can use [organization policy constraints](https://docs.cloud.google.com/resource-manager/docs/organization-policy/overview#constraints) to restrict how resources in your Google Cloud organization can be used.

This section describes constraints that are recommended when you use Workload Identity Federation.

### Manage allowed IdPs

As an organization administrator, you can decide which IdPs your organization is allowed to federate with.

To manage which IdPs are allowed, enable the `constraints/iam.workloadIdentityPoolProviders` list constraint in the organization policy for your organization. This constraint specifies the issuer URIs of the allowed providers. You can use the [Google Cloud console](https://docs.cloud.google.com/resource-manager/docs/organization-policy/creating-managing-policies#list_constraints) or the [Google Cloud CLI](https://docs.cloud.google.com/resource-manager/docs/organization-policy/using-constraints#list-constraint) to enable this constraint.

> **Note:** This constraint only limits creating and updating IdPs. If an IdP was configured before you enabled the constraint, that provider can still be used.

To only allow federation from AWS, create a single constraint with the URI `https://sts.amazonaws.com` . The following example shows how to create this constraint using the gcloud CLI:

```
gcloud resource-manager org-policies allow constraints/iam.workloadIdentityPoolProviders \
     https://sts.amazonaws.com --organization=ORGANIZATION_NUMBER
```

You can also specify which AWS account IDs have access to your Google Cloud resources. To specify the account IDs, use the `constraints/iam.workloadIdentityPoolAwsAccounts` list constraint:

```
gcloud resource-manager org-policies allow constraints/iam.workloadIdentityPoolAwsAccounts \
    ACCOUNT_ID --organization=ORGANIZATION_NUMBER
```

To only allow federation from one OIDC provider, create a single constraint with the `issuer_uri` of the allowed provider. For example, the following only allows federation from a specific Azure tenant:

```
gcloud resource-manager org-policies allow constraints/iam.workloadIdentityPoolProviders \
     https://sts.windows.net/AZURE_TENANT_ID --organization=ORGANIZATION_NUMBER
```

Federation from a SAML IdP is special because the public keys that are used to validate the assertion are provided when the SAML IdP is configured. As a result, it's possible that a malicious user might try to upload a SAML metadata document with the entity ID of your organization's IdP using a public key. Restricting federation using an entity ID in this scenario gives only an illusion of security.

To mitigate this risk, we strongly advise that you only allow a workload identity pool to be created with SAML federation in a Google Cloud project that your organization centrally manages. Then, as needed, grant external identities in that workload identity pool access to resources across your organization.

To allow federation from SAML IdPs, create a constraint allowing the special keyword `KEY_UPLOAD` .

```
gcloud resource-manager org-policies allow constraints/iam.workloadIdentityPoolProviders \
     KEY_UPLOAD --organization=ORGANIZATION_NUMBER
```

You can repeat these commands to allow federation from additional providers.

To block federation from all providers:

1.  Create a YAML file containing the following:

    ```
    constraint: constraints/iam.workloadIdentityPoolProviders
    listPolicy:
      allValues: DENY
    ```

2.  Pass the file to the [`gcloud resource-manager org-policies set-policy`](https://docs.cloud.google.com/sdk/gcloud/reference/resource-manager/org-policies/set-policy) command:

    ```
    gcloud resource-manager org-policies set-policy FILE_NAME.yaml \
        --organization=ORGANIZATION_NUMBER
    ```

### Restrict service account key creation

Workload Identity Federation lets you access Google Cloud resources from outside of Google Cloud without using a service account key. If you never use service account keys to authenticate, you can help reduce risk by disabling key creation.

To disable the creation of service account keys, enforce the `iam.disableServiceAccountKeyCreation` boolean constraint in the organization policy for your organization. You can also enforce the `iam.disableServiceAccountKeyUpload` boolean constraint, which disables uploading of public keys for service accounts.

> **Note** : If your organization was created on or after May 3, 2024, these constraints are enforced by default.

You can use the [Google Cloud console](https://docs.cloud.google.com/resource-manager/docs/organization-policy/creating-managing-policies#boolean_constraints) or the [gcloud CLI](https://docs.cloud.google.com/resource-manager/docs/organization-policy/using-constraints#boolean-constraint) to enable these constraints. For example, the following gcloud CLI commands enable both constraints:

```
gcloud resource-manager org-policies enable-enforce \
    constraints/iam.disableServiceAccountKeyCreation \
    --organization=ORGANIZATION_NUMBER
gcloud resource-manager org-policies enable-enforce \
    constraints/iam.disableServiceAccountKeyUpload \
    --organization=ORGANIZATION_NUMBER
```

## Monitor Workload Identity Federation

You can use [Cloud Monitoring](https://docs.cloud.google.com/monitoring/docs) metrics to monitor authentication events for your workload identity pools and providers. For a list of available metrics, see [IAM metrics](https://docs.cloud.google.com/monitoring/api/metrics_gcp_i_o#gcp-iam) .

## What's next

Learn more about [Workload Identity Federation](https://docs.cloud.google.com/iam/docs/workload-identity-federation) .
