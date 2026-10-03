---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings
title: 'REST Resource: organizations.locations.policyBindings'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: PolicyBinding](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings#PolicyBinding)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings#PolicyBinding.SCHEMA_REPRESENTATION)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings#METHODS_SUMMARY)

## Resource: PolicyBinding

IAM policy binding resource.

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
<p>Identifier. The name of the policy binding, in the format <code>{binding_parent/locations/{location}/policyBindings/{policyBindingId}</code> . The binding parent is the closest Resource Manager resource (project, folder, or organization) to the binding target.</p>
<p>Format:</p>
<ul>
<li><code>projects/{projectId}/locations/{location}/policyBindings/{policyBindingId}</code></li>
<li><code>projects/{projectNumber}/locations/{location}/policyBindings/{policyBindingId}</code></li>
<li><code>folders/{folderId}/locations/{location}/policyBindings/{policyBindingId}</code></li>
<li><code>organizations/{organizationId}/locations/{location}/policyBindings/{policyBindingId}</code></li>
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
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings#PolicyBinding.Target"><code>Target</code></a><code> )</code></p>
<p>Required. Immutable. The full resource name of the resource to which the policy will be bound. Immutable once set.</p></td>
</tr>
<tr class="odd">
<td><code>policyKind</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings#PolicyBinding.PolicyKind"><code>PolicyKind</code></a><code> )</code></p>
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
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/Shared.Types/Expr"><code>Expr</code></a><code> )</code></p>
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

| Methods                                                                                                                                                    |                                                                |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings/create)                                         | Creates a policy binding and returns a long-running operation. |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings/delete)                                         | Deletes a policy binding and returns a long-running operation. |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings/get)                                               | Gets a policy binding.                                         |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings/list)                                             | Lists policy bindings.                                         |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings/patch)                                           | Updates a policy binding and returns a long-running operation. |
| [`searchTargetPolicyBindings`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.policyBindings/searchTargetPolicyBindings) | Search policy bindings by target.                              |
