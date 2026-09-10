---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/mcp/tools_list/recommend_iam_roles
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/mcp/tools_list/recommend_iam_roles
title: 'MCP Tools Reference: policyassist.googleapis.com'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

## Tool: `recommend_iam_roles`

This tool returns IAM role suggestions based on the intent of a user's prompt. Example prompt: 'What role do I need to read Google Cloud Storage buckets?'

The following code sample shows how to use `curl` to call the `recommend_iam_roles` MCP tool.

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
<td><pre dir="ltr" data-is-upgraded="" data-syntax="Bash" translate="no"><code>curl --location &#39;https://policyassist.googleapis.com/mcp&#39; \
--header &#39;content-type: application/json&#39; \
--header &#39;accept: application/json, text/event-stream&#39; \
--data &#39;{
  &quot;method&quot;: &quot;tools/call&quot;,
  &quot;params&quot;: {
    &quot;name&quot;: &quot;recommend_iam_roles&quot;,
    &quot;arguments&quot;: {
      // provide these details according to the tool&#39;s MCP specification
    }
  },
  &quot;jsonrpc&quot;: &quot;2.0&quot;,
  &quot;id&quot;: 1
}&#39;</code></pre></td>
</tr>
</tbody>
</table>

## Input Schema

RecommendIamRoles request.

### RecommendIamRolesRequest

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;parent&quot;: string,&quot;prompt&quot;: {object (Prompt)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`parent`

`string`

Required. The project on which the user wants to grant the suggested roles. Use one of the following formats:

  - `projects/{project_id}`
  - `projects/{project_number}`

`prompt`

` object ( Prompt  ` )

Required. The user's prompt.

### Prompt

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{
  &quot;userInstructions&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`userInstructions`

`string`

Required. The user's prompt. For example, "Suggest a role that lets me view storage buckets."

## Output Schema

Response to the recommendIamRoles method.

### RecommendIamRolesResponse

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;summary&quot;: string,&quot;recommendations&quot;: [{object (Recommendation)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`summary`

`string`

A summary of the reasoning for the suggested roles. If no role suggestions are provided, this field displays the reasoning for no suggestions.

`recommendations[]`

` object ( Recommendation  ` )

A list of the suggested roles that are considered appropriate based on the user's prompt.

### Recommendation

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;intro&quot;: string,&quot;roles&quot;: [{object (Role)}],&quot;detailedReasoning&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`intro`

`string`

Short intro text displayed before the role recommendations.

`roles[]`

` object ( Role  ` )

A list of the suggested roles.

`detailedReasoning`

`string`

Detailed reasoning for why the suggested roles are considered appropriate.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;roleType&quot;: enum (RoleType),&quot;grantableScopes&quot;: [string]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

The role name. For example, roles/storage.admin.

`roleType`

` enum ( RoleType  ` )

The type of role suggested. For example, a predefined role or a custom role.

`grantableScopes[]`

`string`

The list of scopes where the role can be granted. For example, a role can be granted at the project-, folder-, or organization-level.

### RoleType

RoleType defines a list of role types. Current supported values include predefined roles and custom roles.

Enums

`ROLE_TYPE_UNSPECIFIED`

Default value.

`ROLE_TYPE_PREDEFINED`

Predefined roles.

`ROLE_TYPE_CUSTOM`

Custom roles defined by the user.

### Tool Annotations

[Tool annotations](https://modelcontextprotocol.io/specification/latest/schema#toolannotations) are sent to MCP clients to describe the basic risk of a given tool. Most clients treat these hints as untrusted, but they can be used to decide when a confirmation prompt might be sent to a user.

Along with the title string, the following boolean hints are defined as follows:

  - `readOnlyHint` : If true, the tool doesn't modify its environment. Default: false.
  - `destructiveHint` : If true, then the tool can perform destructive actions. If false, then the tool can only perform additive actions. Default: true.
  - `idempotentHint` : If true, then calling the tool repeatedly with the same arguments will have no additional effect on its environment. Default: false.
  - `openWorldHint` : If true, then the tool can interact with an 'open world' of external entities. If false, then the tool can only interact with internal entities. For example, a web search tool would be open world, while a memory tool would not be open world.

Destructive Hint: ❌ | Idempotent Hint: ✅ | Read Only Hint: ✅ | Open World Hint: ❌
