---
name: documents/docs.cloud.google.com/iam/docs/unified-access-policies-view
uri: https://docs.cloud.google.com/iam/docs/unified-access-policies-view
title: View Unified Access Policies
description: How to get and list existing Unified Access Policies and bindings
data_source: docs.cloud.google.com
---

> **Preview**
>
> This feature is subject to the "Pre-GA Offerings Terms" in the General Service Terms section of the [Service Specific Terms](https://docs.cloud.google.com/terms/service-terms#1) . Pre-GA features are available "as is" and might have limited support. For more information, see the [launch stage descriptions](https://cloud.google.com/products/#product-launch-stages) .

Unified Access Policies (UAPs) let you grant and deny principals access to Google Cloud resources. This document explains how to view UAPs and bindings.

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

### Roles required to view Unified Access Policies

To get the permissions that you need to view UAPs, ask your administrator to grant you the [Access Policy Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyViewer) ( `roles/iam.accessPolicyViewer` ) IAM role on the project, folder, or organization that owns the UAP that you want to view . For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

This predefined role contains the permissions required to view UAPs. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to view UAPs:

- `iam.accesspolicies.get`
- `iam.accessPolicies.list`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

### Roles required to view Unified Access Policy bindings

To get the permissions that you need to view bindings, ask your administrator to grant you the following IAM roles on the bindings' [parent resource](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) :

- View bindings in a project: [Project IAM Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin) ( `roles/resourcemanager.projectIamAdmin` )
- View bindings in a folder: [Folder IAM Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin) ( `roles/resourcemanager.folderIamAdmin` )
- View bindings in an organization: [Organization Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin) ( `roles/resourcemanager.organizationAdmin` )

For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

These predefined roles contain the permissions required to view bindings. To see the exact permissions that are required, expand the **Required permissions** section:

#### Required permissions

The following permissions are required to view bindings:

- View a single binding: `iam.policybindings.get`
- List bindings parented by a project, folder, or organization: `iam.policybindings.list`

You might also be able to get these permissions with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

### Roles required to view all bindings for a Unified Access Policy

To get the permission that you need to view all bindings for a UAP, ask your administrator to grant you the [Access Policy Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.accessPolicyViewer) ( `roles/iam.accessPolicyViewer` ) IAM role on the resource that owns the UAP. For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

This predefined role contains the `iam.accesspolicies.searchPolicyBindings` permission, which is required to view all bindings for a UAP.

You might also be able to get this permission with [custom roles](https://docs.cloud.google.com/iam/docs/creating-custom-roles) or other [predefined roles](https://docs.cloud.google.com/iam/docs/roles-overview#predefined) .

### Roles to view all bindings for a resource

To get the permissions that you need to view all bindings that include a specific target resource, ask your administrator to grant you a role that lets you list bindings for that resource. This role must include the permission `SERVICE `` . `` RESOURCE `` .searchPolicyBindings` , where `RESOURCE` is the target resource type and `SERVICE` is the service that owns the resource.

To find a role that includes the required permission, search for the permission in the [role and permission reference](https://docs.cloud.google.com/iam/docs/roles-permissions) , click the permission name, and then review the roles that include the permission.

You need this role on the target resource or one of its ancestors.

For more information about granting roles, see [Manage access to projects, folders, and organizations](https://docs.cloud.google.com/iam/docs/granting-changing-revoking-access) .

## List Unified Access Policies in a project, folder, or organization

You can list all of the UAPs parented by a specific project, folder, or organization using the Google Cloud console, the gcloud CLI, or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Unified Access Policies** page.

2.  Select the project, folder, or organization that owns the UAPs that you want to view.

The Google Cloud console displays the UAPs parented by or bound to the resource that you selected.

### gcloud

The [`gcloud iam access-policies list`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/list) command lists all UAPs that are children of a certain resource.

Before using any of the command data below, make the following replacements:

- `UAP_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that owns the UAPs that you want to list. Use the value `project` , `folder` , or `organization` .
- `UAP_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that owns the UAPs that you want to list. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .
- `FORMAT` : The format for the response. Use `json` or `yaml` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam access-policies list --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID \
    --location=global --format=FORMAT
```

#### Windows (PowerShell)

```
gcloud iam access-policies list --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID `
    --location=global --format=FORMAT
```

#### Windows (cmd.exe)

```
gcloud iam access-policies list --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID ^
    --location=global --format=FORMAT
```

The response contains the UAPs that are children of the resource in the request.

```
{
  "accessPolicies": [
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
      "displayName": "Example policy 1",
      "etag": "W/\"YZtdQgtulCVzvTwlBTFjPQ==\"",
      "name": "projects/0123456789012/locations/global/accessPolicies/example-policy",
      "uid": "puid_0123456789012345678",
      "updateTime": "2026-08-31T21:43:39.822441Z"
    },
    {
      "createTime": "2026-05-29T23:25:01.606730Z",
      "details": {
        "rules": [
          {
            "description": "Deny group from publishing to message buses",
            "effect": "DENY",
            "operation": {
              "permissions": [
                "eventarc.googleapis.com/messageBuses.publish"
              ]
            },
            "principals": [
              "principalSet://goog/group/example-group@example.com"
            ]
          }
        ]
      },
      "displayName": "Example policy 2",
      "etag": "d6BJBTsk2+oDCygmr5ANxA==",
      "name": "organizations/123456789012/locations/global/accessPolicies/example-policy-2",
      "uid": "puid_13064942519001808897",
      "updateTime": "2026-05-29T23:25:01.606730Z"
    }
  ]
}
```

### REST

The [`accessPolicies.list`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/list) method lists all UAPs that are children of a certain resource.

Before using any of the request data, make the following replacements:

- `UAP_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that owns the UAPs that you want to list. Use the value `projects` , `folders` , or `organizations` .
- `UAP_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that owns the UAPs that you want to list. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

HTTP method and URL:

```
GET https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X GET \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies"
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
    -Uri "https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies" | Select-Object -Expand Content
```

The response contains the UAPs that are children of the resource in the request.

```
{
  "accessPolicies": [
    {
      "name": "projects/0123456789012/locations/global/accessPolicies/example-policy",
      "uid": "puid_0123456789012345678",
      "etag": "W/\"YZtdQgtulCVzvTwlBTFjPQ==\"",
      "displayName": "Example policy",
      "createTime": "2026-08-31T21:43:39.822441Z",
      "updateTime": "2026-08-31T21:43:39.822441Z",
      "details": {
        "rules": [
          {
            "principals": [
              "principalSet://goog/group/compute-admins@example.com"
            ],
            "excludedPrincipals": [
              "principal://goog/subject/access-restricted@example.com"
            ],
            "operation": {
              "permissions": [
                "role:roles/compute.admin"
              ],
              "excludedPermissions": [
                "*/*.delete"
              ]
            },
            "conditions": {
              "iam.googleapis.com": {
                "expression": "resource.matchTag('environment', 'prod')"
              }
            },
            "description": "Grant non-delete compute permissions to compute admins in prod",
            "effect": "ALLOW"
          }
        ]
      }
    },
    {
      "name": "organizations/123456789012/locations/global/accessPolicies/example-policy-2",
      "uid": "puid_13064942519001808897",
      "etag": "d6BJBTsk2+oDCygmr5ANxA==",
      "displayName": "Example policy 2",
      "createTime": "2026-05-29T23:25:01.606730Z",
      "updateTime": "2026-05-29T23:25:01.606730Z",
      "details": {
        "rules": [
          {
            "description": "Deny group from publishing to message buses",
            "principals": [
              "principalSet://goog/group/example-group@example.com"
            ],
            "operation": {
              "permissions": [
                "eventarc.googleapis.com/messageBuses.publish"
              ]
            },
            "effect": "DENY"
          }
        ]
      }
    }
  ]
}
```

## Get a single Unified Access Policy

You can get the details of a single UAP using the Google Cloud console, the gcloud CLI, or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Unified Access Policies** page.

2.  Select the project, folder, or organization that owns the UAP whose details you want to view.

3.  Click the policy ID of the UAP whose details you want to view.

The Google Cloud console displays the details of the UAP, including the ID, create time, last updated time, and list of rules.

### gcloud

The [`gcloud iam access-policies describe`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/describe) command gets a single UAP.

Before using any of the command data below, make the following replacements:

- `UAP_ID` : The ID of the UAP that you want to get—for example, `example-policy` .
- `UAP_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that owns the UAP that you want to get. Use the value `project` , `folder` , or `organization`
- `UAP_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that owns the UAP that you want to get. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .
- `FORMAT` : The format for the response. Use `json` or `yaml` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam access-policies describe UAP_ID \
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID \
    --location=global --format=FORMAT
```

#### Windows (PowerShell)

```
gcloud iam access-policies describe UAP_ID `
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID `
    --location=global --format=FORMAT
```

#### Windows (cmd.exe)

```
gcloud iam access-policies describe UAP_ID ^
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID ^
    --location=global --format=FORMAT
```

The response contains the UAP specified in the request.

```
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
  "displayName": "Example policy",
  "etag": "W/\"YZtdQgtulCVzvTwlBTFjPQ==\"",
  "name": "projects/0123456789012/locations/global/accessPolicies/example-policy",
  "uid": "puid_0123456789012345678",
  "updateTime": "2026-08-31T21:43:39.822441Z"
}
```

### REST

The [`accessPolicies.get`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/get) method gets a single UAP.

Before using any of the request data, make the following replacements:

- `UAP_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that owns the UAP that you want to get. Use the value `projects` , `folders` , or `organizations`
- `UAP_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that owns the UAP that you want to get. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .
- `UAP_ID` : The ID of the UAP that you want to get—for example, `example-policy` .

HTTP method and URL:

```
GET https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies/UAP_ID
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X GET \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies/UAP_ID"
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
    -Uri "https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies/UAP_ID" | Select-Object -Expand Content
```

The response contains the UAP specified in the request.

```
{
  "name": "projects/0123456789012/locations/global/accessPolicies/example-policy",
  "uid": "puid_0123456789012345678",
  "etag": "W/\"YZtdQgtulCVzvTwlBTFjPQ==\"",
  "displayName": "Example policy",
  "createTime": "2026-08-31T21:43:39.822441Z",
  "updateTime": "2026-08-31T21:43:39.822441Z",
  "details": {
    "rules": [
      {
        "principals": [
          "principalSet://goog/group/compute-admins@example.com"
        ],
        "excludedPrincipals": [
          "principal://goog/subject/access-restricted@example.com"
        ],
        "operation": {
          "permissions": [
            "role:roles/compute.admin"
          ],
          "excludedPermissions": [
            "*/*.delete"
          ]
        },
        "conditions": {
          "iam.googleapis.com": {
            "expression": "resource.matchTag('environment', 'prod')"
          }
        },
        "description": "Grant non-delete compute permissions to compute admins in prod",
        "effect": "ALLOW"
      }
    ]
  }
}
```

## List bindings for Unified Access Policies

You can list bindings for UAPs in several ways:

- [List bindings for a UAP](https://docs.cloud.google.com/iam/docs/unified-access-policies-view#search-policy-bindings) : View all bindings that include a specific UAP.
- [List bindings for a resource](https://docs.cloud.google.com/iam/docs/unified-access-policies-view#search-target-bindings) : View all bindings that include a specific target resource.
- [List all bindings in a project, folder, or organization](https://docs.cloud.google.com/iam/docs/unified-access-policies-view#list-policy-bindings-parent) : View all bindings that are parented by a specific project, folder, or organization.

### List bindings for a Unified Access Policy

To view all bindings that include a certain UAP, search the bindings for the UAP.

You can view all bindings for a UAP using the Google Cloud console, the gcloud CLI, or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Unified Access Policies** page.

2.  Select the project, folder, or organization that owns the UAP whose bindings you want to view.

3.  Click the policy ID of the UAP whose bindings you want to view.

4.  Select the **Bindings** tab.

The Google Cloud console displays a list of the bindings for the UAP, along with each binding's display name and target resource.

### gcloud

The [`gcloud iam access-policies search-policy-bindings`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/access-policies/search-policy-bindings) command lists all bindings for the specified UAP.

Before using any of the command data below, make the following replacements:

- `UAP_ID` : The ID of the UAP that you want to list bindings for—for example, `example-policy` .
- `UAP_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that owns the UAP that you want to list bindings for. Use the value `project` , `folder` , or `organization` .
- `UAP_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that owns the UAP that you want to list bindings for. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .
- `FORMAT` : The format for the response. Use `json` or `yaml` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam access-policies search-policy-bindings UAP_ID \
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID \
    --location=global --format=FORMAT
```

#### Windows (PowerShell)

```
gcloud iam access-policies search-policy-bindings UAP_ID `
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID `
    --location=global --format=FORMAT
```

#### Windows (cmd.exe)

```
gcloud iam access-policies search-policy-bindings UAP_ID ^
    --UAP_PARENT_RESOURCE_TYPE=UAP_PARENT_RESOURCE_ID ^
    --location=global --format=FORMAT
```

The response contains the bindings for the specified UAP.

```
{
  "policyBindings": [
    {
      "createTime": "2026-05-06T18:08:24.729843Z",
      "displayName": "Example binding 1",
      "etag": "W/\"xkdnPfTxoxyVqOwhQSJbMg==\"",
      "name": "organizations/123456789012/locations/global/policyBindings/example-binding1",
      "policy": "organizations/123456789012/locations/global/accessPolicies/example-policy",
      "policyKind": "ACCESS",
      "policyUid": "puid_9519202237377675265",
      "target": {
        "resource": "//cloudresourcemanager.googleapis.com/organizations/123456789012"
      },
      "uid": "buid_9904260005517852673", 
      "updateTime": "2026-05-06T18:08:24.729843Z"
    },
    {
      "createTime": "2026-05-07T07:05:06.203861Z",
      "displayName": "Example binding 2",
      "etag": "W/\"cRMdDXbT82aLuZlvoL9Gqg==\"",
      "name": "organizations/123456789012/locations/global/policyBindings/example-binding2",
      "policy": "organizations/123456789012/locations/global/accessPolicies/example-policy",
      "policyKind": "ACCESS",
      "policyUid": "puid_9519202237377675265",
      "target": {
        "resource": "//cloudresourcemanager.googleapis.com/projects/example-project"
      },
      "uid": "buid_4331055466646863873", 
      "updateTime": "2026-05-07T07:05:06.203861Z"
    }
  ]
}
```

### REST

The [`accessPolicies.searchPolicyBindings`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/searchPolicyBindings) method lists all bindings for the specified UAP.

Before using any of the request data, make the following replacements:

- `UAP_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that owns the UAP that you want to list bindings for. Use the value `projects` , `folders` , or `organizations` .
- `UAP_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that owns the UAP that you want to list bindings for. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .
- `UAP_ID` : The ID of the UAP that you want to list bindings for—for example, `example-policy` .

HTTP method and URL:

```
GET https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies/UAP_ID:searchPolicyBindings
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X GET \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies/UAP_ID:searchPolicyBindings"
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
    -Uri "https://iam.googleapis.com/v3/UAP_PARENT_RESOURCE_TYPE/UAP_PARENT_RESOURCE_ID/locations/global/accessPolicies/UAP_ID:searchPolicyBindings" | Select-Object -Expand Content
```

The response contains the bindings for the specified UAP.

```
{
  "policyBindings": [
    {
      "name": "organizations/123456789012/locations/global/policyBindings/example-binding1",
      "uid": "buid_9904260005517852673", 
      "etag": "W/\"xkdnPfTxoxyVqOwhQSJbMg==\"",
      "displayName": "Example binding 1",
      "target": {
        "resource": "//cloudresourcemanager.googleapis.com/organizations/123456789012"
      },
      "policyKind": "ACCESS",
      "policy": "organizations/123456789012/locations/global/accessPolicies/example-policy",
      "policyUid": "puid_9519202237377675265",
      "createTime": "2026-05-06T18:08:24.729843Z",
      "updateTime": "2026-05-06T18:08:24.729843Z"
    },
    {
      "name": "organizations/123456789012/locations/global/policyBindings/example-binding2",
      "uid": "buid_4331055466646863873", 
      "etag": "W/\"cRMdDXbT82aLuZlvoL9Gqg==\"",
      "displayName": "Example binding 2",
      "target": {
        "resource": "//cloudresourcemanager.googleapis.com/projects/example-project"
      },
      "policyKind": "ACCESS",
      "policy": "organizations/123456789012/locations/global/accessPolicies/example-policy",
      "policyUid": "puid_9519202237377675265",
      "createTime": "2026-05-07T07:05:06.203861Z",
      "updateTime": "2026-05-07T07:05:06.203861Z"
    }
  ]
}
```

### List all bindings for a resource

To view all bindings that include a specific target resource, search the bindings for that resource.

Each binding contains the ID of the UAP that's bound to the resource. To see the details of a policy, use the policy ID to [get the policy details](https://docs.cloud.google.com/iam/docs/unified-access-policies-view#get-uap) .

You can view all bindings for a resource using the Google Cloud console, the gcloud CLI, or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Unified Access Policies** page.

2.  Select the project, folder, or organization whose bindings you want to view.

3.  In the **Filter** field, enter the filter **Enforcement: Enforced** .

The table displays all of the UAPs that are bound to the resource.

### gcloud

The [`gcloud iam policy-bindings search-target-policy-bindings`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/search-target-policy-bindings) command gets all UAP bindings that include the resource.

Before using any of the command data below, make the following replacements:

- `BINDING_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that parents bindings for the target resource. Use the value `project` , `folder` , or `organization` .

  To learn which resources parent which bindings, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) .

- `BINDING_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that parents bindings for the target resource. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

- `TARGET_RESOURCE` : The resource whose bindings you want to list. For a list of valid resources, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) .

- `FORMAT` : The format for the response. Use `json` or `yaml` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam policy-bindings search-target-policy-bindings \
    --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID \
    --target=TARGET_RESOURCE \
    --format=FORMAT
```

#### Windows (PowerShell)

```
gcloud iam policy-bindings search-target-policy-bindings `
    --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID `
    --target=TARGET_RESOURCE `
    --format=FORMAT
```

#### Windows (cmd.exe)

```
gcloud iam policy-bindings search-target-policy-bindings ^
    --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID ^
    --target=TARGET_RESOURCE ^
    --format=FORMAT
```

The response contains all UAP bindings that include the target resource.

```
{
  "policyBindings": [
    {
      "createTime": "2026-05-06T18:08:24.729843Z",
      "displayName": "Example binding 1",
      "etag": "W/\"xkdnPfTxoxyVqOwhQSJbMg==\"",
      "name": "organizations/123456789012/locations/global/policyBindings/example-binding1",
      "policy": "organizations/123456789012/locations/global/accessPolicies/example-uap-policy-1",
      "policyKind": "ACCESS",
      "policyUid": "puid_9519202237377675265",
      "target": {
        "resource": "//cloudresourcemanager.googleapis.com/organizations/123456789012"
      },
      "uid": "buid_9904260005517852673", 
      "updateTime": "2026-05-06T18:11:16.798841Z"
    },
    {
      "createTime": "2026-05-06T18:08:24.729843Z",
      "displayName": "Example binding 2",
      "etag": "W/\"xkdnPfTxoxyVqOwhQSJbMg==\"",
      "name": "organizations/123456789012/locations/global/policyBindings/example-binding2",
      "policy": "organizations/123456789012/locations/global/accessPolicies/example-uap-policy-2",
      "policyKind": "ACCESS",
      "policyUid": "puid_10358560617928851457",
      "target": {
        "resource": "//cloudresourcemanager.googleapis.com/organizations/123456789012"
      },
      "uid": "buid_4331055466646863873", 
      "updateTime": "2026-05-06T18:11:16.798841Z"
    }
  ]
}
```

### REST

The [`SearchTargetPolicyBindings.search`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings/searchTargetPolicyBindings) method gets all UAP bindings that include the resource.

Before using any of the request data, make the following replacements:

- `BINDING_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that parents bindings for the target resource. Use the value `projects` , `folders` , or `organizations` .

  To learn which resources parent which bindings, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) .

- `BINDING_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that parents bindings for the target resource. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

- `TARGET_RESOURCE` : The resource whose bindings you want to list. For a list of valid resources, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) .

HTTP method and URL:

```
GET https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings:searchTargetPolicyBindings?target=TARGET_RESOURCE
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X GET \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings:searchTargetPolicyBindings?target=TARGET_RESOURCE"
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
    -Uri "https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings:searchTargetPolicyBindings?target=TARGET_RESOURCE" | Select-Object -Expand Content
```

The response contains all UAP bindings that include the target resource.

```
{
  "policyBindings": [
    {
      "name": "organizations/123456789012/locations/global/policyBindings/example-binding1",
      "uid": "buid_9904260005517852673", 
      "etag": "W/\"xkdnPfTxoxyVqOwhQSJbMg==\"",
      "displayName": "Example binding 1",
      "target": {
        "resource": "//cloudresourcemanager.googleapis.com/organizations/123456789012"
      },
      "policy": "organizations/123456789012/locations/global/accessPolicies/example-uap-policy-1",
      "createTime": "2026-05-06T18:08:24.729843Z",
      "updateTime": "2026-05-06T18:11:16.798841Z",
      "policyKind": "ACCESS",
      "policyUid": "puid_9519202237377675265"
    },
    {
      "name": "organizations/123456789012/locations/global/policyBindings/example-binding2",
      "uid": "buid_4331055466646863873", 
      "etag": "W/\"xkdnPfTxoxyVqOwhQSJbMg==\"",
      "displayName": "Example binding 2",
      "target": {
        "resource": "//cloudresourcemanager.googleapis.com/organizations/123456789012"
      },
      "policy": "organizations/123456789012/locations/global/accessPolicies/example-uap-policy-2",
      "createTime": "2026-05-06T18:08:24.729843Z",
      "updateTime": "2026-05-06T18:11:16.798841Z",
      "policyKind": "ACCESS",
      "policyUid": "puid_10358560617928851457"
    }
  ]
}
```

### List all bindings in a project, folder, or organization

If you're using the gcloud CLI or the IAM REST API to view bindings, then you can also list all bindings that are children of a specific project, folder, or organization.

Listing bindings for a project, folder, or organization is similar to [searching the bindings](https://docs.cloud.google.com/iam/docs/unified-access-policies-view#search-target-bindings) for that resource. However, unlike searching bindings, listing bindings for a resource also includes all of the bindings that are immediate children of that resource.

For example, imagine that you have a binding that attaches a policy to a Network Services API agent gateway. This binding's parent resource is the agent gateway's parent project. In other words, the binding is an immediate child of the project. As a result, if you list bindings for that project, then the response includes the binding for the agent gateway. However, if you list bindings for the project's parent organization, then the response doesn't include the binding. That's because, even though the binding is a descendant of the organization, it isn't an immediate child of the organization.

A binding's parent resource depends on the target resource in the binding. To learn more, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) .

Each binding contains the ID of the UAP that's bound to the resource. To see the details of a policy, use the policy ID to [get the policy details](https://docs.cloud.google.com/iam/docs/unified-access-policies-view#get-uap) .

You can view all bindings that are children of a project, folder, or organization using the gcloud CLI or the IAM REST API.

### gcloud

The [`gcloud iam policy-bindings list`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/list) command lists all UAP bindings that are children of a certain resource.

Before using any of the command data below, make the following replacements:

- `BINDING_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that the binding is a child of. Use the value `project` , `folder` , or `organization` .

  The binding's parent resource depends on the target resource in the binding. For more information, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) .

- `BINDING_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that the policy binding is a child of. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

- `FORMAT` : The format for the response. Use `json` or `yaml` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam policy-bindings list --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID \
    --location=global \
    --filter=policyKind:ACCESS \
    --format=FORMAT
```

#### Windows (PowerShell)

```
gcloud iam policy-bindings list --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID `
    --location=global `
    --filter=policyKind:ACCESS `
    --format=FORMAT
```

#### Windows (cmd.exe)

```
gcloud iam policy-bindings list --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID ^
    --location=global ^
    --filter=policyKind:ACCESS ^
    --format=FORMAT
```

The response contains the UAP bindings that are children of the resource in the command.

```
{
  "policyBindings": [
    {
      "createTime": "2026-05-06T18:08:24.729843Z",
      "displayName": "Example binding 1",
      "etag": "W/\"xkdnPfTxoxyVqOwhQSJbMg==\"",
      "name": "organizations/123456789012/locations/global/policyBindings/example-binding-1",
      "policy": "organizations/123456789012/locations/global/accessPolicies/example-uap-1",
      "policyKind": "ACCESS",
      "policyUid": "puid_9519202237377675265",
      "target": {
        "resource": "//cloudresourcemanager.googleapis.com/organizations/123456789012"
      },
      "uid": "buid_9904260005517852673", 
      "updateTime": "2026-05-06T18:08:24.729843Z"
    },
    {
      "createTime": "2026-05-07T07:05:06.203861Z",
      "displayName": "Example binding 2",
      "etag": "W/\"cRMdDXbT82aLuZlvoL9Gqg==\"",
      "name": "organizations/123456789012/locations/global/policyBindings/example-binding-2",
      "policy": "organizations/123456789012/locations/global/accessPolicies/example-uap-2",
      "policyKind": "ACCESS",
      "policyUid": "puid_1566408245394800641",
      "target": {
        "resource": "//cloudresourcemanager.googleapis.com/organizations/123456789012"
      },
      "uid": "buid_4331055466646863873", 
      "updateTime": "2026-05-07T07:05:06.203861Z"
    }
  ]
}
```

### REST

The [`policyBindings.list`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings/list) method lists all UAP bindings that are children of a certain resource.

Before using any of the request data, make the following replacements:

- `BINDING_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that the binding is a child of. Use the value `projects` , `folders` , or `organizations` .

  The binding's parent resource depends on the target resource in the binding. For more information, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) .

- `BINDING_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that the policy binding is a child of. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

HTTP method and URL:

```
GET https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings?filter=policyKind:ACCESS
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X GET \
     -H "Authorization: Bearer $(gcloud auth print-access-token)" \
     "https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings?filter=policyKind:ACCESS"
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
    -Uri "https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings?filter=policyKind:ACCESS" | Select-Object -Expand Content
```

The response contains the UAP bindings that are children of the resource in the request.

```
{
  "policyBindings": [
    {
      "name": "organizations/123456789012/locations/global/policyBindings/example-binding-1",
      "uid": "buid_9904260005517852673", 
      "etag": "W/\"xkdnPfTxoxyVqOwhQSJbMg==\"",
      "displayName": "Example binding 1",
      "target": {
        "resource": "//cloudresourcemanager.googleapis.com/organizations/123456789012"
      },
      "policyKind": "ACCESS",
      "policy": "organizations/123456789012/locations/global/accessPolicies/example-uap-1",
      "policyUid": "puid_9519202237377675265",
      "createTime": "2026-05-06T18:08:24.729843Z",
      "updateTime": "2026-05-06T18:08:24.729843Z"
    },
    {
      "name": "organizations/123456789012/locations/global/policyBindings/example-binding-2",
      "uid": "buid_4331055466646863873", 
      "etag": "W/\"cRMdDXbT82aLuZlvoL9Gqg==\"",
      "displayName": "Example binding 2",
      "target": {
        "resource": "//cloudresourcemanager.googleapis.com/organizations/123456789012"
      },
      "policyKind": "ACCESS",
      "policy": "organizations/123456789012/locations/global/accessPolicies/example-uap-2",
      "policyUid": "puid_1566408245394800641",
      "createTime": "2026-05-07T07:05:06.203861Z",
      "updateTime": "2026-05-07T07:05:06.203861Z"
    }
  ]
}
```

## Get a binding for a Unified Access Policy

You can get the details of a binding using the Google Cloud console, the gcloud CLI, or the IAM REST API.

### Console

1.  In the Google Cloud console, go to the **Unified Access Policies** page.

2.  Select the project, folder, or organization that owns the UAP whose bindings you want to view.

3.  Click the policy ID of the UAP whose bindings you want to view.

4.  Select the **Bindings** tab.

5.  Find the binding using the binding ID or the binding name.

The table displays the binding details, including the binding ID, the binding name, and the target resource in the binding.

### gcloud

The [`gcloud iam policy-bindings describe`](https://docs.cloud.google.com/sdk/gcloud/reference/iam/policy-bindings/describe) command gets a binding.

Before using any of the command data below, make the following replacements:

- `BINDING_ID` : The ID of the binding that you want to get—for example, `example-binding` .

- `BINDING_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that the binding is a child of. Use the value `project` , `folder` , or `organization` .

  The binding's parent resource depends on the target resource in the binding. For more information, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) .

- `BINDING_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that the policy binding is a child of. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

- `FORMAT` : The format for the response. Use `json` or `yaml` .

Execute the following command:

#### Linux, macOS, or Cloud Shell

```
gcloud iam policy-bindings describe BINDING_ID \
    --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID \
    --location=global --format=FORMAT
```

#### Windows (PowerShell)

```
gcloud iam policy-bindings describe BINDING_ID `
    --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID `
    --location=global --format=FORMAT
```

#### Windows (cmd.exe)

```
gcloud iam policy-bindings describe BINDING_ID ^
    --BINDING_PARENT_RESOURCE_TYPE=BINDING_PARENT_RESOURCE_ID ^
    --location=global --format=FORMAT
```

The response contains the binding.

```
{
  "createTime": "2026-05-06T18:08:24.729843Z",
  "displayName": "Example binding",
  "etag": "W/\"xkdnPfTxoxyVqOwhQSJbMg==\"",
  "name": "organizations/123456789012/locations/global/policyBindings/example-binding",
  "policy": "organizations/123456789012/locations/global/accessPolicies/example-uap",
  "policyKind": "ACCESS",
  "policyUid": "puid_9519202237377675265",
  "target": {
    "resource": "//cloudresourcemanager.googleapis.com/organizations/123456789012"
  },
  "uid": "buid_9904260005517852673", 
  "updateTime": "2026-05-06T18:08:24.729843Z"
}
```

### REST

The [`policyBindings.get`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings/get) method gets a binding.

Before using any of the request data, make the following replacements:

- `BINDING_PARENT_RESOURCE_TYPE` : The type of the Resource Manager resource (project, folder, or organization) that the binding is a child of. Use the value `projects` , `folders` , or `organizations` .

  The binding's parent resource depends on the target resource in the binding. For more information, see [Supported resources](https://docs.cloud.google.com/iam/docs/unified-access-policies#policy-bindings-supported-resources) .

- `BINDING_PARENT_RESOURCE_ID` : The ID of the project, folder, or organization that the policy binding is a child of. Project IDs are alphanumeric strings, like `my-project` . Folder and organization IDs are numeric, like `123456789012` .

- `BINDING_ID` : The ID of the binding that you want to get—for example, `example-binding` .

HTTP method and URL:

```
GET https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings/BINDING_ID
```

To send your request, expand one of these options:

#### curl (Linux, macOS, or Cloud Shell)

> **Note:** The following command assumes that you have logged in to the `gcloud` CLI with your user account by running [`gcloud init`](https://docs.cloud.google.com/sdk/gcloud/reference/init) or [`gcloud auth login`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/login) , or by using [Cloud Shell](https://docs.cloud.google.com/shell/docs) , which automatically logs you into the `gcloud` CLI . You can check the currently active account by running [`gcloud auth list`](https://docs.cloud.google.com/sdk/gcloud/reference/auth/list) .

Execute the following command:

```
curl -X GET \
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
    -Method GET `
    -Headers $headers `
    -Uri "https://iam.googleapis.com/v3/BINDING_PARENT_RESOURCE_TYPE/BINDING_PARENT_RESOURCE_ID/locations/global/policyBindings/BINDING_ID" | Select-Object -Expand Content
```

The response contains the binding.

```
{
  "name": "organizations/123456789012/locations/global/policyBindings/example-binding",
  "uid": "buid_9904260005517852673", 
  "etag": "W/\"xkdnPfTxoxyVqOwhQSJbMg==\"",
  "displayName": "Example binding",
  "target": {
    "resource": "//cloudresourcemanager.googleapis.com/organizations/123456789012"
  },
  "policyKind": "ACCESS",
  "policy": "organizations/123456789012/locations/global/accessPolicies/example-uap",
  "policyUid": "puid_9519202237377675265",
  "createTime": "2026-05-06T18:08:24.729843Z",
  "updateTime": "2026-05-06T18:08:24.729843Z"
}
```

## What's next

- [Create and apply UAPs](https://docs.cloud.google.com/iam/docs/unified-access-policies-create-apply)
- [Edit UAPs and bindings](https://docs.cloud.google.com/iam/docs/unified-access-policies-edit)
- [Remove UAPs and bindings](https://docs.cloud.google.com/iam/docs/unified-access-policies-remove)
