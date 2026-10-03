---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/roles
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles
title: 'REST Resource: roles'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: Role](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles#Role)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles#Role.SCHEMA_REPRESENTATION)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles#METHODS_SUMMARY)

## Resource: Role

A role in the Identity and Access Management API.

**JSON representation**

```
{
  "name": string,
  "title": string,
  "description": string,
  "includedPermissions": [
    string
  ],
  "stage": enum (RoleLaunchStage),
  "etag": string,
  "deleted": boolean
}
```

| Fields                  |                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`                  | `string` The name of the role. When `Role` is used in `roles.create` , the role name must not be set. When `Role` is used in output and other input such as `roles.patch` , the role name is the complete path. For example, `roles/logging.viewer` for predefined roles, `organizations/{ORGANIZATION_ID}/roles/myRole` for organization-level custom roles, and `projects/{PROJECT_ID}/roles/myRole` for project-level custom roles. |
| `title`                 | `string` Optional. A human-readable title for the role. Typically this is limited to 100 UTF-8 bytes.                                                                                                                                                                                                                                                                                                                                  |
| `description`           | `string` Optional. A human-readable description for the role.                                                                                                                                                                                                                                                                                                                                                                          |
| `includedPermissions[]` | `string` The names of the permissions this role grants when bound in an IAM policy.                                                                                                                                                                                                                                                                                                                                                    |
| `stage`                 | `enum ( `[`RoleLaunchStage`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role.RoleLaunchStage)` )` The current launch stage of the role. If the `ALPHA` launch stage has been selected for a role, the `stage` field will not be included in the returned definition for the role.                                                                                                                    |
| `etag`                  | `string ( `[`bytes`](https://developers.google.com/discovery/v1/type-format)` format)` Used to perform a consistent read-modify-write. A base64-encoded string.                                                                                                                                                                                                                                                                        |
| `deleted`               | `boolean` The current deleted state of the role. This field is read only. It will be ignored in calls to roles.create and roles.patch.                                                                                                                                                                                                                                                                                                 |

| Methods                                                                                                     |                                                                                                                                                                                                            |
|-------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/get)                                 | Gets the definition of a [`Role`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role) .                                                                                     |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/list)                               | Lists every predefined [`Role`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role) that IAM supports, or every custom role that is defined for an organization or project. |
| [`queryGrantableRoles`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/queryGrantableRoles) | Lists roles that can be granted on a Google Cloud resource.                                                                                                                                                |
