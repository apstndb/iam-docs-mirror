---
name: documents/docs.cloud.google.com/iam/docs/reference/mcp/tools_list/get_deny_policy
uri: https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/get_deny_policy
title: 'MCP Tools Reference: iam.googleapis.com'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Tool: `get_deny_policy`

Gets the details, metadata, and rules of a deny policy attached to a Google Cloud project. Organizations and folders are *not* supported.

Use this tool to inspect the denied principal sets, exempted principal sets, and denied permissions of a specific deny policy.

This tool requires the `name` parameter, which is the URL-encoded resource name of the deny policy to retrieve. Only projects are supported. The format is `policies/URL_ENCODED_ATTACHMENT_POINT/denypolicies/POLICY_ID` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-deny-policy` .

This tool returns the deny policy representation including its rules, display name, and etag.

The following code sample shows how to use `curl` to call the `get_deny_policy` MCP tool.

**Curl Request**

```
curl --location 'https://iam.googleapis.com/mcp' \
--header 'content-type: application/json' \
--header 'accept: application/json, text/event-stream' \
--data '{
  "method": "tools/call",
  "params": {
    "name": "get_deny_policy",
    "arguments": {
      // Provide these details according to the MCP tool specification.
    }
  },
  "jsonrpc": "2.0",
  "id": 1
}'
```

## Input Schema

Request message for `GetPolicy` .

### GetPolicyRequest

**JSON representation**

```
{
  "name": string
}
```

| Fields |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|--------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name` | `string` Required. The resource name of the policy to retrieve. Format: `policies/{attachment_point}/denypolicies/{policy_id}` Use the URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-policy` . For organizations and folders, use the numeric ID in the full resource name. For projects, you can use the alphanumeric or the numeric ID. |

## Output Schema

Data for an IAM policy.

### Policy

**JSON representation**

```
{
  "name": string,
  "uid": string,
  "kind": string,
  "displayName": string,
  "annotations": {
    string: string,
    ...
  },
  "etag": string,
  "createTime": string,
  "updateTime": string,
  "deleteTime": string,
  "rules": [
    {
      object (PolicyRule)
    }
  ]
}
```

| Fields        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`        | `string` Immutable. The resource name of the `Policy` , which must be unique. Format: `policies/{attachment_point}/denypolicies/{policy_id}` The attachment point is identified by its URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-deny-policy` . For organizations and folders, use the numeric ID in the full resource name. For projects, requests can use the alphanumeric or the numeric ID. Responses always contain the numeric ID. |
| `uid`         | `string` Immutable. The globally unique ID of the `Policy` . Assigned automatically when the `Policy` is created.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `kind`        | `string` Output only. The kind of the `Policy` . Always contains the value `DenyPolicy` .                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `displayName` | `string` A user-specified description of the `Policy` . This value can be up to 63 characters.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| `annotations` | `map (key: string, value: string)` A key-value map to store arbitrary metadata for the `Policy` . Keys can be up to 63 characters. Values can be up to 255 characters. An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .                                                                                                                                                                                                                                                                                                                     |
| `etag`        | `string` An opaque tag that identifies the current version of the `Policy` . IAM uses this value to help manage concurrent updates, so they do not cause one update to be overwritten by another. If this field is present in a [`CreatePolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/create_deny_policy#Input.Schema.CreatePolicyRequest) , the value is ignored.                                                                                                                                                                                                             |
| `createTime`  | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. The time when the `Policy` was created. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .                                                                                                                                                                                       |
| `updateTime`  | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. The time when the `Policy` was last updated. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .                                                                                                                                                                                  |
| `deleteTime`  | `string ( `[`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp)` format)` Output only. The time when the `Policy` was deleted. Empty if the policy is not deleted. Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .                                                                                                                                                   |
| `rules[]`     | `object ( `[`PolicyRule`](https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_deny_policies#Output.Schema.PolicyRule)` )` A list of rules that specify the behavior of the `Policy` . All of the rules should be of the `kind` specified in the `Policy` .                                                                                                                                                                                                                                                                                                                                      |

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

### PolicyRule

**JSON representation**

```
{
  "description": string,

  // Union field kind can be only one of the following:
  "denyRule": {
    object (DenyRule)
  }
  // End of list of possible types for union field kind.
}
```

| Fields                                                        |                                                                                                                                                                  |
|---------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `description`                                                 | `string` A user-specified description of the rule. This value can be up to 256 characters.                                                                       |
| Union field `kind` . `kind` can be only one of the following: |                                                                                                                                                                  |
| `denyRule`                                                    | `object ( `[`DenyRule`](https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_deny_policies#Output.Schema.DenyRule)` )` A rule for a deny policy. |
|                                                               |                                                                                                                                                                  |

### DenyRule

**JSON representation**

```
{
  "deniedPrincipals": [
    string
  ],
  "exceptionPrincipals": [
    string
  ],
  "deniedPermissions": [
    string
  ],
  "exceptionPermissions": [
    string
  ],
  "denialCondition": {
    object (Expr)
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
<td><code>deniedPrincipals[]</code></td>
<td><p><code>string</code></p>
<p>The identities that are prevented from using one or more permissions on Google Cloud resources. This field can contain the following values:</p>
<ul>
<li><p><code>principal://goog/subject/{email_id}</code> : A specific Google Account. Includes Gmail, Cloud Identity, and Google Workspace user accounts. For example, <code>principal://goog/subject/alice@example.com</code> .</p></li>
<li><p><code>principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}</code> : A Google Cloud service account. For example, <code>principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com</code> .</p></li>
<li><p><code>principalSet://goog/group/{group_id}</code> : A Google group. For example, <code>principalSet://goog/group/admins@example.com</code> .</p></li>
<li><p><code>principalSet://goog/public:all</code> : A special identifier that represents any principal that is on the internet, even if they do not have a Google Account or are not logged in.</p></li>
<li><p><code>principalSet://goog/cloudIdentityCustomerId/{customer_id}</code> : All of the principals associated with the specified Google Workspace or Cloud Identity customer ID. For example, <code>principalSet://goog/cloudIdentityCustomerId/C01Abc35</code> .</p></li>
<li><p><code>principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}</code> : A single identity in a workforce identity pool.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/group/{group_id}</code> : All workforce identities in a group.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/attribute.{attribute_name}/{attribute_value}</code> : All workforce identities with a specific attribute value.</p></li>
<li><p><code>principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/*</code> : All identities in a workforce identity pool.</p></li>
<li><p><code>principal://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/subject/{subject_attribute_value}</code> : A single identity in a workload identity pool.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/group/{group_id}</code> : A workload identity pool group.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/attribute.{attribute_name}/{attribute_value}</code> : All identities in a workload identity pool with a certain attribute.</p></li>
<li><p><code>principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/*</code> : All identities in a workload identity pool.</p></li>
<li><p><code>principalSet://cloudresourcemanager.googleapis.com/[projects|folders|organizations]/{project_number|folder_number|org_number}/type/ServiceAccount</code> : All service accounts grouped under a resource (project, folder, or organization).</p></li>
<li><p><code>principalSet://cloudresourcemanager.googleapis.com/[projects|folders|organizations]/{project_number|folder_number|org_number}/type/ServiceAgent</code> : All service agents grouped under a resource (project, folder, or organization).</p></li>
<li><p><code>deleted:principal://goog/subject/{email_id}?uid={uid}</code> : A specific Google Account that was deleted recently. For example, <code>deleted:principal://goog/subject/alice@example.com?uid=1234567890</code> . If the Google Account is recovered, this identifier reverts to the standard identifier for a Google Account.</p></li>
<li><p><code>deleted:principalSet://goog/group/{group_id}?uid={uid}</code> : A Google group that was deleted recently. For example, <code>deleted:principalSet://goog/group/admins@example.com?uid=1234567890</code> . If the Google group is restored, this identifier reverts to the standard identifier for a Google group.</p></li>
<li><p><code>deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}?uid={uid}</code> : A Google Cloud service account that was deleted recently. For example, <code>deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com?uid=1234567890</code> . If the service account is undeleted, this identifier reverts to the standard identifier for a service account.</p></li>
<li><p><code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}</code> : Deleted single identity in a workforce identity pool. For example, <code>deleted:principal://iam.googleapis.com/locations/global/workforcePools/my-pool-id/subject/my-subject-attribute-value</code> .</p></li>
</ul></td>
</tr>
<tr class="even">
<td><code>exceptionPrincipals[]</code></td>
<td><p><code>string</code></p>
<p>The identities that are excluded from the deny rule, even if they are listed in the <code>denied_principals</code> . For example, you could add a Google group to the <code>denied_principals</code> , then exclude specific users who belong to that group.</p>
<p>This field can contain the same values as the <code>denied_principals</code> field, excluding <code>principalSet://goog/public:all</code> , which represents all users on the internet.</p></td>
</tr>
<tr class="odd">
<td><code>deniedPermissions[]</code></td>
<td><p><code>string</code></p>
<p>The permissions that are explicitly denied by this rule. Each permission uses the format <code>{service_fqdn}/{resource}.{verb}</code> , where <code>{service_fqdn}</code> is the fully qualified domain name for the service. For example, <code>iam.googleapis.com/roles.list</code> .</p></td>
</tr>
<tr class="even">
<td><code>exceptionPermissions[]</code></td>
<td><p><code>string</code></p>
<p>Specifies the permissions that this rule excludes from the set of denied permissions given by <code>denied_permissions</code> . If a permission appears in <code>denied_permissions</code> <em>and</em> in <code>exception_permissions</code> then it will <em>not</em> be denied.</p>
<p>The excluded permissions can be specified using the same syntax as <code>denied_permissions</code> .</p></td>
</tr>
<tr class="odd">
<td><code>denialCondition</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/mcp/tools_list/list_deny_policies#Output.Schema.Expr"><code>Expr</code></a><code> )</code></p>
<p>The condition that determines whether this deny rule applies to a request. If the condition expression evaluates to <code>true</code> , then the deny rule is applied; otherwise, the deny rule is not applied.</p>
<p>Each deny rule is evaluated independently. If this deny rule does not apply to a request, other deny rules might still apply.</p>
<p>The condition can use CEL functions that evaluate <a href="https://cloud.google.com/iam/help/conditions/resource-tags">resource tags</a> . Other functions and operators are not supported.</p></td>
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

### Tool Annotations

[Tool annotations](https://modelcontextprotocol.io/specification/latest/schema#toolannotations) are sent to MCP clients to describe the basic risk of a given tool. Most clients treat these hints as untrusted, but they can be used to decide when a confirmation prompt might be sent to a user.

Along with the title string, the following boolean hints are defined as follows:

- `readOnlyHint` : If true, the tool doesn't modify its environment. Default: false.
- `destructiveHint` : If true, then the tool can perform destructive actions. If false, then the tool can only perform additive actions. Default: true.
- `idempotentHint` : If true, then calling the tool repeatedly with the same arguments will have no additional effect on its environment. Default: false.
- `openWorldHint` : If true, then the tool can interact with an 'open world' of external entities. If false, then the tool can only interact with internal entities. For example, a web search tool would be open world, while a memory tool would not be open world.

Destructive Hint: ❌ \| Idempotent Hint: ✅ \| Read Only Hint: ✅ \| Open World Hint: ❌
