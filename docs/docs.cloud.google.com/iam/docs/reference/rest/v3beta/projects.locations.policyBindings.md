---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings
title: 'REST Resource: projects.locations.policyBindings'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: PolicyBinding](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings#PolicyBinding)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings#PolicyBinding.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.policyBindings#METHODS_SUMMARY)

## Resource: PolicyBinding

IAM policy binding resource.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;uid&quot;: string,&quot;etag&quot;: string,&quot;displayName&quot;: string,&quot;annotations&quot;: {string: string,...},&quot;target&quot;: {object (Target)},&quot;policyKind&quot;: enum (PolicyKind),&quot;policy&quot;: string,&quot;policyUid&quot;: string,&quot;condition&quot;: {object (Expr)},&quot;createTime&quot;: string,&quot;updateTime&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Identifier. The name of the policy binding, in the format `{binding_parent/locations/{location}/policyBindings/{policyBindingId}` . The binding parent is the closest Resource Manager resource (project, folder, or organization) to the binding target.

Format:

  - `projects/{projectId}/locations/{location}/policyBindings/{policyBindingId}`
  - `projects/{projectNumber}/locations/{location}/policyBindings/{policyBindingId}`
  - `folders/{folderId}/locations/{location}/policyBindings/{policyBindingId}`
  - `organizations/{organizationId}/locations/{location}/policyBindings/{policyBindingId}`

`uid`

`string`

Output only. The globally unique ID of the policy binding. Assigned when the policy binding is created.

`etag`

`string`

Optional. The etag for the policy binding. If this is provided on update, it must match the server's etag.

`displayName`

`string`

Optional. The description of the policy binding. Must be less than or equal to 63 characters.

`annotations`

`map (key: string, value: string)`

Optional. User-defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`target`

` object ( Target  ` )

Required. Immutable. The full resource name of the resource to which the policy will be bound. Immutable once set.

`policyKind`

` enum ( PolicyKind  ` )

Immutable. The kind of the policy to attach in this binding. This field must be one of the following:

  - Left empty (will be automatically set to the policy kind)
  - The input policy kind

`policy`

`string`

Required. Immutable. The resource name of the policy to be bound. The binding parent and policy must belong to the same organization.

`policyUid`

`string`

Output only. The globally unique ID of the policy to be bound.

`condition`

` object ( Expr  ` )

Optional. The condition to apply to the policy binding. When set, the `expression` field in the `Expr` must include from 1 to 10 subexpressions, joined by the "||"(Logical OR), "&&"(Logical AND) or "\!"(Logical NOT) operators and cannot contain more than 250 characters.

The condition is currently only supported when bound to policies of kind principal access boundary.

When the bound policy is a principal access boundary policy, the only supported attributes in any subexpression are `principal.type` and `principal.subject` . An example expression is: "principal.type == 'iam.googleapis.com/ServiceAccount'" or "principal.subject == 'bob@example.com'".

Allowed operations for `principal.subject` :

  - `principal.subject == <principal subject string>`
  - `principal.subject != <principal subject string>`
  - `principal.subject in [<list of principal subjects>]`
  - `principal.subject.startsWith(<string>)`
  - `principal.subject.endsWith(<string>)`

Allowed operations for `principal.type` :

  - `principal.type == <principal type string>`
  - `principal.type != <principal type string>`
  - `principal.type in [<list of principal types>]`

Supported principal types are workspace, workforce pool, workload pool, service account, and agent identity. Allowed string must be one of:

  - `iam.googleapis.com/WorkspaceIdentity`
  - `iam.googleapis.com/WorkforcePoolIdentity`
  - `iam.googleapis.com/WorkloadPoolIdentity`
  - `iam.googleapis.com/ServiceAccount`
  - `iam.googleapis.com/AgentPoolIdentity` (available in Preview)

`createTime`

` string ( Timestamp  ` format)

Output only. The time when the policy binding was created.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`updateTime`

` string ( Timestamp  ` format)

Output only. The time when the policy binding was most recently updated.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

## Methods

### `            create           `

Creates a policy binding and returns a long-running operation.

### `            delete           `

Deletes a policy binding and returns a long-running operation.

### `            get           `

Gets a policy binding.

### `            list           `

Lists policy bindings.

### `            patch           `

Updates a policy binding and returns a long-running operation.

### `            searchTargetPolicyBindings           `

Search policy bindings by target.
