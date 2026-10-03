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

**Curl Request**

```
curl --location 'https://policyassist.googleapis.com/mcp' \
--header 'content-type: application/json' \
--header 'accept: application/json, text/event-stream' \
--data '{
  "method": "tools/call",
  "params": {
    "name": "recommend_iam_roles",
    "arguments": {
      // provide these details according to the tool's MCP specification
    }
  },
  "jsonrpc": "2.0",
  "id": 1
}'
```

## Input Schema

RecommendIamRoles request.

### RecommendIamRolesRequest

**JSON representation**

```
{
  "parent": string,
  "prompt": {
    object (Prompt)
  }
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
<p>Required. The project on which the user wants to grant the suggested roles. Use one of the following formats:</p>
<ul>
<li><code>projects/{project_id}</code></li>
<li><code>projects/{project_number}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>prompt</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/mcp/tools_list/recommend_iam_roles#Input.Schema.Prompt"><code>Prompt</code></a><code> )</code></p>
<p>Required. The user's prompt.</p></td>
</tr>
</tbody>
</table>

### Prompt

**JSON representation**

```
{
  "userInstructions": string
}
```

| Fields             |                                                                                                        |
|--------------------|--------------------------------------------------------------------------------------------------------|
| `userInstructions` | `string` Required. The user's prompt. For example, "Suggest a role that lets me view storage buckets." |

## Output Schema

Response to the recommendIamRoles method.

### RecommendIamRolesResponse

**JSON representation**

```
{
  "summary": string,
  "recommendations": [
    {
      object (Recommendation)
    }
  ]
}
```

| Fields              |                                                                                                                                                                                                                                                                            |
|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `summary`           | `string` A summary of the reasoning for the suggested roles. If no role suggestions are provided, this field displays the reasoning for no suggestions.                                                                                                                    |
| `recommendations[]` | `object ( `[`Recommendation`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/mcp/tools_list/recommend_iam_roles#Output.Schema.Recommendation)` )` A list of the suggested roles that are considered appropriate based on the user's prompt. |

### Recommendation

**JSON representation**

```
{
  "intro": string,
  "roles": [
    {
      object (Role)
    }
  ],
  "detailedReasoning": string
}
```

| Fields              |                                                                                                                                                                                             |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `intro`             | `string` Short intro text displayed before the role recommendations.                                                                                                                        |
| `roles[]`           | `object ( `[`Role`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/mcp/tools_list/recommend_iam_roles#Output.Schema.Role)` )` A list of the suggested roles. |
| `detailedReasoning` | `string` Detailed reasoning for why the suggested roles are considered appropriate.                                                                                                         |

### Role

**JSON representation**

```
{
  "name": string,
  "roleType": enum (RoleType),
  "grantableScopes": [
    string
  ]
}
```

| Fields              |                                                                                                                                                                                                                                                 |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`              | `string` The role name. For example, roles/storage.admin.                                                                                                                                                                                       |
| `roleType`          | `enum ( `[`RoleType`](https://docs.cloud.google.com/policy-intelligence/docs/reference/policyassist/mcp/tools_list/recommend_iam_roles#Output.Schema.RoleType)` )` The type of role suggested. For example, a predefined role or a custom role. |
| `grantableScopes[]` | `string` The list of scopes where the role can be granted. For example, a role can be granted at the project-, folder-, or organization-level.                                                                                                  |

### RoleType

RoleType defines a list of role types. Current supported values include predefined roles and custom roles.

| Enums                   |                                   |
|-------------------------|-----------------------------------|
| `ROLE_TYPE_UNSPECIFIED` | Default value.                    |
| `ROLE_TYPE_PREDEFINED`  | Predefined roles.                 |
| `ROLE_TYPE_CUSTOM`      | Custom roles defined by the user. |

### Tool Annotations

[Tool annotations](https://modelcontextprotocol.io/specification/latest/schema#toolannotations) are sent to MCP clients to describe the basic risk of a given tool. Most clients treat these hints as untrusted, but they can be used to decide when a confirmation prompt might be sent to a user.

Along with the title string, the following boolean hints are defined as follows:

- `readOnlyHint` : If true, the tool doesn't modify its environment. Default: false.
- `destructiveHint` : If true, then the tool can perform destructive actions. If false, then the tool can only perform additive actions. Default: true.
- `idempotentHint` : If true, then calling the tool repeatedly with the same arguments will have no additional effect on its environment. Default: false.
- `openWorldHint` : If true, then the tool can interact with an 'open world' of external entities. If false, then the tool can only interact with internal entities. For example, a web search tool would be open world, while a memory tool would not be open world.

Destructive Hint: ❌ \| Idempotent Hint: ✅ \| Read Only Hint: ✅ \| Open World Hint: ❌
