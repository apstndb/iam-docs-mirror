---
name: documents/docs.cloud.google.com/iam/docs/unified-access-policies-create-apply
uri: https://docs.cloud.google.com/iam/docs/unified-access-policies-create-apply
title: Create and apply Unified Access Policies
description: How to create Unified Access Policies and apply them to resources
data_source: docs.cloud.google.com
---

> **Preview**
>
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

Unified Access Policies (UAPs) let you grant and deny principals access to Google Cloud resources. This document explains how to create and apply UAPs.

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

### Roles required to create Unified Access Policies

To get the permissions that you need to create UAPs, ask your administrator to grant you the [Access Policy Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin) ( `roles/iam.accessPolicyAdmin` ) IAM role on the project, folder, or organization where you want to create the policy . For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

This predefined role contains the permissions required to create UAPs. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to create UAPs:

- `iam.accesspolicies.create`
- Create UAPs in the Google Cloud console: `iam.accesspolicies.list`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

### Roles required to apply Unified Access Policies

To get the permissions that you need to bind a UAP to a resource, ask your administrator to grant you the following IAM roles:

- [Access Policy Admin ( `roles/iam.accessPolicyAdmin` )](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin) on the resource that owns the UAP. This role contains the `iam.accesspolicies.bind` permission, which is required to create bindings.

- A role that includes the permission `SERVICE `` . `` RESOURCE `` .createPolicyBinding` , where `RESOURCE` is the resource type that you want to bind the policy to and `SERVICE` is the service that owns the resource.

  To find a role that includes the required permission, search for the permission in the [role and permission reference](https://docs.cloud.google.com/iam/docs/roles-permissions) , click the permission name, and then review the roles that include the permission.

  You need this role on the resource or one of its ancestors.

For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

## Create a Unified Access Policy

You can create UAPs using the Google Cloud console, the gcloud CLI, or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Unified Access Policies** page.

2.  Select the project, folder, or organization that you want to create the UAP in. For guidance about where to create a UAP, see [Where to create UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies#where-to-create) .

3.  Click **Create policy** .

4.  In the **Policy name** field, enter a name for the UAP—for example, `Example policy` . The name can be a maximum of 63 characters.

5.  Optional: In the **Policy ID** field, customize the ID for the UAP.

6.  Add rules to the policy. For each rule, do the following:

    1.  Optional: In the **Description** field, enter a description for the rule.

    2.  In the **Principals** field, enter the principals that you want to include in the rule.

    3.  Optional: In the **Excluded principals** field, enter the principals that you don't want to include in the rule. These principals won't be included, even if they're part of a group in the **Principals** field.

    4.  Select the effect that you want the rule to have:

        - To grant the specified permissions to the specified principals, select the **Allow** effect.
        - To prevent the specified principals from using the specified permissions, select the **Deny** effect.

    5.  Select the permissions to include in the rule:

        - For rules with the **Allow** effect, you can specify roles and permissions to include in or exclude from the rule. For more information about the roles and permissions that you can include, see [Roles and permissions in UAP rules](https://docs.cloud.google.com/iam/docs/unified-access-policies#rules-roles-permissions) .
        - For rules with the **Deny** effect, specify the permissions that you want to include in or exclude from the rule. For more information about the permissions that you can include, see [Roles and permissions in UAP rules](https://docs.cloud.google.com/iam/docs/unified-access-policies#rules-roles-permissions) .

    6.  Optional: Add conditions under which the rule applies. To learn more about the supported condition attributes, see [Conditions in UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies#conditions) .

        > **Note** : In the Google Cloud console, you can only add conditions that use IAM-provided condition attributes. To add conditions that use other services' attributes, use the REST API or the gcloud CLI.

    7.  When you're done editing the rule, click **Done** .

7.  To add another rule, click **Add rule** , and then add the rule details.

8.  When you're done adding rules, click **Create policy** .

### gcloud

The [`gcloud iam access-policies create`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/create) command creates a UAP.

Before using any of the command data below, make the following replacements:

- `UAP_ID` : A unique ID for the UAP—for example, `example-policy` .

- `UAP_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) where you want to create the UAP. Use the value `project` , `folder` , or `organization` .

- `UAP_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization where you want to create the UAP. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

- `DISPLAY_NAME` : Optional. A human-readable description of the UAP—for example, `Example policy` . The display name can be a maximum of 63 characters.

- `FILE_PATH` : The path to a JSON file containing the UAP rule details. Each rule should have the following format:

  ```
  {
    "description": "DESCRIPTION",
    "effect": "EFFECT",
    "principals": [
      INCLUDED_PRINCIPALS
    ],
    "excludedPrincipals": [
      EXCLUDED_PRINCIPALS
    ],
    "operation": {
      "permissions": [
        INCLUDED_PERMISSIONS
      ],
      "excludedPermissions": [
        EXCLUDED_PERMISSIONS
      ]
    },
    CONDITIONS
  }
  ```

  Replace the following values:

  - `DESCRIPTION` : A human-readable description for the rule.

  - `EFFECT` : How the rule affects access. The supported values are `ALLOW` and `DENY` :

    - `ALLOW` : Grant the specified permissions to the specified principals.
    - `DENY` : Prevent the specified principals from using the specified permissions.

  - Replace the following values to specify the principals included in the rule:

    - `INCLUDED_PRINCIPALS` : The principals to include in the rule.
    - `EXCLUDED_PRINCIPALS` : Optional. The principals to exclude from the rule, even if they're in the list of included principals. For example, you can add a Google group to the list of included principals, and then exclude specific users who belong to that group.

    For a list of supported principal identifiers, see [Principal types for UAPs](https://docs.cloud.google.com/iam/docs/principal-identifiers#access-policies) .

  - Replace the following values to specify the permissions to include in the rule:

    - `INCLUDED_PERMISSIONS` : The permissions to include in the rule.
    - `EXCLUDED_PERMISSIONS` : Optional. The permissions to exclude from the rule, even if they're in the list of included permissions. For example, you could add a role to the list of included permissions, and then exclude specific permissions in that role.

    When creating these lists of permissions, you can reference permission names, role names, and permission groups. To learn more, see [Roles and permissions in UAP rules](https://docs.cloud.google.com/iam/docs/unified-access-policies#rules-roles-permissions) .

  - `CONDITIONS` : Optional. The conditions under which the rule applies. Use the following format:

    ```
    "conditions": {
      "SERVICE": {
        "title": "CONDITION_TITLE",
        "description": "CONDITION_DESCRIPTION",
        "expression": "CONDITION_EXPRESSION"
      }
    }
    ```

    Replace the following values:

    - `SERVICE` : The service that provides the attributes used in the condition expression.
    - `CONDITION_TITLE` : Optional. A brief summary of the purpose of the condition.
    - `CONDITION_DESCRIPTION` : Optional. A longer description of the condition.
    - `CONDITION_EXPRESSION` : A boolean expression referencing attributes of the access attempt, such as the tags attached to the resource in the access attempt. If the expression evaluates to `true` , then the rule applies for the access attempt. If it evaluates to `false` , then the rule doesn't apply for the access attempt.

    For a list of supported attributes and their services, see [Supported condition attributes](https://docs.cloud.google.com/iam/docs/unified-access-policies#supported-attributes) .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam access-policies create UAP_ID \
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID \
    --location=global --display-name=DISPLAY_NAME \
    --details-rules=FILE_PATH
```

#### Windows (PowerShell)

```
gcloud iam access-policies create UAP_ID `
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID `
    --location=global --display-name=DISPLAY_NAME `
    --details-rules=FILE_PATH
```

#### Windows (cmd.exe)

```
gcloud iam access-policies create UAP_ID ^
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID ^
    --location=global --display-name=DISPLAY_NAME ^
    --details-rules=FILE_PATH
```

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/unified-access-policies-create-apply#check-lro) on this page.

```
Create request issued for: [example-policy]
Waiting for operation [organizations/123456789012/locations/global/operations/operation-1715373988044-6181fa136df85-3b06a30a-4816d25b] to complete...done.
Created accessPolicy [example-policy].
```

### REST

The [`accessPolicies.create`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/create) method creates a UAP.

Before using any of the request data, make the following replacements:

- `UAP_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) where you want to create the UAP. Use the value `projects` , `folders` , or `organizations` .

- `UAP_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization where you want to create the UAP. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

- `UAP_ID` : A unique ID for the UAP—for example, `example-policy` .

- `DISPLAY_NAME` : Optional. A human-readable description of the UAP—for example, `Example policy` . The display name can be a maximum of 63 characters.

- `UAP_RULES` : A list of UAP rules, which define the access to grant or deny and the principals to grant or deny access to. A UAP can have up to 100 rules. Each rule has the following format:

  ```
  {
    "description": "DESCRIPTION",
    "effect": "EFFECT",
    "principals": [
      INCLUDED_PRINCIPALS
    ],
    "excludedPrincipals": [
      EXCLUDED_PRINCIPALS
    ],
    "operation": {
      "permissions": [
        INCLUDED_PERMISSIONS
      ],
      "excludedPermissions": [
        EXCLUDED_PERMISSIONS
      ]
    },
    CONDITIONS
  }
  ```

  Replace the following values:

  - `DESCRIPTION` : A human-readable description for the rule.

  - `EFFECT` : How the rule affects access. The supported values are `ALLOW` and `DENY` :

    - `ALLOW` : Grant the specified permissions to the specified principals.
    - `DENY` : Prevent the specified principals from using the specified permissions.

  - Replace the following values to specify the principals included in the rule:

    - `INCLUDED_PRINCIPALS` : The principals to include in the rule.
    - `EXCLUDED_PRINCIPALS` : Optional. The principals to exclude from the rule, even if they're in the list of included principals. For example, you can add a Google group to the list of included principals, and then exclude specific users who belong to that group.

    For a list of supported principal identifiers, see [Principal types for UAPs](https://docs.cloud.google.com/iam/docs/principal-identifiers#access-policies) .

  - Replace the following values to specify the permissions to include in the rule:

    - `INCLUDED_PERMISSIONS` : The permissions to include in the rule.
    - `EXCLUDED_PERMISSIONS` : Optional. The permissions to exclude from the rule, even if they're in the list of included permissions. For example, you could add a role to the list of included permissions, and then exclude specific permissions in that role.

    When creating these lists of permissions, you can reference permission names, role names, and permission groups. To learn more, see [Roles and permissions in UAP rules](https://docs.cloud.google.com/iam/docs/unified-access-policies#rules-roles-permissions) .

  - `CONDITIONS` : Optional. The conditions under which the rule applies. Use the following format:

    ```
    "conditions": {
      "SERVICE": {
        "title": "CONDITION_TITLE",
        "description": "CONDITION_DESCRIPTION",
        "expression": "CONDITION_EXPRESSION"
      }
    }
    ```

    Replace the following values:

    - `SERVICE` : The service that provides the attributes used in the condition expression.
    - `CONDITION_TITLE` : Optional. A brief summary of the purpose of the condition.
    - `CONDITION_DESCRIPTION` : Optional. A longer description of the condition.
    - `CONDITION_EXPRESSION` : A boolean expression referencing attributes of the access attempt, such as the tags attached to the resource in the access attempt. If the expression evaluates to `true` , then the rule applies for the access attempt. If it evaluates to `false` , then the rule doesn't apply for the access attempt.

    For a list of supported attributes and their services, see [Supported condition attributes](https://docs.cloud.google.com/iam/docs/unified-access-policies#supported-attributes) .

HTTP method and URL:

```
POST https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies?accessPolicyId=UAP_ID
```

Request JSON body:

```
{
  "displayName": "DISPLAY_NAME",
  "details": {
    "rules": [
      UAP_RULES
    ]
  }
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
     "https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies?accessPolicyId=UAP_ID"
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
    -Uri "https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies?accessPolicyId=UAP_ID" | Select-Object -Expand Content
```

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/unified-access-policies-create-apply#check-lro) on this page.

```
{
  "name": "organizations/123456789012/locations/global/operations/operation-1715373120647-6181f6d8371d2-83309b71-2b8a7532",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v3.OperationMetadata",
    "createTime": "2026-05-10T20:32:00.898809495Z",
    "target": "organizations/123456789012/locations/global/accessPolicies/example-policy",
    "verb": "create",
    "requestedCancellation": false,
    "apiVersion": "v3"
  },
  "done": false
}
```

## Apply a Unified Access Policy to a resource

To apply a UAP to a resource, you create a binding. After you create a binding for a policy, the rules in that policy become effective for the specified resource, as well as any of that resource's [descendants](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-inheritance) .

Before you create a binding, ensure that the [`iam.managed.disableAccessPolicyBinding` organization policy constraint](https://docs.cloud.google.com/organization-policy/reference/org-policy-constraints#constraints/iam.managed.disableAccessPolicyBinding) is disabled. To learn how to enable or disable this constraint, see [Using managed constraints in an organization policy](https://docs.cloud.google.com/organization-policy/create-organization-policies#managed-constraints) .

You can apply UAPs to projects, folders, and organizations using the Google Cloud console, the gcloud CLI, or the IAM REST API. To apply UAPs to other resources, you must use the gcloud CLI or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Unified Access Policies** page.

2.  Select the project, folder, or organization that owns the UAP that you want to apply.

3.  Click the ID of the UAP that you want to apply.

4.  Select the **Bindings** tab, and then click **Add binding** .

5.  In the **Add binding** pane, edit the binding details:

    1.  In the **Binding location** menu, select the resource that you want to apply the UAP to.
    2.  Optional: In the **Binding display name** field, enter a human-readable description of the binding—for example, `Example binding` . The display name can be a maximum of 63 characters.
    3.  In the **Binding ID** field, enter a unique name for the binding—for example, `example-binding` .

6.  Click **Add binding** .

### gcloud

The [`gcloud iam policy-bindings create`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/create) command creates a binding.

Before using any of the command data below, make the following replacements:

- `BINDING_ID` : A unique name for the binding—for example, `example-binding` .

- `BINDING_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that the binding is a child of. Use the value `project` , `folder` , or `organization` .

  The binding's parent resource depends on the target resource in the binding. For more information, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) .

- `BINDING_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that the policy binding is a child of. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

- `POLICY_PARENT_RESOURCE` : The resource where the UAP was created, in the form `RESOURCE_TYPE `` / `` RESOURCE_ID` . For example, `organizations/0123456789012` . UAPs can be created in projects, folders, or organizations. Folder and organization IDs must be numeric. Project IDs can be numeric or alphanumeric.

- `UAP_ID` : The ID of the UAP that you want to bind to the resource—for example, `example-uap` . You can't change this value after you create the binding.

- `TARGET_RESOURCE` : The resource that you want to bind the UAP to. For a list of valid resources, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) . You can't change this value after you create the binding.

- `DISPLAY_NAME` : Optional. A human-readable description of the binding—for example, `Example binding` . The display name can be a maximum of 63 characters.

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam policy-bindings create BINDING_ID \
    --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID --location=global \
    --policy="POLICY_PARENT_RESOURCE/locations/global/accessPolicies/UAP_ID" \
    --target-resource=TARGET_RESOURCE \
    --display-name=DISPLAY_NAME
```

#### Windows (PowerShell)

```
gcloud iam policy-bindings create BINDING_ID `
    --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID --location=global `
    --policy="POLICY_PARENT_RESOURCE/locations/global/accessPolicies/UAP_ID" `
    --target-resource=TARGET_RESOURCE `
    --display-name=DISPLAY_NAME
```

#### Windows (cmd.exe)

```
gcloud iam policy-bindings create BINDING_ID ^
    --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID --location=global ^
    --policy="POLICY_PARENT_RESOURCE/locations/global/accessPolicies/UAP_ID" ^
    --target-resource=TARGET_RESOURCE ^
    --display-name=DISPLAY_NAME
```

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/unified-access-policies-create-apply#check-lro) on this page.

```
Create request issued for: [example-binding]
Waiting for operation [organizations/123456789012/locations/global/operations/operation-1715374545618-6181fc272c6f9-55ff07f4-97d0ac76] to complete...done.
Created policyBinding [example-binding].
```

### REST

The [`policyBindings.create`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings/create) method creates a binding.

Before using any of the request data, make the following replacements:

- `BINDING_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that the binding is a child of. Use the value `projects` , `folders` , or `organizations` .

  The binding's parent resource depends on the target resource in the binding. For more information, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) .

- `BINDING_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that the policy binding is a child of. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

- `BINDING_ID` : A unique name for the binding—for example, `example-binding` .

- `DISPLAY_NAME` : Optional. A human-readable description of the binding—for example, `Example binding` . The display name can be a maximum of 63 characters.

- `TARGET_RESOURCE` : The resource that you want to bind the UAP to. For a list of valid resources, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) . You can't change this value after you create the binding.

- `POLICY_PARENT_RESOURCE` : The resource where the UAP was created, in the form `RESOURCE_TYPE `` / `` RESOURCE_ID` . For example, `organizations/0123456789012` . UAPs can be created in projects, folders, or organizations. Folder and organization IDs must be numeric. Project IDs can be numeric or alphanumeric.

- `UAP_ID` : The ID of the UAP that you want to bind to the resource—for example, `example-uap` . You can't change this value after you create the binding.

HTTP method and URL:

```
POST https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings?policyBindingId=BINDING_ID
```

Request JSON body:

```
{
  "displayName": "DISPLAY_NAME",
  "target": {
    "resource": "TARGET_RESOURCE"
  },
  "policyKind": "ACCESS",
  "policy": "POLICY_PARENT_RESOURCE/locations/global/accessPolicies/UAP_ID"
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
     "https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings?policyBindingId=BINDING_ID"
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
    -Uri "https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings?policyBindingId=BINDING_ID" | Select-Object -Expand Content
```

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/unified-access-policies-create-apply#check-lro) on this page.

```
{
  "name": "organizations/123456789012/locations/global/operations/operation-1715373120647-6181f6d8371d2-83309b71-2b8a7532",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v3.OperationMetadata",
    "createTime": "2026-05-10T20:32:00.898809495Z",
    "target": "organizations/123456789012/locations/global/policyBindings/example-binding",
    "verb": "create",
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

- [View UAPs and bindings](https://docs.cloud.google.com/iam/docs/unified-access-policies-view)
- [Edit UAPs and bindings](https://docs.cloud.google.com/iam/docs/unified-access-policies-edit)
- [Remove UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies-remove)
