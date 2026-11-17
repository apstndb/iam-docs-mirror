---
name: documents/docs.cloud.google.com/iam/docs/deny-access-change-permissions
uri: https://docs.cloud.google.com/iam/docs/deny-access-change-permissions
title: Prevent users from granting access
description: Learn how to identify and deny the permissions that let users grant access to {{dynamic_data.site_values.cloud_name_short}} resources.
data_source: docs.cloud.google.com
---

Denying permissions that let users grant access helps you prevent unauthorized privilege escalation and tighten your security controls. This document describes how to identify these permissions and create a deny policy that blocks them for most users while allowing exceptions for trusted principals.

## Before you begin

- Enable the IAM API, if it is not already enabled.

  **Roles required to enable APIs**

  To enable APIs, you need the `serviceusage.services.enable` permission. If you created the project, then you likely already have this permission through the Owner role ( `roles/owner` ). Otherwise, you can get this permission through the Service Usage Admin role ( `roles/serviceusage.serviceUsageAdmin` ). [Learn how to grant roles](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

- Set up authentication.

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

- Optional: Read the [overview of deny policies](https://docs.cloud.google.com/iam/docs/deny-overview) .

### Required roles

To get the permission that you need to create a deny policy, ask your administrator to grant you the [Deny Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin) ( `roles/iam.denyAdmin` ) IAM role on your organization. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

This predefined role contains the `iam.denypolicies.create` permission, which is required to create a deny policy.

You might also be able to get this permission with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

## Identify permissions that let users grant access

Before you create a deny policy to prevent users from granting access, determine which permissions you want to deny.

The following permissions let users grant access:

- Permissions ending in `setIamPolicy` . The most broadly permissive of these permissions are those for Resource Manager resources because allow policies for those resources are inherited by all descendant resources. These permissions are as follows:

  - `cloudresourcemanager.googleapis.com/projects.setIamPolicy`
  - `cloudresourcemanager.googleapis.com/folders.setIamPolicy`
  - `cloudresourcemanager.googleapis.com/organizations.setIamPolicy`

  Other resources also have `setIamPolicy` permissions—for example, Compute Engine instances have the permission `compute.googleapis.com/instances.setIamPolicy` . To prevent users from modifying allow policies for these resources, add these permissions to your deny policy.

  For a full list of deniable permissions ending in `setIamPolicy` , go to [Permissions supported in deny policies](https://docs.cloud.google.com/iam/docs/deny-permissions-support) and search for `setIamPolicy` .

- The `iam.googleapis.com/roles.update` permission, which lets users modify [custom roles](https://docs.cloud.google.com/iam/docs/roles-overview#custom) . Users with this permission can add permissions to custom roles, effectively granting themselves or others those permissions.

<!-- -->

- Permissions to modify [Unified Access Policies (UAPs)](https://docs.cloud.google.com/iam/docs/unified-access-policies) and bind them to resources. These permissions are as follows:

  - The `iam.googleapis.com/accesspolicies.update` permission, which lets users update existing UAPs.
  - Permissions ending in `createPolicyBinding` . These permissions exist for every [resource that you can bind UAPs to](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) . For projects, folders, and organizations, these permissions are as follows:
    - `cloudresourcemanager.googleapis.com/projects.createPolicyBinding`
    - `cloudresourcemanager.googleapis.com/folders.createPolicyBinding`
    - `cloudresourcemanager.googleapis.com/organizations.createPolicyBinding`

  Alternatively, you can prevent all users from binding UAPs to resources by enforcing the [`iam.managed.disableAccessPolicyBinding` organization policy constraint](https://docs.cloud.google.com/organization-policy/reference/org-policy-constraints#constraints/iam.managed.disableAccessPolicyBinding) in your organization. However, this organization policy doesn't prevent users from modifying existing UAPs that are already bound to resources.

## Deny access change permissions

After you determine which permissions you want to deny, create a deny policy for your organization that denies these permissions.

### Console

1.  In the Google Cloud console, go to the **Deny** tab on the **IAM** page.

2.  Select your organization.

3.  Click **Create deny policy** .

4.  In the **Policy name** section, define the policy ID by doing one of the following:

    - In the **Display name** field, enter a display name for the policy. Filling out this field automatically fills out the **ID** field. If you want to change the ID of the policy, update the text in the **ID** field.
    - In the **ID** field, enter an ID for the policy.

5.  In the **Deny rules** section, add a deny rule that blocks access change permissions:

    1.  In the **Denied principals** field, add the principals to deny access to. To deny access change permissions to all users, use the value `principalSet://goog/public:all` . For a full list of values that you can use, see [Principal identifiers for deny policies](https://docs.cloud.google.com/iam/docs/principal-identifiers#deny) .

    2.  In the **Exception principals** field, add the trusted principals that you want to let grant access. For a full list of values that you can use, see [Principal identifiers for deny policies](https://docs.cloud.google.com/iam/docs/principal-identifiers#deny) .

        > **Note** : If a principal set in the list of denied principals includes [service agents](https://docs.cloud.google.com/iam/docs/service-account-types#service-agents) —for example, the principal set `principalSet://goog/public:all` —then we recommend adding your service agents as exceptions in the deny rule. This helps ensure that your services continue to function properly. When adding service agents as exceptions, use the project, folder, or organization's [service agent principal set](https://docs.cloud.google.com/iam/docs/principal-identifiers#deny-service-agent-principal-sets) .

    3.  In the **Denied permissions** section, add the permissions that you identified in [Identify permissions that let users grant access](https://docs.cloud.google.com/iam/docs/deny-access-change-permissions#identify-permissions) .

    4.  Optional: Add a denial condition that specifies which resources are affected by this rule. For example, you can add a condition to ensure that the policy applies only for resources with the `prod` tag value. For more information about denial conditions, see [Conditions in deny policies](https://docs.cloud.google.com/iam/docs/conditions-overview#deny) .

6.  Click **Create** .

### gcloud

The [`gcloud iam policies create`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policies/create) command creates a deny policy for a resource.

Before using any of the command data below, make the following replacements:

- `POLICY_ID` : An identifier for the deny policy.

- `ORG_ID` : The numeric ID of the organization where you want to create the deny policy.

- `POLICY_FILE` : A file that contains the deny policy that you want to set. Use the following format for the deny policy:

  ```
  {
    "displayName": "POLICY_NAME",
    "rules": [
      {
        "denyRule": {
          "deniedPrincipals": [
            DENIED_PRINCIPALS
          ],
          "exceptionPrincipals": [
            EXCEPTION_PRINCIPALS
          ],
          "deniedPermissions": [
            ACCESS_CHANGE_PERMISSIONS
          ],
          DENIAL_CONDITION
        }
      }
    ]
  }
  ```

  Replace the following values:

  - `POLICY_NAME` : The display name for the deny policy.

  - `DENIED_PRINCIPALS` : The principals to deny access to. To deny access change permissions to all users, use the value `"principalSet://goog/public:all"` . For a full list of values that you can use, see [Principal identifiers for deny policies](https://docs.cloud.google.com/iam/docs/principal-identifiers#deny) .

  - `EXCEPTION_PRINCIPALS` : The trusted principals that you want to let grant access. For a full list of values that you can use, see [Principal identifiers for deny policies](https://docs.cloud.google.com/iam/docs/principal-identifiers#deny) .

    > **Note** : If a principal set in the list of denied principals includes [service agents](https://docs.cloud.google.com/iam/docs/service-account-types#service-agents) —for example, the principal set `principalSet://goog/public:all` —then we recommend adding your service agents as exceptions in the deny rule. This helps ensure that your services continue to function properly. When adding service agents as exceptions, use the project, folder, or organization's [service agent principal set](https://docs.cloud.google.com/iam/docs/principal-identifiers#deny-service-agent-principal-sets) .

  - `ACCESS_CHANGE_PERMISSIONS` : The permissions that you identified in [Identify permissions that let users grant access](https://docs.cloud.google.com/iam/docs/deny-access-change-permissions#identify-permissions) .

  - `DENIAL_CONDITION` : Optional. A denial condition that specifies which resources are affected by this rule. For example, you can add a condition to ensure that the rule applies only for resources with the `prod` tag value. For more information about denial conditions, see [Conditions in deny policies](https://docs.cloud.google.com/iam/docs/conditions-overview#deny) .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam policies create POLICY_ID \
    --attachment-point=cloudresourcemanager.googleapis.com/organizations/ORG_ID \
    --kind=denypolicies \
    --policy-file=POLICY_FILE
```

#### Windows (PowerShell)

```
gcloud iam policies create POLICY_ID `
    --attachment-point=cloudresourcemanager.googleapis.com/organizations/ORG_ID `
    --kind=denypolicies `
    --policy-file=POLICY_FILE
```

#### Windows (cmd.exe)

```
gcloud iam policies create POLICY_ID ^
    --attachment-point=cloudresourcemanager.googleapis.com/organizations/ORG_ID ^
    --kind=denypolicies ^
    --policy-file=POLICY_FILE
```

If successful, this command returns no output. To print a detailed response, use the `--format=json` flag.

### REST

The [`policies.createPolicy`](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/createPolicy) method creates a deny policy for a resource.

Before using any of the request data, make the following replacements:

- `ORG_ID` : The numeric ID of the organization where you want to create the deny policy.

- `POLICY_ID` : An identifier for the deny policy.

- `POLICY_NAME` : The display name for the deny policy.

- `DENIED_PRINCIPALS` : The principals to deny access to. To deny access change permissions to all users, use the value `"principalSet://goog/public:all"` . For a full list of values that you can use, see [Principal identifiers for deny policies](https://docs.cloud.google.com/iam/docs/principal-identifiers#deny) .

- `EXCEPTION_PRINCIPALS` : The trusted principals that you want to let grant access. For a full list of values that you can use, see [Principal identifiers for deny policies](https://docs.cloud.google.com/iam/docs/principal-identifiers#deny) .

  > **Note** : If a principal set in the list of denied principals includes [service agents](https://docs.cloud.google.com/iam/docs/service-account-types#service-agents) —for example, the principal set `principalSet://goog/public:all` —then we recommend adding your service agents as exceptions in the deny rule. This helps ensure that your services continue to function properly. When adding service agents as exceptions, use the project, folder, or organization's [service agent principal set](https://docs.cloud.google.com/iam/docs/principal-identifiers#deny-service-agent-principal-sets) .

- `ACCESS_CHANGE_PERMISSIONS` : The permissions that you identified in [Identify permissions that let users grant access](https://docs.cloud.google.com/iam/docs/deny-access-change-permissions#identify-permissions) .

- `DENIAL_CONDITION` : Optional. A denial condition that specifies which resources are affected by this rule. For example, you can add a condition to ensure that the rule applies only for resources with the `prod` tag value. For more information about denial conditions, see [Conditions in deny policies](https://docs.cloud.google.com/iam/docs/conditions-overview#deny) .

HTTP method and URL:

```
POST https://iam.googleapis.com/v2/policies/cloudresourcemanager.googleapis.com%2Forganizations%2FORG_ID/denypolicies?policyId=POLICY_ID
```

Request JSON body:

```
{
  "displayName": "POLICY_NAME",
  "rules": [
    {
      "denyRule": {
        "deniedPrincipals": [
          DENIED_PRINCIPALS
        ],
        "exceptionPrincipals": [
          EXCEPTION_PRINCIPALS
        ],
        "deniedPermissions": [
          ACCESS_CHANGE_PERMISSIONS
        ],
        DENIAL_CONDITION
      }
    }
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
     "https://iam.googleapis.com/v2/policies/cloudresourcemanager.googleapis.com%2Forganizations%2FORG_ID/denypolicies?policyId=POLICY_ID"
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
    -Uri "https://iam.googleapis.com/v2/policies/cloudresourcemanager.googleapis.com%2Forganizations%2FORG_ID/denypolicies?policyId=POLICY_ID" | Select-Object -Expand Content
```

#### APIs Explorer (browser)

Copy the request body and open the [method reference page](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/createPolicy) . The APIs Explorer panel opens on the right side of the page. You can interact with this tool to send requests. Paste the request body in this tool, complete any other required fields, and click **Execute** .

You should receive a JSON response similar to the following:

```
{
  "name": "policies/cloudresourcemanager.googleapis.com%2Forganizations%2F1234567890123/denypolicies/deny-access-granting/operations/89cb3e508bf1ff01",
  "metadata": {
    "@type": "type.googleapis.com/google.iam.v2.PolicyOperationMetadata",
    "createTime": "2026-10-31T19:06:12.455151Z"
  },
  "response": {
    "@type": "type.googleapis.com/google.iam.v2.Policy",
    "name": "policies/cloudresourcemanager.googleapis.com%2Forganizations%2F1234567890123/denypolicies/deny-access-granting",
    "uid": "6665c437-a3b2-a018-6934-54dd16d3426e",
    "kind": "DenyPolicy",
    "displayName": "Deny access change permissions.",
    "etag": "MTc3NDU4KjM4OZ0MzU5MjQ5OTI=",
    "createTime": "2026-10-31T19:06:12.455151Z",
    "updateTime": "2026-10-31T22:26:21.968687Z",
    "rules": [
      {
        "denyRule": {
          "deniedPrincipals": [
            "principalSet://goog/public:all"
          ],
          "exceptionPrincipals": [
            "principalSet://cloudresourcemanager.googleapis.com/organizations/1234567890123/type/ServiceAgent",
            "principalSet://goog/group/iam-admins@example.com"
          ],
          "deniedPermissions": [
            
            "cloudresourcemanager.googleapis.com/projects.setIamPolicy",
            "cloudresourcemanager.googleapis.com/folders.setIamPolicy",
            "cloudresourcemanager.googleapis.com/organizations.setIamPolicy",
            "iam.googleapis.com/accesspolicies.update",
            "cloudresourcemanager.googleapis.com/projects.createPolicyBinding",
            "cloudresourcemanager.googleapis.com/folders.createPolicyBinding",
            "cloudresourcemanager.googleapis.com/organizations.createPolicyBinding"
            
          ],
          "denialCondition": {
            "title": "Only for prod resources",
            "expression": "resource.matchTag('12345678/env', 'prod')"
          }
        }
      }
    ]
  }
}
```

The response identifies a long-running operation. You can monitor the status of the long-running operation to find out when it's complete. For details, see [Check the status of a long-running operation](https://docs.cloud.google.com/iam/docs/deny-access#check-operation-status) .

## What's next

- Find out how to [troubleshoot access issues with deny policies](https://docs.cloud.google.com/iam/docs/troubleshoot-policies) .
- Learn more about [denying access to principals](https://docs.cloud.google.com/iam/docs/deny-overview) .
