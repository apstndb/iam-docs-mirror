---
name: documents/docs.cloud.google.com/iam/docs/reference/mcp/tools_list/get_access_policy_binding
uri: https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/get_access_policy_binding
title: 'MCP Tools Reference: iam.googleapis.com'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Tool: `get_access_policy_binding`

Gets the details and configuration of a Unified Access Policy binding. Only supports Unified Access Policy bindings that are parented by a project.

Use this tool to inspect a binding's target resource, applied policy, and conditions.

This tool requires the `name` parameter, which is the resource name of the policy binding to retrieve. Only projects are supported. The format is `projects/PROJECT_ID/locations/LOCATION/policyBindings/BINDING_ID` .

This tool returns the details and configuration of the specified binding.

The following code sample shows how to use `curl` to call the `get_access_policy_binding` MCP tool.

**Curl Request**

```
curl --location 'https://iam.googleapis.com/mcp' \
--header 'content-type: application/json' \
--header 'accept: application/json, text/event-stream' \
--data '{
  "method": "tools/call",
  "params": {
    "name": "get_access_policy_binding",
    "arguments": {
      // Provide these details according to the MCP tool specification.
    }
  },
  "jsonrpc": "2.0",
  "id": 1
}'
```

## Input Schema

Request message for GetPolicyBinding method.

### GetPolicyBindingRequest

**JSON representation**

```
{
  "name": string
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
<p>Required. The name of the policy binding to retrieve.</p>
<p>Format:</p>
<ul>
<li><code>projects/{project_id}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
<li><code>projects/{project_number}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
<li><code>folders/{folder_id}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
<li><code>organizations/{organization_id}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Output Schema

IAM policy binding resource.

### PolicyBinding

**JSON representation**

```
{
  "name": string,
  "uid": string,
  "etag": string,
  "displayName": string,
  "annotations": {
    string: string,
    ...
  },
  "target": {
    object (Target)
  },
  "policyKind": enum (PolicyKind),
  "policy": string,
  "policyUid": string,
  "condition": {
    object (Expr)
  },
  "createTime": string,
  "updateTime": string
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
<p>Identifier. The name of the policy binding, in the format <code>{binding_parent/locations/{location}/policyBindings/{policy_binding_id}</code> . The binding parent is the closest Resource Manager resource (project, folder, or organization) to the binding target.</p>
<p>Format:</p>
<ul>
<li><code>projects/{project_id}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
<li><code>projects/{project_number}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
<li><code>folders/{folder_id}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
<li><code>organizations/{organization_id}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>uid</code></td>
<td><p><code>string</code></p>
<p>Output only. The globally unique ID of the policy binding. Assigned when the policy binding is created.</p></td>
</tr>
<tr class="odd">
<td><code>etag</code></td>
<td><p><code>string</code></p>
<p>Optional. The etag for the policy binding. If this is provided on update, it must match the server's etag.</p></td>
</tr>
<tr class="even">
<td><code>displayName</code></td>
<td><p><code>string</code></p>
<p>Optional. The description of the policy binding. Must be less than or equal to 63 characters.</p></td>
</tr>
<tr class="odd">
<td><code>annotations</code></td>
<td><p><code>map (key: string, value: string)</code></p>
<p>Optional. User-defined annotations. See <a href="https://google.aip.dev/148#annotations">https://google.aip.dev/148#annotations</a> for more details such as format and size limitations</p>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="even">
<td><code>target</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_access_policy_bindings#Output.Schema.Target"><code>Target</code></a><code> )</code></p>
<p>Required. Immutable. The full resource name of the resource to which the policy will be bound. Immutable once set.</p></td>
</tr>
<tr class="odd">
<td><code>policyKind</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_access_policy_bindings#Output.Schema.PolicyKind"><code>PolicyKind</code></a><code> )</code></p>
<p>Immutable. The kind of the policy to attach in this binding. This field must be one of the following:</p>
<ul>
<li>Left empty (will be automatically set to the policy kind)</li>
<li>The input policy kind</li>
</ul></td>
</tr>
<tr class="even">
<td><code>policy</code></td>
<td><p><code>string</code></p>
<p>Required. Immutable. The resource name of the policy to be bound. The binding parent and policy must belong to the same organization.</p></td>
</tr>
<tr class="odd">
<td><code>policyUid</code></td>
<td><p><code>string</code></p>
<p>Output only. The globally unique ID of the policy to be bound.</p></td>
</tr>
<tr class="even">
<td><code>condition</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_deny_policies#Output.Schema.Expr"><code>Expr</code></a><code> )</code></p>
<p>Optional. The condition to apply to the policy binding. When set, the <code>expression</code> field in the <code>Expr</code> must include from 1 to 10 subexpressions, joined by the "||"(Logical OR), "&amp;&amp;"(Logical AND) or "!"(Logical NOT) operators and cannot contain more than 250 characters.</p>
<p>The condition is currently only supported when bound to policies of kind principal access boundary.</p>
<p>When the bound policy is a principal access boundary policy, the only supported attributes in any subexpression are <code>principal.type</code> and <code>principal.subject</code> . An example expression is: "principal.type == 'iam.googleapis.com/ServiceAccount'" or "principal.subject == 'bob@example.com'".</p>
<p>Allowed operations for <code>principal.subject</code> :</p>
<ul>
<li><code>principal.subject == &lt;principal subject string&gt;</code></li>
<li><code>principal.subject != &lt;principal subject string&gt;</code></li>
<li><code>principal.subject in [&lt;list of principal subjects&gt;]</code></li>
<li><code>principal.subject.startsWith(&lt;string&gt;)</code></li>
<li><code>principal.subject.endsWith(&lt;string&gt;)</code></li>
</ul>
<p>Allowed operations for <code>principal.type</code> :</p>
<ul>
<li><code>principal.type == &lt;principal type string&gt;</code></li>
<li><code>principal.type != &lt;principal type string&gt;</code></li>
<li><code>principal.type in [&lt;list of principal types&gt;]</code></li>
</ul>
<p>Supported principal types are workspace, workforce pool, workload pool, service account, and agent identity. Allowed string must be one of:</p>
<ul>
<li><code>iam.googleapis.com/WorkspaceIdentity</code></li>
<li><code>iam.googleapis.com/WorkforcePoolIdentity</code></li>
<li><code>iam.googleapis.com/WorkloadPoolIdentity</code></li>
<li><code>iam.googleapis.com/ServiceAccount</code></li>
<li><code>iam.googleapis.com/AgentPoolIdentity</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><code>createTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The time when the policy binding was created.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="even">
<td><code>updateTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The time when the policy binding was most recently updated.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
</tbody>
</table>

### AnnotationsEntry

**JSON representation**

```
{
  "key": string,
  "value": string
}
```

| Fields  |          |
|---------|----------|
| `key`   | `string` |
| `value` | `string` |

### Target

**JSON representation**

```
{

  // Union field target can be only one of the following:
  "principalSet": string,
  "resource": string
  // End of list of possible types for union field target.
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
<td>Union field <code>target</code> . The different types of targets that can be bound to a policy. <code>target</code> can be only one of the following:</td>
<td></td>
</tr>
<tr class="even">
<td><code>principalSet</code></td>
<td><p><code>string</code></p>
<p>Immutable. The full resource name that's used for principal access boundary policy bindings. The principal set must be directly parented by the policy binding's parent or same as the parent if the target is a project, folder, or organization.</p>
<p>Examples:</p>
<ul>
<li>For bindings parented by an organization:
<ul>
<li>Organization: <code>//cloudresourcemanager.googleapis.com/organizations/ORGANIZATION_ID</code></li>
<li>Workforce Identity: <code>//iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID</code></li>
<li>Workspace Identity: <code>//iam.googleapis.com/locations/global/workspace/WORKSPACE_ID</code></li>
</ul></li>
<li>For bindings parented by a folder:
<ul>
<li>Folder: <code>//cloudresourcemanager.googleapis.com/folders/FOLDER_ID</code></li>
</ul></li>
<li>For bindings parented by a project:
<ul>
<li>Project:
<ul>
<li><code>//cloudresourcemanager.googleapis.com/projects/PROJECT_NUMBER</code></li>
<li><code>//cloudresourcemanager.googleapis.com/projects/PROJECT_ID</code></li>
</ul></li>
<li>Workload Identity Pool: <code>//iam.googleapis.com/projects/PROJECT_NUMBER/locations/LOCATION/workloadIdentityPools/WORKLOAD_POOL_ID</code></li>
</ul></li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resource</code></td>
<td><p><code>string</code></p>
<p>Immutable. The full resource name that's used for Unified Access Policy bindings.</p>
<p>Examples:</p>
<ul>
<li>Organization: <code>//cloudresourcemanager.googleapis.com/organizations/ORGANIZATION_ID</code></li>
<li>Folder: <code>//cloudresourcemanager.googleapis.com/folders/FOLDER_ID</code></li>
<li>Project:
<ul>
<li><code>//cloudresourcemanager.googleapis.com/projects/PROJECT_NUMBER</code></li>
<li><code>//cloudresourcemanager.googleapis.com/projects/PROJECT_ID</code></li>
</ul></li>
</ul></td>
</tr>
<tr class="even">
<td></td>
<td></td>
</tr>
</tbody>
</table>

### Expr

**JSON representation**

```
{
  "expression": string,
  "title": string,
  "description": string,
  "location": string
}
```

| Fields        |                                                                                                                                                            |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `expression`  | `string` Textual representation of an expression in Common Expression Language syntax.                                                                     |
| `title`       | `string` Optional. Title for the expression, i.e. a short string describing its purpose. This can be used e.g. in UIs which allow to enter the expression. |
| `description` | `string` Optional. Description of the expression. This is a longer text which describes the expression, e.g. when hovered over it in a UI.                 |
| `location`    | `string` Optional. String indicating the location of the expression for error reporting, e.g. a file name and a position in the file.                      |

### Timestamp

**JSON representation**

```
{
  "seconds": string,
  "nanos": integer
}
```

| Fields    |                                                                                                                                                                                                                                                                                                                      |
|-----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `seconds` | `string ( `[`int64`](https://developers.google.com/discovery/v1/type-format)` format)` Represents seconds of UTC time since Unix epoch 1970-01-01T00:00:00Z. Must be between -62135596800 and 253402300799 inclusive (which corresponds to 0001-01-01T00:00:00Z to 9999-12-31T23:59:59Z).                            |
| `nanos`   | `integer` Non-negative fractions of a second at nanosecond resolution. This field is the nanosecond portion of the duration, not an alternative to seconds. Negative second values with fractions must still have non-negative nanos values that count forward in time. Must be between 0 and 999,999,999 inclusive. |

### PolicyKind

The different policy kinds supported in this binding.

| Enums                       |                                            |
|-----------------------------|--------------------------------------------|
| `POLICY_KIND_UNSPECIFIED`   | Unspecified policy kind; Not a valid state |
| `PRINCIPAL_ACCESS_BOUNDARY` | Principal access boundary policy kind      |
| `ACCESS`                    | Unified Access Policy kind.                |

### Tool Annotations

[Tool annotations](https://modelcontextprotocol.io/specification/latest/schema#toolannotations) are sent to MCP clients to describe the basic risk of a given tool. Most clients treat these hints as untrusted, but they can be used to decide when a confirmation prompt might be sent to a user.

Along with the title string, the following boolean hints are defined as follows:

- `readOnlyHint` : If true, the tool doesn't modify its environment. Default: false.
- `destructiveHint` : If true, then the tool can perform destructive actions. If false, then the tool can only perform additive actions. Default: true.
- `idempotentHint` : If true, then calling the tool repeatedly with the same arguments will have no additional effect on its environment. Default: false.
- `openWorldHint` : If true, then the tool can interact with an 'open world' of external entities. If false, then the tool can only interact with internal entities. For example, a web search tool would be open world, while a memory tool would not be open world.

Destructive Hint: ❌ \| Idempotent Hint: ✅ \| Read Only Hint: ✅ \| Open World Hint: ❌
