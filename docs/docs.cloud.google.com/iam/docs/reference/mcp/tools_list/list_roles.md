---
name: documents/docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_roles
uri: https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_roles
title: 'MCP Tools Reference: iam.googleapis.com'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Tool: `list_roles`

Lists every custom IAM role that is defined for a Google Cloud project. Organizations are *not* supported.

Use this tool to discover available custom roles. Predefined roles are *not* supported by this tool.

This tool requires the following parameters:

- `parent` (string): The parent resource name under which custom roles are defined. Only projects are supported. The format is `projects/PROJECT_ID` . Wildcards and empty parent values are not supported.

The following parameters are optional:

- `page_size` (int32): The maximum number of roles to return. Default is 300, max is 1000.
- `page_token` (string): Pagination token from a previous list request.
- `view` (string): Level of details. Supported values are 'BASIC' (default, excludes permissions) and 'FULL' (includes permissions).
- `show_deleted` (boolean): If true, deleted custom roles are included in the results.

This tool returns a list of custom roles for the project along with an optional next page token.

The following code sample shows how to use `curl` to call the `list_roles` MCP tool.

**Curl Request**

```
curl --location 'https://iam.googleapis.com/mcp' \
--header 'content-type: application/json' \
--header 'accept: application/json, text/event-stream' \
--data '{
  "method": "tools/call",
  "params": {
    "name": "list_roles",
    "arguments": {
      // Provide these details according to the MCP tool specification.
    }
  },
  "jsonrpc": "2.0",
  "id": 1
}'
```

## Input Schema

The request to get all roles defined under a resource.

### ListRolesRequest

**JSON representation**

```
{
  "parent": string,
  "pageSize": integer,
  "pageToken": string,
  "view": enum (RoleView),
  "showDeleted": boolean
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
<td><code>parent</code></td>
<td><p><code>string</code></p>
<p>The <code>parent</code> parameter's value depends on the target resource for the request, namely <a href="https://cloud.google.com/iam/docs/reference/rest/v1/roles">roles</a> , <a href="https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles">projects</a> , or <a href="https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles">organizations</a> . Each resource type's <code>parent</code> value format is described below:</p>
<ul>
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/roles/list">roles.list</a> : An empty string. This method doesn't require a resource; it simply returns all <a href="https://cloud.google.com/iam/docs/understanding-roles#predefined_roles">predefined roles</a> in IAM. Example request URL: <code>https://iam.googleapis.com/v1/roles</code></p></li>
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/list">projects.roles.list</a> : <code>projects/{PROJECT_ID}</code> . This method lists all project-level <a href="https://cloud.google.com/iam/docs/understanding-custom-roles">custom roles</a> . Example request URL: <code>https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles</code></p></li>
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list">organizations.roles.list</a> : <code>organizations/{ORGANIZATION_ID}</code> . This method lists all organization-level <a href="https://cloud.google.com/iam/docs/understanding-custom-roles">custom roles</a> . Example request URL: <code>https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles</code></p></li>
</ul>
<p>Note: Wildcard (*) values are invalid; you must specify a complete project ID or organization ID.</p></td>
</tr>
<tr class="even">
<td><code>pageSize</code></td>
<td><p><code>integer</code></p>
<p>Optional limit on the number of roles to include in the response.</p>
<p>The default is 300, and the maximum is 1,000.</p></td>
</tr>
<tr class="odd">
<td><code>pageToken</code></td>
<td><p><code>string</code></p>
<p>Optional pagination token returned in an earlier ListRolesResponse.</p></td>
</tr>
<tr class="even">
<td><code>view</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_roles#Input.Schema.RoleView"><code>RoleView</code></a><code> )</code></p>
<p>Optional view for the returned Role objects. When <code>FULL</code> is specified, the <code>includedPermissions</code> field is returned, which includes a list of all permissions in the role. The default value is <code>BASIC</code> , which does not return the <code>includedPermissions</code> field.</p></td>
</tr>
<tr class="odd">
<td><code>showDeleted</code></td>
<td><p><code>boolean</code></p>
<p>Include Roles that have been deleted.</p></td>
</tr>
</tbody>
</table>

### RoleView

A view for Role objects.

| Enums   |                                                                    |
|---------|--------------------------------------------------------------------|
| `BASIC` | Omits the `included_permissions` field. This is the default value. |
| `FULL`  | Returns all fields.                                                |

## Output Schema

The response containing the roles defined under a resource.

### ListRolesResponse

**JSON representation**

```
{
  "roles": [
    {
      object (Role)
    }
  ],
  "nextPageToken": string
}
```

| Fields          |                                                                                                                                                            |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `roles[]`       | `object ( `[`Role`](https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_roles#Output.Schema.Role)` )` The Roles defined on this resource. |
| `nextPageToken` | `string` To retrieve the next page of results, set `ListRolesRequest.page_token` to this value.                                                            |

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

Destructive Hint: ❌ \| Idempotent Hint: ✅ \| Read Only Hint: ✅ \| Open World Hint: ❌
