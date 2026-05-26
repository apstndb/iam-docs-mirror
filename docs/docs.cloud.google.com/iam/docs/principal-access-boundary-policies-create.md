---
name: documents/docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create
uri: https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create
title: Create and apply principal access boundary policies
description: How to create principal access boundary policies and apply them to principal sets.
data_source: docs.cloud.google.com
---

Principal access boundary (PAB) policies let you limit the resources that a set of principals are eligible to access. This page explains how to create and apply principal access boundary policies.

## Before you begin

  - Set up authentication.
    
    Select the tab for how you plan to use the samples on this page:
    
    ### Console
    
    When you use the Google Cloud console to access Google Cloud services and APIs, you don't need to set up authentication.
    
    ### gcloud
    
    In the Google Cloud console, activate Cloud Shell.
    
    At the bottom of the Google Cloud console, a [Cloud Shell](https://docs.cloud.google.com/shell/docs/how-cloud-shell-works) session starts and displays a command-line prompt. Cloud Shell is a shell environment with the Google Cloud CLI already installed and with values already set for your current project. It can take a few seconds for the session to initialize.
    
    ### REST
    
    To use the REST API samples on this page in a local development environment, you use the credentials you provide to the gcloud CLI.
    
    For more information, see [Authenticate for using REST](https://docs.cloud.google.com/docs/authentication/rest) in the Google Cloud authentication documentation.

  - Read the [overview of principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies) .

### Roles required to create principal access boundary policies

To get the permission that you need to create principal access boundary policies, ask your administrator to grant you the [Principal Access Boundary Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryAdmin) ( `roles/iam.principalAccessBoundaryAdmin` ) IAM role on your organization. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

This predefined role contains the `iam.principalaccessboundarypolicies.create` permission, which is required to create principal access boundary policies.

You might also be able to get this permission with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

### Roles required to apply principal access boundary policies

The permissions that you need in order to apply a principal access boundary policy depend on the principal set that you want to apply the policy to.

To get the permissions that you need to apply principal access boundary policies, ask your administrator to grant you the following IAM roles:

  - [Principal Access Boundary User](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.principalAccessBoundaryUser) ( `roles/iam.principalAccessBoundaryUser` ) on the organization
  - Apply principal access boundary policies to workforce identity pools: [IAM Workforce Pool Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workforcePoolAdmin) ( `roles/iam.workforcePoolAdmin` ) on the target workforce identity pool
  - Apply principal access boundary policies to workload identity pools: [IAM Workload Identity Pool Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin) ( `roles/iam.workloadIdentityPoolAdmin` ) on the project that owns the target workload identity pool
  - Get the status of a long-running operation for applying a principal access boundary policy to a workload identity pool: [IAM Operation Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.operationViewer) ( `roles/iam.operationViewer` ) on the project that owns the target workload identity pool
  - Apply principal access boundary policies to a Google Workspace domain: [Workspace Pool IAM Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workspacePoolAdmin) ( `roles/iam.workspacePoolAdmin` ) on the organization
  - Apply principal access boundary policies to a project's principal set: [Project IAM Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin) ( `roles/resourcemanager.projectIamAdmin` ) on the project
  - Get the status of a long-running operation for applying a principal access boundary policy to a project's principal set: [IAM Operation Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.operationViewer) ( `roles/iam.operationViewer` ) on the project
  - Apply principal access boundary policies to a folder's principal set: [Folder IAM Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin) ( `roles/resourcemanager.folderIamAdmin` ) on the folder
  - Apply principal access boundary policies to an organization's principal set: [Organization Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin) ( `roles/resourcemanager.organizationAdmin` ) on the organization

For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

These predefined roles contain the permissions required to apply principal access boundary policies. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to apply principal access boundary policies:

  - `iam.principalaccessboundarypolicies.bind` on the organization
  - Apply principal access boundary policies to Workforce Identity Federation pools: `iam.workforcePools.createPolicyBinding` on the target Workforce Identity Federation pool
  - Apply principal access boundary policies to Workload Identity Federation pools: `iam.workloadIdentityPools.createPolicyBinding` on the project that owns the target Workforce Identity Federation pool
  - Get the status of a long-running operation for applying a principal access boundary policy to a workload identity pool: `iam.operations.get` on the project that owns the target workload identity pool
  - Apply principal access boundary policies to a Google Workspace domain: `iam.workspacePools.createPolicyBinding` on the organization
  - Apply principal access boundary policies to a project's principal set: `resourcemanager.projects.createPolicyBinding` on the project
  - Get the status of a long-running operation for applying a principal access boundary policy to a project's principal set: `iam.operations.get` on the project
  - Apply principal access boundary policies to a folder's principal set: `resourcemanager.folders.createPolicyBinding` on the folder
  - Apply principal access boundary policies to an organization's principal set: `resourcemanager.organizations.createPolicyBinding` on the organization

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Create a principal access boundary policy

You can create a principal access boundary policy using the Google Cloud console, the gcloud CLI, or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Principal Access Boundary policies** page.

2.  Select the organization that you want to create principal access boundary policies for.

3.  Click add\_box **Create policy** .

4.  Add principal access boundary rules to the policy:
    
    1.  Click add\_box **Add boundary rule** .
    
    2.  In the **Description** field, add a description of the principal access boundary policy rule. The description can be a maximum of 256 characters.
    
    3.  In the **Resources** section, enter all of the Resource Manager resources (projects, folders, and organizations) that you want principals to be eligible to access. Any principal that is subject to this policy is eligible to access these resources.
        
        Each principal access boundary policy can reference a maximum of 500 resources across all rules in the policy.
    
    4.  Click **Done** .
    
    5.  To add additional policy rules, repeat these steps. Each principal access boundary policy can have up to 500 rules.

5.  In the **Policy name** section, enter a name for the policy. The name can be a maximum of 63 characters.

6.  In the **Enforcement version** list, select the enforcement version for the policy. The principal access boundary policy version determines which permissions IAM enforces the principal access boundary policy for.
    
    For more information about enforcement versions, see [Principal access boundary enforcement versions](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#versions) .

7.  Click **Create** .

### gcloud

The `  gcloud iam principal-access-boundary-policies create  ` command creates a principal access boundary policy.

Before using any of the command data below, make the following replacements:

  - `  ORG_ID  ` : The ID of the organization that you want to create the principal access boundary policy in. Organization IDs are numeric, like `123456789012` .

  - `  PAB_POLICY_ID  ` : A unique ID for the principal access boundary policy—for example, `example-policy` . :

  - `  DISPLAY_NAME  ` : Optional. A human-readable description of the principal access boundary policy—for example, `Example policy` . The display name can be a maximum of 63 characters.

  - `  FILE_PATH  ` : The path to a JSON file containing the principal access boundary policy rule details. This file should have the following format:
    
    ```json
    {
      "description": DESCRIPTION,
      "resources": [
        RESOURCES
      ],
      "effect": ALLOW
    }
        
    ```
    
    Replace the following values:
    
      - `  DESCRIPTION  ` : Optional. The description of the principal access boundary policy rule. The description can be a maximum of 256 characters.
    
      - `  RESOURCES  ` : A list of Resource Manager resources (projects, folders, and organizations) that you want principals to be eligible to access. Any principal that is subject to this policy is eligible to access these resources.
        
        Each principal access boundary policy can reference a maximum of 500 resources across all rules in the policy.

  - `  ENFORCEMENT_VERSION  ` : The version of principal access boundary policies that IAM uses when enforcing the policy. The enforcement version determines which permissions IAM enforces the principal access boundary policy for.
    
    Accepted values are `1` , `2` , `3` , `4` , and `latest` .
    
    For more information about enforcement versions, see [Principal access boundary enforcement versions](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#versions) .

Execute the following command:

#### Linux, macOS, or Cloud Shell

    gcloud iam principal-access-boundary-policies create PAB_POLICY_ID \
        --organization=ORG_ID --location=global \
        --display-name=DISPLAY_NAME --details-rules=FILE_PATH.json \
        --details-enforcement-version=ENFORCEMENT_VERSION

#### Windows (PowerShell)

    gcloud iam principal-access-boundary-policies create PAB_POLICY_ID `
        --organization=ORG_ID --location=global `
        --display-name=DISPLAY_NAME --details-rules=FILE_PATH.json `
        --details-enforcement-version=ENFORCEMENT_VERSION

#### Windows (cmd.exe)

    gcloud iam principal-access-boundary-policies create PAB_POLICY_ID ^
        --organization=ORG_ID --location=global ^
        --display-name=DISPLAY_NAME --details-rules=FILE_PATH.json ^
        --details-enforcement-version=ENFORCEMENT_VERSION

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create#get-lro) on this page.

    Create request issued for: [example-policy]
    Waiting for operation [organizations/123456789012/locations/global/operations/operation-1715373988044-6181fa136df85-3b06a30a-4816d25b] to complete...done.
    Created principalAccessBoundaryPolicy [example-policy].

### REST

The `  principalAccessBoundaryPolicies.create  ` method creates a principal access boundary policy.

Before using any of the request data, make the following replacements:

  - `  ORG_ID  ` : The ID of the organization that you want to create the principal access boundary policy in. Organization IDs are numeric, like `123456789012` .

  - `  PAB_POLICY_ID  ` : A unique ID for the principal access boundary policy—for example, `example-policy` .

  - `  DISPLAY_NAME  ` : Optional. A human-readable description of the principal access boundary policy—for example, `Example policy` . The display name can be a maximum of 63 characters.

  - `  PAB_RULES  ` : A list of principal access boundary rules, which define the resources that affected principals are eligible to access. A principal access boundary policy can have up to 500 rules. Each rule has the following format:
    
        {
        "description": "DESCRIPTION",
        "resources": [
          RESOURCES
        ],
        "effect": ALLOW
        }
    
    Replace the following values:
    
      - `  DESCRIPTION  ` : Optional. The description of the principal access boundary policy rule. The description can be a maximum of 256 characters.
    
      - `  RESOURCES  ` : A list of Resource Manager resources (projects, folders, and organizations) that you want principals to be eligible to access. Any principal that is subject to this policy is eligible to access these resources.
        
        Each principal access boundary policy can reference a maximum of 500 resources across all rules in the policy.

  - `  ENFORCEMENT_VERSION  ` : The version of principal access boundary policies that IAM uses when enforcing the policy. The enforcement version determines which permissions IAM enforces the principal access boundary policy for.
    
    Accepted values are `1` , `2` , `3` , `4` , and `latest` .
    
    For more information about enforcement versions, see [Principal access boundary enforcement versions](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#versions) .

HTTP method and URL:

    POST https://iam.googleapis.com/v3/organizations/ORG_ID/locations/global?principalAccessBoundaryPolicyId=PAB_POLICY_ID

Request JSON body:

    {
      "displayName": DISPLAY_NAME,
      "details": {
        "rules": [
          PAB_RULES
        ],
        "effect": ALLOW
        }
      ],
      "enforcementVersion": "ENFORCEMENT_VERSION"
    }

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

    curl -X POST \
         -H "Authorization: Bearer $(gcloud auth print-access-token)" \
         -H "Content-Type: application/json; charset=utf-8" \
         -d @request.json \
         "https://iam.googleapis.com/v3/organizations/ORG_ID/locations/global?principalAccessBoundaryPolicyId=PAB_POLICY_ID"

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

    $cred = gcloud auth print-access-token
    $headers = @{ "Authorization" = "Bearer $cred" }
    
    Invoke-WebRequest `
        -Method POST `
        -Headers $headers `
        -ContentType: "application/json; charset=utf-8" `
        -InFile request.json `
        -Uri "https://iam.googleapis.com/v3/organizations/ORG_ID/locations/global?principalAccessBoundaryPolicyId=PAB_POLICY_ID" | Select-Object -Expand Content

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create#get-lro) on this page.

    {
      "name": "organizations/123456789012/locations/global/operations/operation-1715373120647-6181f6d8371d2-83309b71-2b8a7532",
      "metadata": {
        "@type": "type.googleapis.com/google.iam.v3.OperationMetadata",
        "createTime": "2024-05-10T20:32:00.898809495Z",
        "target": "organizations/123456789012/locations/global/policyBindings/example-policy",
        "verb": "create",
        "requestedCancellation": false,
        "apiVersion": "v3"
      },
      "done": false
    }

## Apply a principal access boundary policy to a principal set

To apply a principal access boundary policy to a principal set, create a policy binding resource that binds the policy to the principal set. After you create a policy binding, the principal access boundary policy in the binding is enforced for the principals in the binding.

You can create a policy binding using the Google Cloud console, the gcloud CLI, or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Principal Access Boundary policies** page.

2.  Select the organization that owns the principal access boundary policy that you want to create a binding for.

3.  Click the policy ID of the principal access boundary policy that you want to create a binding for.

4.  Click the **Bindings** tab, then click add\_box **Add binding** .

5.  Enter the binding details:
    
    1.  Optional: In the **Display name** field, enter a display name for the binding. The display name can be a maximum of 63 characters.
    
    2.  In the **Binding ID** field, enter a unique name for the binding—for example, `example-binding` .
    
    3.  In the **Target principal set** section, enter the type and ID of the principal set that you want to bind the policy to. You can't change this value after you create the policy binding.
        
        To learn more about the principals included in each principal set, see [Supported principal sets](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#principal-sets) .

6.  Optional: To specify which principals in the principal set the principal access boundary policy is enforced for, add a condition to the binding:
    
    1.  Click add **Add condition** .
    2.  In the **Title** field, enter a brief summary of the purpose of the condition.
    3.  Optional: In the **Description** field, enter a longer description of the condition.
    4.  In the **Expression** field, enter condition expression that uses the [Common Expression Language (CEL) syntax](https://github.com/google/cel-spec/blob/master/doc/langdef.md) . The expression must reference the [`principal.type` or `principal.subject` attributes](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#principals) . Other attributes are not supported.
    5.  Click **Save** .

7.  Optional: To test your changes to the principal access boundary policy with Policy Simulator, click **Test changes** . Review the [simulation results](https://docs.cloud.google.com/policy-intelligence/docs/simulate-pab-policies#view-results) and update the policy if necessary.
    
    To learn more about testing principal access boundary policies with Policy Simulator, see [Policy Simulator for principal access boundary policies](https://docs.cloud.google.com/policy-intelligence/docs/pab-simulator-overview) .

8.  To create the binding, click **Add** .

### gcloud

The `  gcloud iam policy-bindings create  ` command creates a policy binding.

Before using any of the command data below, make the following replacements:

  - `  BINDING_ID  ` : A unique name for the policy binding—for example, `example-binding` .

  - `  RESOURCE_TYPE  ` : The type of the Resource Manager resource (project, folder, or organization) that the policy binding is a child of. Use the value `project` , `folder` , or `organization`
    
    The resource type depends on the principal set in the policy binding. To see which resource type to use, see [Supported principal types](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#principal-sets) .

  - `  RESOURCE_ID  ` : The ID of the project, folder, or organization that the policy binding is a child of. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

  - `  ORG_ID  ` : The ID of the organization that owns the principal access boundary policy that you want to bind to the principal set. Organization IDs are numeric, like `123456789012` .

  - `  PAB_POLICY_ID  ` : The ID of the principal access boundary policy that you want to bind to the principal set—for example, `example-pab-policy` . You can't change this value after you create the policy binding.

  - `  PRINCIPAL_SET  ` : The principal set that you want to bind the policy to. For a list of valid principal types, see [Supported principal sets](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#principal-sets) . You can't change this value after you create the policy binding.

  - `  DISPLAY_NAME  ` : Optional. A human-readable description of the binding—for example, `Example binding` . The display name can be a maximum of 63 characters.

  - `  CONDITION_DETAILS  ` : Optional. A [condition expression](https://docs.cloud.google.com/iam/docs/conditions-overview) that specifies which principals in the principal set the principal access boundary policy is enforced for. Contains the following fields:
    
      - `expression` : A condition expression that uses [Common Expression Language (CEL) syntax](https://github.com/google/cel-spec/blob/master/doc/langdef.md) . The expression must reference the [`principal.type` or `principal.subject` attributes](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#principals) . Other attributes are not supported.
        
        The expression can contain up to 10 logical operators ( `&&` , `||` , `!` ), and can be up to 250 characters long.
    
      - `title` : Optional. A brief summary of the purpose of the condition.
    
      - `description` : Optional. A longer description of the condition.

Execute the following command:

#### Linux, macOS, or Cloud Shell

    gcloud iam policy-bindings create BINDING_ID \
        --RESOURCE_TYPE=RESOURCE_ID --location=global \
        --policy="organizations/ORG_ID/locations/global/principalAccessBoundaryPolicies/PAB_POLICY_ID" \
        --target-principal-set=PRINCIPAL_SET_ID \
        --display-name=DISPLAY_NAME \
        CONDITION_DETAILS

#### Windows (PowerShell)

    gcloud iam policy-bindings create BINDING_ID `
        --RESOURCE_TYPE=RESOURCE_ID --location=global `
        --policy="organizations/ORG_ID/locations/global/principalAccessBoundaryPolicies/PAB_POLICY_ID" `
        --target-principal-set=PRINCIPAL_SET_ID `
        --display-name=DISPLAY_NAME `
        CONDITION_DETAILS

#### Windows (cmd.exe)

    gcloud iam policy-bindings create BINDING_ID ^
        --RESOURCE_TYPE=RESOURCE_ID --location=global ^
        --policy="organizations/ORG_ID/locations/global/principalAccessBoundaryPolicies/PAB_POLICY_ID" ^
        --target-principal-set=PRINCIPAL_SET_ID ^
        --display-name=DISPLAY_NAME ^
        CONDITION_DETAILS

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create#get-lro) on this page.

    Create request issued for: [example-binding]
    Waiting for operation [organizations/123456789012/locations/global/operations/operation-1715374545618-6181fc272c6f9-55ff07f4-97d0ac76] to complete...done.
    Created policyBinding [example-binding].

### REST

The `  policyBindings.create  ` method creates a policy binding.

Before using any of the request data, make the following replacements:

  - `  RESOURCE_TYPE  ` : The type of the Resource Manager resource (project, folder, or organization) that the policy binding is a child of. Use the value `projects` , `folders` , or `organizations`
    
    The resource type depends on the principal set in the policy binding. To see which resource type to use, see [Supported principal types](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#principal-sets) .

  - `  RESOURCE_ID  ` : The ID of the project, folder, or organization that the policy binding is a child of. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

  - `  BINDING_ID  ` : A unique name for the policy binding—for example, `example-binding` .

  - `  DISPLAY_NAME  ` : Optional. A human-readable description of the binding—for example, `Example binding` . The display name can be a maximum of 63 characters.

  - `  PRINCIPAL_SET  ` : The principal set that you want to bind the policy to. For a list of valid principal types, see [Supported principal sets](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies#principal-sets) . You can't change this value after you create the policy binding.

  - `  ORG_ID  ` : The ID of the organization that owns the principal access boundary policy that you want to bind to the principal set. Organization IDs are numeric, like `123456789012` .

  - `  PAB_POLICY_ID  ` : The ID of the principal access boundary policy that you want to bind to the principal set—for example, `example-pab-policy` . You can't change this value after you create the policy binding.

  - `  CONDITION_DETAILS  ` : Optional. A [condition expression](https://docs.cloud.google.com/iam/docs/conditions-overview) that specifies which principals in the principal set the principal access boundary policy is enforced for. Contains the following fields:
    
      - `expression` : A condition expression that uses [Common Expression Language (CEL) syntax](https://github.com/google/cel-spec/blob/master/doc/langdef.md) . The expression must reference the [`principal.type` or `principal.subject` attributes](https://docs.cloud.google.com/iam/docs/conditions-attribute-reference#principals) . Other attributes are not supported.
        
        The expression can contain up to 10 logical operators ( `&&` , `||` , `!` ), and can be up to 250 characters long.
    
      - `title` : Optional. A brief summary of the purpose of the condition.
    
      - `description` : Optional. A longer description of the condition.

HTTP method and URL:

    POST https://iam.googleapis.com/v3/RESOURCE_TYPE/RESOURCE_ID/locations/global/policyBindings?policyBindingId=BINDING_ID

Request JSON body:

    {
      "displayName": DISPLAY_NAME,
      "target": {
        "principalSet": PRINCIPAL_SET
      },
      "policyKind": "PRINCIPAL_ACCESS_BOUNDARY",
      "policy": "organizations/ORG_ID/locations/global/principalAccessBoundaryPolicies/PAB_POLICY_ID",
      "condition": {
        CONDITION_DETAILS
      }
    }

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

    curl -X POST \
         -H "Authorization: Bearer $(gcloud auth print-access-token)" \
         -H "Content-Type: application/json; charset=utf-8" \
         -d @request.json \
         "https://iam.googleapis.com/v3/RESOURCE_TYPE/RESOURCE_ID/locations/global/policyBindings?policyBindingId=BINDING_ID"

#### PowerShell (Windows)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Save the request body in a file named `request.json` , and execute the following command:

    $cred = gcloud auth print-access-token
    $headers = @{ "Authorization" = "Bearer $cred" }
    
    Invoke-WebRequest `
        -Method POST `
        -Headers $headers `
        -ContentType: "application/json; charset=utf-8" `
        -InFile request.json `
        -Uri "https://iam.googleapis.com/v3/RESOURCE_TYPE/RESOURCE_ID/locations/global/policyBindings?policyBindingId=BINDING_ID" | Select-Object -Expand Content

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-create#get-lro) on this page.

    {
      "name": "organizations/123456789012/locations/global/operations/operation-1715373120647-6181f6d8371d2-83309b71-2b8a7532",
      "metadata": {
        "@type": "type.googleapis.com/google.iam.v3.OperationMetadata",
        "createTime": "2024-05-10T20:32:00.898809495Z",
        "target": "organizations/123456789012/locations/global/policyBindings/example-binding",
        "verb": "create",
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

  - [View principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-view)
  - [Edit principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-edit)
  - [Remove principal access boundary policies](https://docs.cloud.google.com/iam/docs/principal-access-boundary-policies-remove)
