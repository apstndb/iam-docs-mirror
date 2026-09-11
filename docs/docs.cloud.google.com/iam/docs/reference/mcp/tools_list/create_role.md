---
name: documents/docs.cloud.google.com/iam/docs/reference/mcp/tools_list/create_role
uri: https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/create_role
title: 'MCP Tools Reference: iam.googleapis.com'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Tool: `create_role`

Creates a new custom IAM role for a Google Cloud project. Organizations are *not* supported.

Use this tool only when predefined roles do not satisfy your needs and you require a specific, customized combination of permissions.

This tool requires the following parameters:

  - `parent` (string): The resource where the role will be created. Only projects are supported. The format is `projects/PROJECT_ID` .

  - `role_id` (string): A unique identifier for the role. Must be 3-64 characters and contain only alphanumeric characters, underscores, and periods.

  - `role` (object): The role definition containing the following fields:
    
      - `title` (string): Required. A friendly title for the role.
      - `description` (string): Optional. A description of the role.
      - `included_permissions` (list of strings): Required. The list of IAM permissions this role grants (for example, `['iam.roles.list', 'iam.roles.get']` ).
      - `stage` (string): Optional. The launch stage of the role. Supported values are: `ALPHA` , `BETA` , `GA` , `DEPRECATED` , `DISABLED` , `EAP` .

This tool returns the created role definition.

The following code sample shows how to use `curl` to call the `create_role` MCP tool.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>Curl Request</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" data-syntax="Bash" translate="no"><code>curl --location &#39;https://iam.googleapis.com/mcp&#39; \
--header &#39;content-type: application/json&#39; \
--header &#39;accept: application/json, text/event-stream&#39; \
--data &#39;{
  &quot;method&quot;: &quot;tools/call&quot;,
  &quot;params&quot;: {
    &quot;name&quot;: &quot;create_role&quot;,
    &quot;arguments&quot;: {
      // Provide these details according to the MCP tool specification.
    }
  },
  &quot;jsonrpc&quot;: &quot;2.0&quot;,
  &quot;id&quot;: 1
}&#39;</code></pre></td>
</tr>
</tbody>
</table>

## Input Schema

The request to create a new role.

### CreateRoleRequest

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;parent&quot;: string,&quot;roleId&quot;: string,&quot;role&quot;: {object (Role)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`parent`

`string`

The `parent` parameter's value depends on the target resource for the request, namely [projects](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles) or [organizations](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles) . Each resource type's `parent` value format is described below:

  - [projects.roles.create](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create) : `projects/{PROJECT_ID}` . This method creates project-level [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) . Example request URL: `https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles`

  - [organizations.roles.create](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create) : `organizations/{ORGANIZATION_ID}` . This method creates organization-level [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) . Example request URL: `https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles`

Note: Wildcard (\*) values are invalid; you must specify a complete project ID or organization ID.

`roleId`

`string`

The role ID to use for this role.

A role ID may contain alphanumeric characters, underscores ( `_` ), and periods ( `.` ). It must contain a minimum of 3 characters and a maximum of 64 characters.

`role`

` object ( Role  ` )

The Role resource to create.

### Role

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;title&quot;: string,&quot;description&quot;: string,&quot;includedPermissions&quot;: [string],&quot;stage&quot;: enum (RoleLaunchStage),&quot;etag&quot;: string,&quot;deleted&quot;: boolean}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

The name of the role.

When `Role` is used in `CreateRole` , the role name must not be set.

When `Role` is used in output and other input such as `UpdateRole` , the role name is the complete path. For example, `roles/logging.viewer` for predefined roles, `organizations/{ORGANIZATION_ID}/roles/myRole` for organization-level custom roles, and `projects/{PROJECT_ID}/roles/myRole` for project-level custom roles.

`title`

`string`

Optional. A human-readable title for the role. Typically this is limited to 100 UTF-8 bytes.

`description`

`string`

Optional. A human-readable description for the role.

`includedPermissions[]`

`string`

The names of the permissions this role grants when bound in an IAM policy.

`stage`

` enum ( RoleLaunchStage  ` )

The current launch stage of the role. If the `ALPHA` launch stage has been selected for a role, the `stage` field will not be included in the returned definition for the role.

`etag`

`string ( bytes format)`

Used to perform a consistent read-modify-write.

A base64-encoded string.

`deleted`

`boolean`

The current deleted state of the role. This field is read only. It will be ignored in calls to CreateRole and UpdateRole.

### RoleLaunchStage

A stage representing a role's lifecycle phase.

Enums

`ALPHA`

The user has indicated this role is currently in an Alpha phase. If this launch stage is selected, the `stage` field will not be included when requesting the definition for a given role.

`BETA`

The user has indicated this role is currently in a Beta phase.

`GA`

The user has indicated this role is generally available.

`DEPRECATED`

The user has indicated this role is being deprecated.

`DISABLED`

This role is disabled and will not contribute permissions to any principals it is granted to in policies.

`EAP`

The user has indicated this role is currently in an EAP phase.

## Output Schema

A role in the Identity and Access Management API.

### Role

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;title&quot;: string,&quot;description&quot;: string,&quot;includedPermissions&quot;: [string],&quot;stage&quot;: enum (RoleLaunchStage),&quot;etag&quot;: string,&quot;deleted&quot;: boolean}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

The name of the role.

When `Role` is used in `CreateRole` , the role name must not be set.

When `Role` is used in output and other input such as `UpdateRole` , the role name is the complete path. For example, `roles/logging.viewer` for predefined roles, `organizations/{ORGANIZATION_ID}/roles/myRole` for organization-level custom roles, and `projects/{PROJECT_ID}/roles/myRole` for project-level custom roles.

`title`

`string`

Optional. A human-readable title for the role. Typically this is limited to 100 UTF-8 bytes.

`description`

`string`

Optional. A human-readable description for the role.

`includedPermissions[]`

`string`

The names of the permissions this role grants when bound in an IAM policy.

`stage`

` enum ( RoleLaunchStage  ` )

The current launch stage of the role. If the `ALPHA` launch stage has been selected for a role, the `stage` field will not be included in the returned definition for the role.

`etag`

`string ( bytes format)`

Used to perform a consistent read-modify-write.

A base64-encoded string.

`deleted`

`boolean`

The current deleted state of the role. This field is read only. It will be ignored in calls to CreateRole and UpdateRole.

### RoleLaunchStage

A stage representing a role's lifecycle phase.

Enums

`ALPHA`

The user has indicated this role is currently in an Alpha phase. If this launch stage is selected, the `stage` field will not be included when requesting the definition for a given role.

`BETA`

The user has indicated this role is currently in a Beta phase.

`GA`

The user has indicated this role is generally available.

`DEPRECATED`

The user has indicated this role is being deprecated.

`DISABLED`

This role is disabled and will not contribute permissions to any principals it is granted to in policies.

`EAP`

The user has indicated this role is currently in an EAP phase.

### Tool Annotations

[Tool annotations](https://modelcontextprotocol.io/specification/latest/schema#toolannotations) are sent to MCP clients to describe the basic risk of a given tool. Most clients treat these hints as untrusted, but they can be used to decide when a confirmation prompt might be sent to a user.

Along with the title string, the following boolean hints are defined as follows:

  - `readOnlyHint` : If true, the tool doesn't modify its environment. Default: false.
  - `destructiveHint` : If true, then the tool can perform destructive actions. If false, then the tool can only perform additive actions. Default: true.
  - `idempotentHint` : If true, then calling the tool repeatedly with the same arguments will have no additional effect on its environment. Default: false.
  - `openWorldHint` : If true, then the tool can interact with an 'open world' of external entities. If false, then the tool can only interact with internal entities. For example, a web search tool would be open world, while a memory tool would not be open world.

Destructive Hint: ❌ | Idempotent Hint: ❌ | Read Only Hint: ❌ | Open World Hint: ❌
