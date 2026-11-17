---
name: documents/docs.cloud.google.com/iam/docs/unified-access-policies-remove
uri: https://docs.cloud.google.com/iam/docs/unified-access-policies-remove
title: Remove Unified Access Policies
description: How to remove Unified Access Policies from resources.
data_source: docs.cloud.google.com
---

> **Preview**
>
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

Unified Access Policies (UAPs) let you grant and deny principals access to Google Cloud resources. If you no longer want a UAP to apply to a resource, you can delete the policy binding that binds the policy to the resource. If you want to remove a policy from all resources that it's bound to, you can delete the policy.

## Before you begin

1.  Set up authentication.

    Select the tab for how you plan to use the samples on this page:

    ### Console

    When you use the Google Cloud console to access Google Cloud services and APIs, you don't need to set up authentication.

    ### gcloud

    In the Google Cloud console, activate Cloud Shell.

    At the bottom of the Google Cloud console, a [Cloud Shell](https://docs.cloud.google.com/shell/docs/how-cloud-shell-works) session starts and displays a command-line prompt. Cloud Shell is a shell environment with the Google Cloud CLI already installed and with values already set for your current project. It can take a few seconds for the session to initialize.

    ### REST

    To use the REST API samples on this page in a local development environment, you use the credentials you provide to the gcloud CLI.

    [Install](https://docs.cloud.google.com/sdk/docs/install) the Google Cloud CLI.

    If you're using an external identity provider (IdP), you must first [sign in to the gcloud CLI with your federated identity](https://docs.cloud.google.com/iam/docs/workforce-log-in-gcloud) .

    For more information, see [Authenticate for using REST](https://docs.cloud.google.com/docs/authentication/rest) in the Google Cloud authentication documentation.

2.  [Verify that billing is enabled for your Google Cloud project](https://docs.cloud.google.com/billing/docs/how-to/verify-billing-enabled#confirm_billing_is_enabled_on_a_project) .

3.  Optional: Read the [overview of UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies) .

### Roles required to delete Unified Access Policy bindings

To get the permissions that you need to delete a binding for a UAP, ask your administrator to grant you the following IAM roles:

- [Access Policy User ( `roles/iam.accessPolicyUser` )](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyUser) on the resource that owns the UAP. This role includes the `iam.accesspolicies.unbind` permission, which is required to delete bindings.

- A role that includes the permission `SERVICE `` . `` RESOURCE `` .deletePolicyBinding` , where `RESOURCE` is the resource type that the UAP is bound to and `SERVICE` is the service that owns the resource.

  To find a role that includes the required permission, search for the permission in the [role and permission reference](https://docs.cloud.google.com/iam/docs/roles-permissions) , click the permission name, and then review the roles that include the permission.

  You need this role on the resource or one of its ancestors.

For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

### Roles required to delete Unified Access Policies

To get the permissions that you need to delete UAPs, ask your administrator to grant you the [Access Policy Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin) ( `roles/iam.accessPolicyAdmin` ) IAM role on the project, folder, or organization that owns the UAP that you want to delete. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

This predefined role contains the permissions required to delete UAPs. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to delete UAPs:

- `iam.accesspolicies.delete`
- Delete UAPs in the Google Cloud console:
  - `iam.accesspolicies.get`
  - `iam.accessPolicies.list`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Remove a Unified Access Policy from a resource

To remove a UAP from a resource, delete the binding that binds the UAP to the resource. After you delete the binding, the UAP no longer applies to the resource or the resource's descendants. However, the UAP is not deleted and none of its other bindings are affected.

You can delete bindings for projects, folders, and organizations using the Google Cloud console, the gcloud CLI, or the IAM REST API. To delete bindings for other resources, you must use the gcloud CLI or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Unified Access Policies** page.

2.  Select the project, folder, or organization that owns the UAP that you want to remove.

3.  Click the policy ID of the UAP that you want to remove.

4.  Select the **Bindings** tab.

5.  In the **Bindings** table, find the row containing the binding that you want to remove.

6.  In that row, click the **Actions** menu, and then click **Delete binding** .

7.  In the **Delete binding** dialog, click **Delete** .

### gcloud

The [`gcloud iam policy-bindings delete`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/delete) command deletes a binding.

Before using any of the command data below, make the following replacements:

- `BINDING_ID` : The ID of the binding that you want to delete—for example, `example-binding` .

- `BINDING_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that the binding is a child of. Use the value `project` , `folder` , or `organization` .

  The binding's parent resource depends on the target resource in the binding. For more information, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) .

- `BINDING_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that the policy binding is a child of. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam policy-bindings delete BINDING_ID \
    --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID --location=global
```

#### Windows (PowerShell)

```
gcloud iam policy-bindings delete BINDING_ID `
    --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID --location=global
```

#### Windows (cmd.exe)

```
gcloud iam policy-bindings delete BINDING_ID ^
    --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID --location=global
```

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/unified-access-policies-remove#check-lro) on this page.

```
Delete request issued for: [example-binding]
Waiting for operation [organizations/123456789012/locations/global/operations/operation-1715374724030-6181fcd1520c5-d21b0a12-b704e1ce] to complete...done.
Deleted policyBinding [example-binding].
```

### REST

The [`policyBindings.delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings/delete) method deletes a binding.

Before using any of the request data, make the following replacements:

- `BINDING_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that the binding is a child of. Use the value `projects` , `folders` , or `organizations` .

  The binding's parent resource depends on the target resource in the binding. For more information, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) .

- `BINDING_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that the policy binding is a child of. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

- `BINDING_ID` : The ID of the binding that you want to delete—for example, `example-binding` .

HTTP method and URL:

```
DELETE https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings/BINDING_ID
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X DELETE \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings/BINDING_ID"
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
    -Uri "https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings/BINDING_ID" | Select-Object -Expand Content
```

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/unified-access-policies-remove#check-lro) on this page.

```
{
  "name": "organizations/123456789012/locations/global/operations/operation-1715373190994-6181f71b4daad-6d8168c1-13cc6600",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v3.OperationMetadata",
    "createTime": "2026-05-10T20:33:11.165728913Z",
    "target": "organizations/123456789012/locations/global/policyBindings/example-binding",
    "verb": "delete",
    "requestedCancellation": false,
    "apiVersion": "v3"
  },
  "done": false
}
```

## Delete a Unified Access Policy

Before you delete a UAP, [identify](https://docs.cloud.google.com/iam/docs/unified-access-policies-view#search-policy-bindings) and [delete](https://docs.cloud.google.com/iam/docs/unified-access-policies-remove#delete-binding) all existing bindings that reference the UAP. Attempts to delete a UAP without deleting existing bindings result in an error.

If you want to delete a UAP without deleting existing bindings, then you can forcefully delete the UAP. Forcefully deleting a UAP removes it from all of the resources that it's bound to. Any bindings that reference the UAP will eventually be deleted. However, until they are deleted, the bindings still count against the limit of the number of bindings that can refer to a single resource.

You can delete UAPs using the Google Cloud console, the gcloud CLI, or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Unified Access Policies** page.

2.  Select the project, folder, or organization that owns the UAP that you want to delete.

3.  Click the policy ID of the UAP that you want to delete.

4.  Click **Delete policy** .

5.  If the UAP has existing bindings, then select **Delete this policy and all of its bindings** . If you try to delete a UAP with existing bindings without selecting this option, then the request fails.

6.  In the **Delete policy** dialog, click **Delete** .

### gcloud

The [`gcloud iam access-policies delete`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/delete) command deletes a UAP and all associated bindings.

Before using any of the command data below, make the following replacements:

- `UAP_ID` : The ID of the UAP that you want to delete—for example, `example-policy` .
- `UAP_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that owns the UAP that you want to delete. Use the value `project` , `folder` , or `organization` .
- `UAP_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that owns the UAP that you want to delete. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .
- `FORCE_FLAG` : Optional. To force the command to delete a policy, even if that policy is referenced in existing bindings, use the flag `--force` . If this flag is not set and the policy is referenced in existing bindings, then the command fails.

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam access-policies delete UAP_ID \
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID --location=global \
    FORCE_FLAG
```

#### Windows (PowerShell)

```
gcloud iam access-policies delete UAP_ID `
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID --location=global `
    FORCE_FLAG
```

#### Windows (cmd.exe)

```
gcloud iam access-policies delete UAP_ID ^
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID --location=global ^
    FORCE_FLAG
```

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/unified-access-policies-remove#check-lro) on this page.

```
Delete request issued for: [example-policy]
Waiting for operation [organizations/123456789012/locations/global/operations/operation-1715374811191-6181fd2471ab4-f0947406-85778c43] to complete...done.
Deleted accessPolicy [example-policy].
```

### REST

The [`accessPolicies.delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/delete) method deletes a UAP and all associated bindings.

Before using any of the request data, make the following replacements:

- `UAP_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that owns the UAP that you want to delete. Use the value `projects` , `folders` , or `organizations` .
- `UAP_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that owns the UAP that you want to delete. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .
- `UAP_ID` : The ID of the UAP that you want to delete—for example, `example-policy` .
- `FORCE_DELETE` : Optional. To force the request to delete the policy, even if the policy is referenced in existing bindings, add the query parameter `force=true` . If this query parameter is not set and the policy is referenced in existing bindings, then the request fails.

HTTP method and URL:

```
DELETE https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies/UAP_ID?FORCE_DELETE
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X DELETE \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies/UAP_ID?FORCE_DELETE"
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
    -Uri "https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies/UAP_ID?FORCE_DELETE" | Select-Object -Expand Content
```

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/unified-access-policies-remove#check-lro) on this page.

```
{
  "name": "organizations/123456789012/locations/global/operations/operation-1715373190994-6181f71b4daad-6d8168c1-13cc6600",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v3.OperationMetadata",
    "createTime": "2026-05-10T20:33:11.165728913Z",
    "target": "organizations/123456789012/locations/global/accessPolicies/example-policy",
    "verb": "delete",
    "requestedCancellation": false,
    "apiVersion": "v3"
  },
  "done": false
}
```

## Check the status of a long-running operation

When you use the REST API or the client libraries, any method that changes a policy or binding returns a long-running operation (LRO). The long-running operation tracks the status of the request and indicates whether the change to the policy or binding is complete.

> **Note** : When you modify a policy or binding using the gcloud CLI, the gcloud CLI shows a message saying that it's waiting for an operation to complete. However, you must use the REST API or the client libraries to get the operation's status.

### REST

The [`operations.get`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.operations/get) method returns the status of a long-running operation.

Before using any of the request data, make the following replacements:

- `OPERATION_NAME` : The full name of the operation. You receive this name in the response to your original request.

  The operation name has the following format:

  ```
  RESOURCE_TYPE/RESOURCE_ID/locations/global/operations/OPERATION_ID
  ```

HTTP method and URL:

```
GET https://iam.googleapis.com/v3/OPERATION_NAME
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X GET \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v3/OPERATION_NAME"
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
    -Uri "https://iam.googleapis.com/v3/OPERATION_NAME" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.operations/get) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Complete any required fields and click **Execute** .

You should receive a JSON response similar to the following:

```
{
  "name": "organizations/314340013352/locations/global/operations/operation-1732752311821-627edd607a3df-9a62cdea-2a7d9f07",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v3.OperationMetadata",
    "createTime": "2024-11-28T00:05:12.006289686Z",
    "endTime": "2024-11-28T00:05:12.192141801Z",
    "target": "organizations/314340013352/locations/global/POLICY_TYPE/POLICY_ID",
    "verb": "create",
    "requestedCancellation": false,
    "apiVersion": "v3"
  },
  "done": true,
  "response": {
    POLICY
  }
}
```

If the operation's `done` field is not present, continue to monitor its status by getting the operation repeatedly. Use [truncated exponential backoff](https://docs.cloud.google.com/iam/docs/retry-strategy#algorithm) to introduce a delay between each request. When the `done` field is set to `true` , the operation is complete, and you can stop getting the operation.

## What's next

- [Create and apply UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies-create-apply)
- [View UAPs and bindings](https://docs.cloud.google.com/iam/docs/unified-access-policies-view)
- [Edit UAPs and bindings](https://docs.cloud.google.com/iam/docs/unified-access-policies-edit)
