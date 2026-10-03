---
name: documents/docs.cloud.google.com/iam/docs/reference/mcp/tools_list/update_role
uri: https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/update_role
title: 'MCP Tools Reference: iam.googleapis.com'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Tool: `update_role`

Updates the definition of an existing custom IAM role. Use this tool to modify the title, description, launch stage, or set of permissions of a role that was previously created.

Do *not* use this tool to update predefined roles (for example, `roles/viewer` or `roles/iam.viewer` ), as they are managed by Google and cannot be modified.

This tool requires the following parameters:

- `name` (string): The resource name of the role to update. The format is `projects/PROJECT_ID/roles/ROLE_ID` or `organizations/ORGANIZATION_ID/roles/ROLE_ID` .

- `role` (object): The updated role definition containing the fields to modify. You must specify at least one of the following parameters:

  - `title` (string): The new title for the role.
  - `description` (string): The new description.
  - `included_permissions` (list of strings): The complete, updated list of permissions. This will replace the existing permissions.
  - `stage` (string): The updated launch stage (for example, 'ALPHA', 'BETA', 'GA').

The following parameters are optional:

- `update_mask` (string): A comma-separated list of fields in the `role` object to update (for example, 'title,included_permissions'). If omitted, all non-empty fields in `role` will be updated.

This tool returns the updated role definition.

The following code sample shows how to use `curl` to call the `update_role` MCP tool.

**Curl Request**

```
curl --location 'https://iam.googleapis.com/mcp' \
--header 'content-type: application/json' \
--header 'accept: application/json, text/event-stream' \
--data '{
  "method": "tools/call",
  "params": {
    "name": "update_role",
    "arguments": {
      // Provide these details according to the MCP tool specification.
    }
  },
  "jsonrpc": "2.0",
  "id": 1
}'
```

## Input Schema

The request to update a role.

### UpdateRoleRequest

**JSON representation**

```
{
  "name": string,
  "role": {
    object (Role)
  },
  "updateMask": string
}
```

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>The <code>name</code> parameter's value depends on the target resource for the request, namely <a href="https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles">projects</a> or <a href="https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles">organizations</a> . Each resource type's <code>name</code> value format is described below:</p>
<ul>
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/patch">projects.roles.patch</a> : <code>projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}</code> . This method updates only <a href="https://cloud.google.com/iam/docs/understanding-custom-roles">custom roles</a> that have been created at the project level. Example request URL: <code>https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}</code></p></li>
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/patch">organizations.roles.patch</a> : <code>organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}</code> . This method updates only <a href="https://cloud.google.com/iam/docs/understanding-custom-roles">custom roles</a> that have been created at the organization level. Example request URL: <code>https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}</code></p></li>
</ul>
<p>Note: Wildcard (*) values are invalid; you must specify a complete project ID or organization ID.</p></td>
</tr>
<tr class="even">
<td><code>role</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_roles#Output.Schema.Role"><code>Role</code></a><code> )</code></p>
<p>The updated role.</p></td>
</tr>
<tr class="odd">
<td><code>updateMask</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#field-mask"><code>FieldMask</code></a><code> format)</code></p>
<p>A mask describing which fields in the Role have changed.</p>
<p>This is a comma-separated list of fully qualified names of fields. Example: <code>"user.displayName,photo"</code> .</p></td>
</tr>
</tbody>
</table>

### Role

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

| Fields                  |                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|-------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`                  | `string` The name of the role. When `Role` is used in `CreateRole` , the role name must not be set. When `Role` is used in output and other input such as `UpdateRole` , the role name is the complete path. For example, `roles/logging.viewer` for predefined roles, `organizations/{ORGANIZATION_ID}/roles/myRole` for organization-level custom roles, and `projects/{PROJECT_ID}/roles/myRole` for project-level custom roles. |
| `title`                 | `string` Optional. A human-readable title for the role. Typically this is limited to 100 UTF-8 bytes.                                                                                                                                                                                                                                                                                                                               |
| `description`           | `string` Optional. A human-readable description for the role.                                                                                                                                                                                                                                                                                                                                                                       |
| `includedPermissions[]` | `string` The names of the permissions this role grants when bound in an IAM policy.                                                                                                                                                                                                                                                                                                                                                 |
| `stage`                 | `enum ( `[`RoleLaunchStage`](https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_roles#Output.Schema.RoleLaunchStage)` )` The current launch stage of the role. If the `ALPHA` launch stage has been selected for a role, the `stage` field will not be included in the returned definition for the role.                                                                                                          |
| `etag`                  | `string ( `[`bytes`](https://developers.google.com/discovery/v1/type-format)` format)` Used to perform a consistent read-modify-write. A base64-encoded string.                                                                                                                                                                                                                                                                     |
| `deleted`               | `boolean` The current deleted state of the role. This field is read only. It will be ignored in calls to CreateRole and UpdateRole.                                                                                                                                                                                                                                                                                                 |

### FieldMask

**JSON representation**

```
{
  "paths": [
    string
  ]
}
```

| Fields    |                                       |
|-----------|---------------------------------------|
| `paths[]` | `string` The set of field mask paths. |

### RoleLaunchStage

A stage representing a role's lifecycle phase.

| Enums        |                                                                                                                                                                                            |
|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `ALPHA`      | The user has indicated this role is currently in an Alpha phase. If this launch stage is selected, the `stage` field will not be included when requesting the definition for a given role. |
| `BETA`       | The user has indicated this role is currently in a Beta phase.                                                                                                                             |
| `GA`         | The user has indicated this role is generally available.                                                                                                                                   |
| `DEPRECATED` | The user has indicated this role is being deprecated.                                                                                                                                      |
| `DISABLED`   | This role is disabled and will not contribute permissions to any principals it is granted to in policies.                                                                                  |
| `EAP`        | The user has indicated this role is currently in an EAP phase.                                                                                                                             |

## Output Schema

A role in the Identity and Access Management API.

### Role

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

| Fields                  |                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|-------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`                  | `string` The name of the role. When `Role` is used in `CreateRole` , the role name must not be set. When `Role` is used in output and other input such as `UpdateRole` , the role name is the complete path. For example, `roles/logging.viewer` for predefined roles, `organizations/{ORGANIZATION_ID}/roles/myRole` for organization-level custom roles, and `projects/{PROJECT_ID}/roles/myRole` for project-level custom roles. |
| `title`                 | `string` Optional. A human-readable title for the role. Typically this is limited to 100 UTF-8 bytes.                                                                                                                                                                                                                                                                                                                               |
| `description`           | `string` Optional. A human-readable description for the role.                                                                                                                                                                                                                                                                                                                                                                       |
| `includedPermissions[]` | `string` The names of the permissions this role grants when bound in an IAM policy.                                                                                                                                                                                                                                                                                                                                                 |
| `stage`                 | `enum ( `[`RoleLaunchStage`](https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_roles#Output.Schema.RoleLaunchStage)` )` The current launch stage of the role. If the `ALPHA` launch stage has been selected for a role, the `stage` field will not be included in the returned definition for the role.                                                                                                          |
| `etag`                  | `string ( `[`bytes`](https://developers.google.com/discovery/v1/type-format)` format)` Used to perform a consistent read-modify-write. A base64-encoded string.                                                                                                                                                                                                                                                                     |
| `deleted`               | `boolean` The current deleted state of the role. This field is read only. It will be ignored in calls to CreateRole and UpdateRole.                                                                                                                                                                                                                                                                                                 |

### RoleLaunchStage

A stage representing a role's lifecycle phase.

| Enums        |                                                                                                                                                                                            |
|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `ALPHA`      | The user has indicated this role is currently in an Alpha phase. If this launch stage is selected, the `stage` field will not be included when requesting the definition for a given role. |
| `BETA`       | The user has indicated this role is currently in a Beta phase.                                                                                                                             |
| `GA`         | The user has indicated this role is generally available.                                                                                                                                   |
| `DEPRECATED` | The user has indicated this role is being deprecated.                                                                                                                                      |
| `DISABLED`   | This role is disabled and will not contribute permissions to any principals it is granted to in policies.                                                                                  |
| `EAP`        | The user has indicated this role is currently in an EAP phase.                                                                                                                             |

### Tool Annotations

[Tool annotations](https://modelcontextprotocol.io/specification/latest/schema#toolannotations) are sent to MCP clients to describe the basic risk of a given tool. Most clients treat these hints as untrusted, but they can be used to decide when a confirmation prompt might be sent to a user.

Along with the title string, the following boolean hints are defined as follows:

- `readOnlyHint` : If true, the tool doesn't modify its environment. Default: false.
- `destructiveHint` : If true, then the tool can perform destructive actions. If false, then the tool can only perform additive actions. Default: true.
- `idempotentHint` : If true, then calling the tool repeatedly with the same arguments will have no additional effect on its environment. Default: false.
- `openWorldHint` : If true, then the tool can interact with an 'open world' of external entities. If false, then the tool can only interact with internal entities. For example, a web search tool would be open world, while a memory tool would not be open world.

Destructive Hint: ❌ \| Idempotent Hint: ❌ \| Read Only Hint: ❌ \| Open World Hint: ❌
