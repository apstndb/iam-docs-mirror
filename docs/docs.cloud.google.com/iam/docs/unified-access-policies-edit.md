---
name: documents/docs.cloud.google.com/iam/docs/unified-access-policies-edit
uri: https://docs.cloud.google.com/iam/docs/unified-access-policies-edit
title: Edit Unified Access Policies
description: How to edit Unified Access Policies and bindings
data_source: docs.cloud.google.com
---

> **Preview**
>
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

Unified Access Policies (UAPs) let you grant and deny principals access to Google Cloud resources. This document explains how to edit existing UAPs and modify which resources a UAP applies to.

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

3.  Optional. Read the [overview of UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies) .

### Required roles

To get the permissions that you need to edit UAPs, ask your administrator to grant you the [Access Policy Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyAdmin) ( `roles/iam.accessPolicyAdmin` ) IAM role on the project, folder, or organization that owns the UAP that you want to edit . For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

This predefined role contains the permissions required to edit UAPs. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to edit UAPs:

- `iam.accesspolicies.update`
- Edit UAPs in the Google Cloud console:
  - `iam.accesspolicies.get`
  - `iam.accessPolicies.list`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Edit an existing Unified Access Policy

You can edit a UAP to update its display name or its rules.

> **Note:** Modifying a UAP affects access for all resources that the UAP is bound to.

You can edit a UAP using the Google Cloud console, the gcloud CLI, or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Unified Access Policies** page.

2.  Select the project, folder, or organization that owns the UAP that you want to edit.

3.  Click the policy ID of the UAP that you want to edit.

4.  To add rules, click **Add rule** and then add the details of the rule. To save the rule, click **Add rule** .

    To learn more about the fields of a rule, see [Create a UAP](https://docs.cloud.google.com/iam/docs/unified-access-policies-create-apply#create-uap) .

5.  To edit other fields of the UAP, click **Edit policy** .

6.  Edit any of the following fields:

    - **Policy name** : Enter a new display name for the UAP.
    - **Rules** : Update, add, or remove rules in the UAP.

7.  When you're done editing the UAP, click **Update policy** .

### gcloud

The [`gcloud iam access-policies update`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/update) command updates an existing UAP.

Before using any of the command data below, make the following replacements:

- `UAP_ID` : The ID of the UAP that you want to update—for example, `example-policy` .

- `UAP_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that owns the UAP that you want to update. Use the value `project` , `folder` , or `organization` .

- `UAP_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that owns the UAP that you want to update. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

- `FIELD_TO_UPDATE `` = `` UPDATED_VALUE` : The fields that you want to update and the corresponding updated value.

  The following are examples of flags that you can use to update the fields in the policy:

  - `--display-name= `` DISPLAY_NAME` : Replace the display name of the UAP with the specified name.

  - `--details-rules= `` RULES_FILE` : Replace the UAP rules with the rules in the specified file. Each rule in the file should have the following format:

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

  - `--add-details-rules= `` RULES_FILE` : Append the rules in the specified file to the existing rules in the UAP.

  - `--remove-details-rules= `` RULES_FILE` : Remove the rules in the specified file from the existing rules in the UAP. Only rules that exactly match one of the rules in the specified file are removed.

  - `--clear-details-rules` : Clear all rules from the UAP.

  For a full list of flags that you can use to update a UAP, see the [`gcloud iam access-policies update` command reference](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/update) . Some flags are mutually exclusive.

- `FORMAT` : The format for the response. Use `json` or `yaml` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam access-policies update UAP_ID \
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID \
    --location=global --FIELD_TO_UPDATE=UPDATED_VALUE \
    --format=FORMAT
```

#### Windows (PowerShell)

```
gcloud iam access-policies update UAP_ID `
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID `
    --location=global --FIELD_TO_UPDATE=UPDATED_VALUE `
    --format=FORMAT
```

#### Windows (cmd.exe)

```
gcloud iam access-policies update UAP_ID ^
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID ^
    --location=global --FIELD_TO_UPDATE=UPDATED_VALUE ^
    --format=FORMAT
```

The response contains a long-running operation representing your request. After the operation is complete, the response prints the updated UAP.

```
Request issued for: [example-policy]
Waiting for operation [organizations/123456789012/locations/global/operations/operation-1715374208720-6181fae5e2034-2d8a712b-5c92e5b9] to complete...done.
Updated accessPolicy [example-policy].
{
  "createTime": "2026-08-31T21:43:39.822441Z",
  "details": {
    "rules": [
      {
        "conditions": {
          "iam.googleapis.com": {
            "expression": "resource.matchTag('environment', 'prod')"
          }
        },
        "description": "Grant non-delete compute permissions to compute admins in prod",
        "effect": "ALLOW",
        "excludedPrincipals": [
          "principal://goog/subject/access-restricted@example.com"
        ],
        "operation": {
          "excludedPermissions": [
            "*/*.delete"
          ],
          "permissions": [
            "role:roles/compute.admin"
          ]
        },
        "principals": [
          "principalSet://goog/group/compute-admins@example.com"
        ]
      }
    ]
  },
  "displayName": "Updated display name",
  "etag": "W/\"YZtdQgtulCVzvTwlBTFjPQ==\"",
  "name": "projects/0123456789012/locations/global/accessPolicies/example-policy",
  "uid": "puid_0123456789012345678",
  "updateTime": "2026-08-31T21:43:39.822441Z"
}
```

### REST

The [`accessPolicies.patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/patch) method updates an existing UAP.

Before using any of the request data, make the following replacements:

- `UAP_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that owns the UAP that you want to update. Use the value `projects` , `folders` , or `organizations` .

- `UAP_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that owns the UAP that you want to update. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

- `UAP_ID` : The ID of the UAP that you want to update—for example, `example-policy` .

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
PATCH https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies/UAP_ID
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
curl -X PATCH \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     -H "Content-Type: application/json; charset=utf-8" \
     -d @request.json \
     "https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies/UAP_ID"
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
    -Uri "https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies/UAP_ID" | Select-Object -Expand Content
```

The response contains a long-running operation representing your request. To learn how to get the status of a long-running operation, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/unified-access-policies-edit#check-lro) on this page.

```
{
  "name": "organizations/123456789012/locations/global/operations/operation-1715626721931-6185a7953ef76-76f80ee4-19cd1bf7",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v3.OperationMetadata",
    "createTime": "2026-05-13T18:58:43.721277235Z",
    "target": "organizations/123456789012/locations/global/accessPolicies/example-policy",
    "verb": "update",
    "requestedCancellation": false,
    "apiVersion": "v3"
  },
  "done": false
}
```

## Change which resources the policy applies to

After you create a binding for a UAP, you can't change the policy ID or the resource in the binding. As a result, if you want to change which resource a UAP applies to, you must do one of the following:

- To apply the UAP to another resource, [create a new binding](https://docs.cloud.google.com/iam/docs/unified-access-policies-create-apply#create-binding) that binds the UAP to that resource.
- To remove a UAP from a resource, [delete the binding](https://docs.cloud.google.com/iam/docs/unified-access-policies-remove#delete-binding) that binds the UAP to the resource.

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
- [Remove UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies-remove)
