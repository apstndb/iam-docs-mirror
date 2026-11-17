---
name: documents/docs.cloud.google.com/iam/docs/reference/mcp/tools_list/get_access_policy
uri: https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/get_access_policy
title: 'MCP Tools Reference: iam.googleapis.com'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Tool: `get_access_policy`

Gets the details, metadata, and rules of a Unified Access Policy. Only supports Unified Access Policies that are parented by a project.

Use this tool to inspect the policy rules and configuration of a specific Unified Access Policy.

This tool requires the `name` parameter, which is the resource name of the Unified Access Policy to retrieve. Only projects are supported. The format is `projects/PROJECT_ID/locations/LOCATION/accessPolicies/POLICY_ID` .

This tool returns the details and configuration of the specified Unified Access Policy, including its rules and etag.

The following code sample shows how to use `curl` to call the `get_access_policy` MCP tool.

**Curl Request**

```
curl --location 'https://iam.googleapis.com/mcp' \
--header 'content-type: application/json' \
--header 'accept: application/json, text/event-stream' \
--data '{
  "method": "tools/call",
  "params": {
    "name": "get_access_policy",
    "arguments": {
      // Provide these details according to the MCP tool specification.
    }
  },
  "jsonrpc": "2.0",
  "id": 1
}'
```

## Input Schema

Request message for GetAccessPolicy method.

### GetAccessPolicyRequest

**JSON representation**

```
{
  "name": string
}
```

| Fields |                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|--------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name` | `string` Required. The name of the Unified Access Policy to retrieve. Format: \* `projects/{project_id}/locations/{location}/accessPolicies/{unified_access_policy_id}` \* `projects/{project_number}/locations/{location}/accessPolicies/{unified_access_policy_id}` \* `folders/{folder_id}/locations/{location}/accessPolicies/{unified_access_policy_id}` \* `organizations/{organization_id}/locations/{location}/accessPolicies/{unified_access_policy_id}` |

## Output Schema

An IAM Unified Access Policy resource.

### AccessPolicy

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
  "createTime": string,
  "updateTime": string,
  "details": {
    object (AccessPolicyDetails)
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
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>Identifier. The resource name of the Unified Access Policy.</p>
<p>The following formats are supported:</p>
<ul>
<li><code>projects/{project_id}/locations/{location}/accessPolicies/{unified_access_policy_id}</code></li>
<li><code>projects/{project_number}/locations/{location}/accessPolicies/{unified_access_policy_id}</code></li>
<li><code>folders/{folder_id}/locations/{location}/accessPolicies/{unified_access_policy_id}</code></li>
<li><code>organizations/{organization_id}/locations/{location}/accessPolicies/{unified_access_policy_id}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>uid</code></td>
<td><p><code>string</code></p>
<p>Output only. The globally unique ID of the Unified Access Policy.</p></td>
</tr>
<tr class="odd">
<td><code>etag</code></td>
<td><p><code>string</code></p>
<p>Optional. The etag for the Unified Access Policy. If this is provided on update, it must match the server's etag.</p></td>
</tr>
<tr class="even">
<td><code>displayName</code></td>
<td><p><code>string</code></p>
<p>Optional. The description of the Unified Access Policy. This description can be a maximum of 63 characters.</p></td>
</tr>
<tr class="odd">
<td><code>annotations</code></td>
<td><p><code>map (key: string, value: string)</code></p>
<p>Optional. User-defined annotations. See <a href="https://google.aip.dev/148#annotations">https://google.aip.dev/148#annotations</a> for more details such as format and size limitations.</p>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="even">
<td><code>createTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The time when the Unified Access Policy was created.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="odd">
<td><code>updateTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The time when the Unified Access Policy was most recently updated.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="even">
<td><code>details</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_access_policies#Output.Schema.AccessPolicyDetails"><code>AccessPolicyDetails</code></a><code> )</code></p>
<p>Optional. The details for the Unified Access Policy.</p></td>
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

### AccessPolicyDetails

**JSON representation**

```
{
  "rules": [
    {
      object (AccessPolicyRule)
    }
  ]
}
```

| Fields    |                                                                                                                                                                                                           |
|-----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `rules[]` | `object ( `[`AccessPolicyRule`](https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_access_policies#Output.Schema.AccessPolicyRule)` )` Required. A list of Unified Access Policy rules. |

### AccessPolicyRule

**JSON representation**

```
{
  "principals": [
    string
  ],
  "excludedPrincipals": [
    string
  ],
  "operation": {
    object (Operation)
  },
  "conditions": {
    string: {
      object (Expr)
    },
    ...
  },

  // Union field _description can be only one of the following:
  "description": string
  // End of list of possible types for union field _description.

  // Union field _effect can be only one of the following:
  "effect": enum (Effect)
  // End of list of possible types for union field _effect.
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
<td><code>principals[]</code></td>
<td><p><code>string</code></p>
<p>Required. The principals to include in the rule. This field can contain the following values:</p>
<ul>
<li><p><code>principal://goog/subject/{email_id}</code> : A specific Google Account. Includes Gmail, Cloud Identity, and Google Workspace user accounts. For example, <code>principal://goog/subject/alice@example.com</code> .</p></li>
<li><p><code>principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}</code> : A Google Cloud service account. For example, <code>principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com</code> .</p></li>
<li><p><code>principalSet://goog/group/{group_id}</code> : A Google group. For example, <code>principalSet://goog/group/admins@example.com</code> .</p></li>
<li><p><code>principalSet://goog/cloudIdentityCustomerId/{customer_id}</code> : All of the principals associated with the specified Google Workspace or Cloud Identity customer ID. For example, <code>principalSet://goog/cloudIdentityCustomerId/C01Abc35</code> .</p></li>
<li><p><code>principalSet://goog/public:all</code> : A special identifier that represents any principal that is on the internet, even if they do not have a Google Account or are not logged in. This value is only supported in rules with the <code>DENY</code> effect.</p></li>
<li><p><code>principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}</code> : A single identity in a workforce identity pool.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/group/{group_id}</code> : All workforce identities in a group.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/attribute.{attribute_name}/{attribute_value}</code> : All workforce identities with a specific attribute value.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/*</code> : All identities in a workforce identity pool.</p></li>
<li><p><code>principal://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/subject/{subject_attribute_value}</code> : A single identity in a workload identity pool.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/group/{group_id}</code> : A workload identity pool group.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/attribute.{attribute_name}/{attribute_value}</code> : All identities in a workload identity pool with a certain attribute.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/*</code> : All identities in a workload identity pool.</p></li>
<li><p><code>principal://{trust_domain}/{agent_resource_path}/{agent_id}</code> : A single, specific agent identity.</p></li>
<li><p><code>principalSet://{trust_domain}/*</code> : All agent identities that belong to a particular trust domain.</p></li>
<li><p><code>principalSet://{trust_domain}/attribute.{attribute_name}/{attribute_value}</code> : All agents with a particular attribute.</p></li>
</ul>
<p>If an identifier that was previously used in a rule is soft deleted, then a <code>deleted</code> prefix is automatically added to the identifier. Users can't add new identifiers with this syntax.</p>
<ul>
<li><p><code>deleted:principal://goog/subject/{email_id}?uid={uid}</code> : A specific Google Account that was deleted recently. For example, <code>deleted:principal://goog/subject/alice@example.com?uid=1234567890</code> . If the Google Account is recovered, this identifier reverts to the standard identifier for a Google Account.</p></li>
<li><p><code>deleted:principalSet://goog/group/{group_id}?uid={uid}</code> : A Google group that was deleted recently. For example, <code>deleted:principalSet://goog/group/admins@example.com?uid=1234567890</code> . If the Google group is restored, this identifier reverts to the standard identifier for a Google group.</p></li>
<li><p><code>deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}?uid={uid}</code> : A Google Cloud service account that was deleted recently. For example, <code>deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com?uid=1234567890</code> . If the service account is undeleted, this identifier reverts to the standard identifier for a service account.</p></li>
<li><p><code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}</code> : A workforce identity that was deleted recently. For example, <code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/my-pool-id/subject/my-subject-attribute-value</code> . If the workforce identity is undeleted, this identifier reverts to the standard identifier for a workforce identity.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><code>excludedPrincipals[]</code></td>
<td><p><code>string</code></p>
<p>Optional. The principals to exclude from the rule, even if they are listed in the <code>principals</code> . For example, you could add a Google group to the <code>principals</code> , then exclude specific users who belong to that group.</p></td>
</tr>
<tr class="odd">
<td><code>operation</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_access_policies#Output.Schema.Operation"><code>Operation</code></a><code> )</code></p>
<p>Required. Attributes that are used to determine whether this rule applies to a request.</p></td>
</tr>
<tr class="even">
<td><code>conditions</code></td>
<td><p><code>map (key: string, value: object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_deny_policies#Output.Schema.Expr"><code>Expr</code></a><code> ))</code></p>
<p>Optional. The conditions that determine whether this rule applies to a request. Conditions are identified by their key, which is the FQDN of the service that they are relevant to. For example:</p>
<pre data-fenced=""><code>&quot;conditions&quot;: {
 &quot;iam.googleapis.com&quot;: {
  &quot;expression&quot;: {cel_expression}
 }
}</code></pre>
<p>Each rule is evaluated independently. If this rule does not apply to a request, other rules might still apply. The following keys are supported:</p>
<ul>
<li><p><code>eventarc.googleapis.com</code> : Can use <code>CEL</code> functions that evaluate resource fields.</p></li>
<li><p><code>iam.googleapis.com</code> : Can use <code>CEL</code> functions that evaluate <a href="https://cloud.google.com/iam/help/conditions/resource-tags">resource tags</a> and combine them using boolean and logical operators. Other functions and operators are not supported.</p></li>
<li><p><code>iap.googleapis.com</code> : Can use <code>CEL</code> functions and <a href="https://docs.cloud.google.com/gemini-enterprise-agent-platform/govern/policies/cel-attributes-uap">attributes</a> that evaluate destination resources for requests that use the <code>iap.googleapis.com/resources.egressViaIAP</code> permission.</p></li>
</ul>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="odd">
<td><p>Union field <code>_description</code> .</p>
<p><code>_description</code> can be only one of the following:</p></td>
<td></td>
</tr>
<tr class="even">
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>Optional. Customer-specified description of the rule. This description can be a maximum of 256 characters.</p></td>
</tr>
<tr class="odd">
<td></td>
<td></td>
</tr>
<tr class="even">
<td><p>Union field <code>_effect</code> .</p>
<p><code>_effect</code> can be only one of the following:</p></td>
<td></td>
</tr>
<tr class="odd">
<td><code>effect</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_access_policies#Output.Schema.Effect"><code>Effect</code></a><code> )</code></p>
<p>Required. The effect of the rule.</p></td>
</tr>
<tr class="even">
<td></td>
<td></td>
</tr>
</tbody>
</table>

### Operation

**JSON representation**

```
{
  "permissions": [
    string
  ],
  "excludedPermissions": [
    string
  ]
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
<td><code>permissions[]</code></td>
<td><p><code>string</code></p>
<p>Optional. The permissions to include in the rule. Rules with the <code>ALLOW</code> effect grant the specified permissions. Rules with the <code>DENY</code> effect deny the specified permissions.</p>
<p>The following formats are supported:</p>
<ul>
<li>Individual permissions: Individual permissions use the format <code>{service_fqdn}/{resource}.{verb}</code> , where <code>{service_fqdn}</code> is the fully qualified domain name for the service. For example, <code>eventarc.googleapis.com/messageBuses.publish</code> .</li>
<li>Roles: Only supported in rules with the <code>ALLOW</code> effect. Roles use the format <code>role:{role_name}</code> . For example, <code>role:roles/logging.logsViewer</code> . If you include a role name in a rule, then the rule includes all of the permissions in that role.</li>
<li>Permission groups: Sets of permissions, such as <code>aiplatform.googleapis.com/*.*</code> . Permission groups are sets of permissions that match a specified pattern. There are some restrictions on the permission groups you can reference and the permissions included in those groups. For more information, see <a href="https://docs.cloud.google.com/iam/help/uap/permission-groups">Permission groups</a> .</li>
</ul>
<p>An empty list doesn't match any <code>permissions</code> .</p></td>
</tr>
<tr class="even">
<td><code>excludedPermissions[]</code></td>
<td><p><code>string</code></p>
<p>Optional. Specifies the permissions to exclude from the rule. If a permission appears in <code>permissions</code> <em>and</em> in <code>excluded_permissions</code> , then it will <em>not</em> be subject to the rule effect.</p>
<p>The excluded permissions can be specified using the same syntax as <code>permissions</code> .</p></td>
</tr>
</tbody>
</table>

### ConditionsEntry

**JSON representation**

```
{
  "key": string,
  "value": {
    object (Expr)
  }
}
```

| Fields  |                                                                                                                                |
|---------|--------------------------------------------------------------------------------------------------------------------------------|
| `key`   | `string`                                                                                                                       |
| `value` | `object ( `[`Expr`](https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_deny_policies#Output.Schema.Expr)` )` |

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

### Effect

An effect to describe how the rule affects access.

| Enums                |                                                     |
|----------------------|-----------------------------------------------------|
| `EFFECT_UNSPECIFIED` | The effect is unspecified.                          |
| `DENY`               | The rule will deny access if it evaluates to true.  |
| `ALLOW`              | The rule will grant access if it evaluates to true. |

### Tool Annotations

[Tool annotations](https://modelcontextprotocol.io/specification/latest/schema#toolannotations) are sent to MCP clients to describe the basic risk of a given tool. Most clients treat these hints as untrusted, but they can be used to decide when a confirmation prompt might be sent to a user.

Along with the title string, the following boolean hints are defined as follows:

- `readOnlyHint` : If true, the tool doesn't modify its environment. Default: false.
- `destructiveHint` : If true, then the tool can perform destructive actions. If false, then the tool can only perform additive actions. Default: true.
- `idempotentHint` : If true, then calling the tool repeatedly with the same arguments will have no additional effect on its environment. Default: false.
- `openWorldHint` : If true, then the tool can interact with an 'open world' of external entities. If false, then the tool can only interact with internal entities. For example, a web search tool would be open world, while a memory tool would not be open world.

Destructive Hint: ❌ \| Idempotent Hint: ✅ \| Read Only Hint: ✅ \| Open World Hint: ❌
