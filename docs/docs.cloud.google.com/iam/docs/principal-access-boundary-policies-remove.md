---
name: documents/docs.cloud.google.com/iam/docs/principal-access-boundary-policies-remove
uri: https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-remove
title: Remove principal access boundary policies
description: How to remove principal access boundary policies from principal sets.
data_source: docs.cloud.google.com
---

Principal access boundary (PAB) policies let you limit the resources that a set of principals are eligible to access. If you no longer want a principal access boundary policy to be enforced for a principal set, you can delete the policy binding that binds the policy to the principal set. If you want to remove a principal access boundary policy from all principal sets that it's bound to, you can delete the policy.

Removing a principal access boundary policy from a principal set has one of the following effects:

  - If the principals in the principal set aren't subject to any other principal access boundary policies, then they will be eligible to access all Google Cloud resources.
  - If the principals in the principal set are subject to other principal access boundary policies, then they will only be eligible to access the resources in those policies.

## Before you begin

  - Set up authentication.
    
    Select the tab for how you plan to use the samples on this page:
    
    ### gcloud
    
    In the Google Cloud console, activate Cloud Shell.
    
    At the bottom of the Google Cloud console, a [Cloud Shell](https://docs.cloud.google.com/shell/docs/how-cloud-shell-works) session starts and displays a command-line prompt. Cloud Shell is a shell environment with the Google Cloud CLI already installed and with values already set for your current project. It can take a few seconds for the session to initialize.
    
    ### REST
    
    To use the REST API samples on this page in a local development environment, you use the credentials you provide to the gcloud CLI.
    
    For more information, see [Authenticate for using REST](https://docs.cloud.google.com/docs/authentication/rest) in the Google Cloud authentication documentation.

  - Read the [overview of principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies) .

### Roles required to delete principal access boundary policies

To get the permission that you need to delete principal access boundary policies, ask your administrator to grant you the [Principal Access Boundary Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin) ( `roles/iam.principalAccessBoundaryAdmin` ) IAM role on your organization. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

This predefined role contains the `iam.principalaccessboundarypolicies.delete` permission, which is required to delete principal access boundary policies.

You might also be able to get this permission with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

### Roles required to delete principal access boundary policy bindings

The permissions that you need in order to delete policy bindings for principal access boundary policies depends on the principal set that's bound to the policy.

To get the permissions that you need to delete policy bindings for principal access boundary policies, ask your administrator to grant you the following IAM roles:

  - [Principal Access Boundary User](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryUser) ( `roles/iam.principalAccessBoundaryUser` ) on your organization
  - Delete policy bindings for principal access boundary policies bound to workforce identity pools: [IAM Workforce Pool Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin) ( `roles/iam.workforcePoolAdmin` ) on the target workforce identity pool
  - Delete policy bindings for principal access boundary policies bound to workload identity pools: [IAM Workload Identity Pool Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin) ( `roles/iam.workloadIdentityPoolAdmin` ) on the project that owns the target workload identity pool
  - Get the status of a long-running operation for deleting a binding that references a workload identity pool: [IAM Operation Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.operationViewer) ( `roles/iam.operationViewer` ) on the project that owns the target workload identity pool
  - Delete policy bindings for principal access boundary policies bound to a Google Workspace domain: [Workspace Pool IAM Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workspacePoolAdmin) ( `roles/iam.workspacePoolAdmin` ) on the organization
  - Delete policy bindings for principal access boundary policies bound to a project's principal set: [Project IAM Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin) ( `roles/resourcemanager.projectIamAdmin` ) on the project
  - Get the status of a long-running operation for deleting a binding that references a project's principal set: [IAM Operation Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.operationViewer) ( `roles/iam.operationViewer` ) on the project
  - Delete policy bindings for principal access boundary policies bound to a folder's principal set: [Folder IAM Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin) ( `roles/resourcemanager.folderIamAdmin` ) on the folder
  - Delete policy bindings for principal access boundary policies bound to an organization's principal set: [Organization Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin) ( `roles/resourcemanager.organizationAdmin` ) on the organization

For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

These predefined roles contain the permissions required to delete policy bindings for principal access boundary policies. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to delete policy bindings for principal access boundary policies:

  - `iam.principalaccessboundarypolicies.unbind` on the organization
  - Delete policy bindings for principal access boundary policies bound to workforce identity pools: `iam.workforcePools.deletePolicyBinding` on the target workforce identity pool
  - Delete policy bindings for principal access boundary policies bound to workload identity pools: `iam.workloadIdentityPools.deletePolicyBinding` on the project that owns the target workload identity pool
  - Get the status of a long-running operation for deleting a binding that references a workload identity pool: `iam.operations.get` on the project that owns the target workload identity pool
  - Delete policy bindings for principal access boundary policies bound to a Google Workspace domain: `iam.workspacePools.deletePolicyBinding` on the organization
  - Delete policy bindings for principal access boundary policies bound to a project's principal set: `resourcemanager.projects.deletePolicyBinding` on the project
  - Get the status of a long-running operation for deleting a binding that references a project's principal set: `iam.operations.get` on the project
  - Delete policy bindings for principal access boundary policies bound to a folder's principal set: `resourcemanager.folders.deletePolicyBinding` on the folder
  - Delete policy bindings for principal access boundary policies bound to an organization's principal set: `resourcemanager.organizations.deletePolicyBinding` on the organization

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Prepare to remove a principal access boundary policy

Before you remove a principal access boundary policy, decide which of the following goals you want to accomplish:

  - Make the principals in a principal set eligible to access all resources
  - Reduce the number of resources that the principals in a principal set are eligible to access

The following sections describe the steps to take to accomplish each of these goals.

### Make principals eligible to access all resources

If you want to make the principals in a principal set eligible to access all resources, then do the following:

1.  [Identify all principal access boundary policies bound to the principal set](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-view#search-target-bindings) .
2.  Remove all principal access boundary policies bound to the principal set by [deleting the relevant policy bindings](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-remove#delete-binding) .

If a principal isn't subject to any principal access boundary policies, then the principal is eligible to access all Google Cloud resources.

Being eligible to access a resource doesn't necessarily mean that a user is able to access a resource. For more information, see [Policy evaluation](https://docs.cloud.google.com/iam/docs/policy-types#evaluation) .

### Reduce the resources that principals are eligible to access

If the principals in a principal set are subject to multiple principal access boundary policies, then you can reduce the number of resources that the principals are eligible to access by removing one or more of the principal access boundary policies that they're subject to. However, don't, at any point, remove all of the principal access boundary policies that the principals are subject to—if you do, then the principals will be eligible to access all Google Cloud resources.

To remove a principal access boundary policy while ensuring that the principals in a principal set are always subject to at least one principal access boundary policy, follow these steps:

1.  [Identify all principal access boundary policies bound to the principal set](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-view#search-target-bindings) .

2.  Identify the principal access boundary policies that contain *only* resources that you want principals in the principal set to be eligible to access. These are the policies that you won't remove from the principal set.
    
    If you don't have any such policies, then [create a new principal access boundary policy](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create) with only resources that you want the principals to be eligible to access. Then, [attach the policy](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create#create-binding) to the principal set.

3.  Identify the principal access boundary policies that contain resources that you don't want principals in the principal set to be eligible to access. Then, remove those principal access boundary policies by [deleting the relevant policy binding](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-remove#delete-binding) .
    
    If you want to reduce access for specific principals, then add a [condition](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#conditions) to the policy binding instead of deleting it.

If you want to reduce the number of resources that a principal is eligible to access but don't want to remove any principal access boundary policies, you can instead modify the principal access boundary policies that the principal is subject to. To learn how to modify principal access boundary policies, see [Edit principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-edit) .

### Test the deletion of a principal access boundary policy or binding

Before you commit to deleting a principal access boundary policy or binding, we recommend testing how the change might affect your principals' access. You can use Policy Simulator to simulate a deletion and help you understand the potential impact of it.

To test a deletion, see the following procedures in the Policy Intelligence documentation:

  - [Simulate deleting principal access boundary rules](https://docs.cloud.google.com/policy-intelligence/docs/simulate-pab-policies#simulate-delete-rule)
  - [Simulate deleting a principal access boundary policy](https://docs.cloud.google.com/policy-intelligence/docs/simulate-pab-policies#simulate-delete-policy)
  - [Simulate deleting a binding for a principal access boundary policy](https://docs.cloud.google.com/policy-intelligence/docs/simulate-pab-policies#simulate-delete-binding)

To learn more about testing principal access boundary policies with Policy Simulator, see [Policy Simulator for principal access boundary policies](https://docs.cloud.google.com/policy-intelligence/docs/pab-simulator-overview) .

## Remove a principal access boundary policy from a principal set

Before you remove a principal access boundary policy from a principal set, first [prepare for the removal of the policy](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-remove#prepare) . Then, remove the policy by deleting the policy binding that binds the policy to the principal set.

> **Note:** If a principal isn't subject to any principal access boundary policies, then the principal is eligible to access all Google Cloud resources.

You can delete a policy binding using the Google Cloud console, the gcloud CLI, or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Principal Access Boundary policies** page.

2.  Select the organization that owns the principal access boundary policy whose binding you want to delete.

3.  Click the policy ID of the principal access boundary policy whose bindings you want to delete.

4.  Click the **Bindings** tab.

5.  Find the ID of the binding that you want to delete. In that binding's row, click more\_vert **Actions** , then click **Delete binding** .

6.  In the confirmation dialog, click **Delete** .

### gcloud

The `  gcloud iam policy-bindings delete  ` command deletes a policy binding.

Before using any of the command data below, make the following replacements:

  - `  BINDING_ID  ` : The ID of the policy binding that you want to delete—for example, `example-binding` .

  - `  RESOURCE_TYPE  ` : The type of the Resource Manager resource (project, folder, or organization) that the policy binding is a child of. Use the value `project` , `folder` , or `organization`
    
    The resource type depends on the principal set in the policy binding. To see which resource type to use, see [Supported principal types](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#principal-sets) .

  - `  RESOURCE_ID  ` : The ID of the project, folder, or organization that the policy binding is a child of. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

    gcloud iam policy-bindings delete BINDING_ID \
        --RESOURCE_TYPE=RESOURCE_ID --location=global

#### Windows (PowerShell)

    gcloud iam policy-bindings delete BINDING_ID `
        --RESOURCE_TYPE=RESOURCE_ID --location=global

#### Windows (cmd.exe)

    gcloud iam policy-bindings delete BINDING_ID ^
        --RESOURCE_TYPE=RESOURCE_ID --location=global

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-remove#get-lro) on this page.

    Delete request issued for: [example-binding]
    Waiting for operation [organizations/123456789012/locations/global/operations/operation-1715374724030-6181fcd1520c5-d21b0a12-b704e1ce] to complete...done.
    Deleted policyBinding [example-binding].

### REST

The `  policyBindings.delete  ` method deletes a policy binding.

Before using any of the request data, make the following replacements:

  - `  RESOURCE_TYPE  ` : The type of the Resource Manager resource (project, folder, or organization) that the policy binding is a child of. Use the value `projects` , `folders` , or `organizations`
    
    The resource type depends on the principal set in the policy binding. To see which resource type to use, see [Supported principal types](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#principal-sets) .

  - `  RESOURCE_ID  ` : The ID of the project, folder, or organization that the policy binding is a child of. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

  - `  BINDING_ID  ` : The ID of the policy binding that you want to delete—for example, `example-binding` .

HTTP method and URL:

    DELETE https://iam.googleapis.com/v3/RESOURCE_TYPE/RESOURCE_ID/locations/global/policyBindings/BINDING_ID

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

    curl -X DELETE \
         -H "Authorization: Bearer $(gcloud auth print-access-token)" \
         "https://iam.googleapis.com/v3/RESOURCE_TYPE/RESOURCE_ID/locations/global/policyBindings/BINDING_ID"

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

    $cred = gcloud auth print-access-token
    $headers = @{ "Authorization" = "Bearer $cred" }
    
    Invoke-WebRequest `
        -Method DELETE `
        -Headers $headers `
        -Uri "https://iam.googleapis.com/v3/RESOURCE_TYPE/RESOURCE_ID/locations/global/policyBindings/BINDING_ID" | Select-Object -Expand Content

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-remove#get-lro) on this page.

    {
      "name": "organizations/123456789012/locations/global/operations/operation-1715373190994-6181f71b4daad-6d8168c1-13cc6600",
      "metadata": {
        "@type": "type.googleapis.com/google.iam.v3.OperationMetadata",
        "createTime": "2024-05-10T20:33:11.165728913Z",
        "target": "organizations/123456789012/locations/global/policyBindings/example-binding",
        "verb": "delete",
        "requestedCancellation": false,
        "apiVersion": "v3"
      },
      "done": false
    }

## Delete a principal access boundary policy

Before you delete a principal access boundary policy, we recommend that you [identify](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-view#search-policy-bindings) and [delete](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-remove#delete-binding) all principal access boundary policy bindings that reference the principal access boundary policy.

If you delete a principal access boundary policy with existing policy bindings, then those bindings will eventually be deleted. However, until they are deleted, the policy bindings still count against the limit of 10 bindings that can refer to a single principal set.

> **Note:** If a principal isn't subject to any principal access boundary policies, then the principal is eligible to access all Google Cloud resources.

You can delete a principal access boundary policy using the Google Cloud console, the gcloud CLI, or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Principal Access Boundary policies** page.

2.  Select the organization that owns the principal access boundary policy whose binding you want to delete.

3.  Find the ID of the policy that you want to delete. In that policy's row, click more\_vert **Actions** , then click **Delete policy** .

4.  In the confirmation dialog, confirm that you want to delete the policy:
    
      - To delete the policy only if the policy doesn't have any bindings associated with it, click **Delete** .
      - To delete the policy and all associated bindings, select the **Forcefully delete policy** checkbox, then click **Delete** .

### gcloud

The `  gcloud iam gcloud iam principal-access-boundary-policies delete  ` command deletes a principal access boundary policy and all associated bindings.

Before using any of the command data below, make the following replacements:

  - `  PAB_POLICY_ID  ` : The ID of the principal access boundary policy that you want to delete—for example, `example-policy` .
  - `  ORG_ID  ` : The ID of the organization that owns the principal access boundary policy. Organization IDs are numeric, like `123456789012` .
  - `  FORCE_FLAG  ` : Optional. To force the command to delete a policy, even if that policy is referenced in existing policy bindings, use the flag `--force` . If this flag is not set and the policy is referenced in existing policy bindings, then the command fails.

Execute the following command:

#### Linux, macOS, or Cloud Shell

    gcloud iam principal-access-boundary-policies delete PAB_POLICY_ID \
        --organization=ORG_ID --location=global FORCE_FLAG

#### Windows (PowerShell)

    gcloud iam principal-access-boundary-policies delete PAB_POLICY_ID `
        --organization=ORG_ID --location=global FORCE_FLAG

#### Windows (cmd.exe)

    gcloud iam principal-access-boundary-policies delete PAB_POLICY_ID ^
        --organization=ORG_ID --location=global FORCE_FLAG

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-remove#get-lro) on this page.

    Delete request issued for: [example-policy]
    Waiting for operation [organizations/123456789012/locations/global/operations/operation-1715374811191-6181fd2471ab4-f0947406-85778c43] to complete...
    Waiting for operation [organizations/123456789012/locations/global/operations/operation-1715374811191-6181fd2471ab4-f0947406-85778c43] to complete...done.
    Deleted principalAccessBoundaryPolicy [example-policy].

### REST

The `  principalAccessBoundaryPolicies.delete  ` method deletes a principal access boundary policy and all associated bindings.

Before using any of the request data, make the following replacements:

  - `  ORG_ID  ` : The ID of the organization that owns the principal access boundary policy. Organization IDs are numeric, like `123456789012` .
  - `  PAB_POLICY_ID  ` : The ID of the principal access boundary policy that you want to delete—for example, `example-policy` .
  - `  FORCE_DELETE  ` : Optional. To force the request to delete the policy, even if the policy is referenced in existing policy bindings, add the query parameter `force=true` . If this query parameter is not set and the policy is referenced in existing policy bindings, then the request fails.

HTTP method and URL:

    DELETE https://iam.googleapis.com/v3/organizations/ORG_ID/locations/global/principalAccessBoundaryPolicies/PAB_POLICY_ID?FORCE_DELETE

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

    curl -X DELETE \
         -H "Authorization: Bearer $(gcloud auth print-access-token)" \
         "https://iam.googleapis.com/v3/organizations/ORG_ID/locations/global/principalAccessBoundaryPolicies/PAB_POLICY_ID?FORCE_DELETE"

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

    $cred = gcloud auth print-access-token
    $headers = @{ "Authorization" = "Bearer $cred" }
    
    Invoke-WebRequest `
        -Method DELETE `
        -Headers $headers `
        -Uri "https://iam.googleapis.com/v3/organizations/ORG_ID/locations/global/principalAccessBoundaryPolicies/PAB_POLICY_ID?FORCE_DELETE" | Select-Object -Expand Content

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-remove#get-lro) on this page.

    {
      "name": "organizations/123456789012/locations/global/operations/operation-1715373190994-6181f71b4daad-6d8168c1-13cc6600",
      "metadata": {
        "@type": "type.googleapis.com/google.iam.v3.OperationMetadata",
        "createTime": "2024-05-10T20:33:11.165728913Z",
        "target": "organizations/123456789012/locations/global/policyBindings/example-policy",
        "verb": "delete",
        "requestedCancellation": false,
        "apiVersion": "v3"
      },
      "done": false
    }

## Check the status of a long-running operation

When you use the REST API or the client libraries, any method that changes a principal access boundary policy or binding returns a long-running operation (LRO). The long-running operation tracks the status of the request and indicates whether the change to the policy or binding is complete.

> **Note** : When you modify a principal access boundary policy or binding using the gcloud CLI, the gcloud CLI shows a message saying that it's waiting for an operation to complete. However, you must use the REST API or the client libraries to get the operation's status.

### REST

The `  operations.get  ` method returns the status of a long-running operation.

Before using any of the request data, make the following replacements:

  - `  OPERATION_NAME  ` : The full name of the operation. You receive this name in the response to your original request.
    
    The operation name has the following format:
    
    ``` 
          RESOURCE_TYPE/RESOURCE_ID/locations/global/operations/OPERATION_ID
        
    ```

HTTP method and URL:

    GET https://iam.googleapis.com/v3/OPERATION_NAME

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

    curl -X GET \
         -H "Authorization: Bearer $(gcloud auth print-access-token)" \
         "https://iam.googleapis.com/v3/OPERATION_NAME"

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

    $cred = gcloud auth print-access-token
    $headers = @{ "Authorization" = "Bearer $cred" }
    
    Invoke-WebRequest `
        -Method GET `
        -Headers $headers `
        -Uri "https://iam.googleapis.com/v3/OPERATION_NAME" | Select-Object -Expand Content

#### APIs Explorer (browser)

Open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.operations/get) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Complete any required fields and click **Execute** .

You should receive a JSON response similar to the following:

    {
      "name": "organizations/314340013352/locations/global/operations/operation-1732752311821-627edd607a3df-9a62cdea-2a7d9f07",
      "metadata": {
        "@type": "type.googleapis.com/google.iam.v3.OperationMetadata",
        "createTime": "2024-11-28T00:05:12.006289686Z",
        "endTime": "2024-11-28T00:05:12.192141801Z",
        "target": "organizations/314340013352/locations/global/principalAccessBoundaryPolicies/example-policy",
        "verb": "create",
        "requestedCancellation": false,
        "apiVersion": "v3"
      },
      "done": true,
      "response": {
        PAB_POLICY
      }
    }

If the operation's `done` field is not present, continue to monitor its status by getting the operation repeatedly. Use [truncated exponential backoff](https://docs.cloud.google.com/iam/docs/retry-strategy#algorithm) to introduce a delay between each request. When the `done` field is set to `true` , the operation is complete, and you can stop getting the operation.

## What's next

  - [Create and apply principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create)
  - [View principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-view)
  - [Edit principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-edit)
