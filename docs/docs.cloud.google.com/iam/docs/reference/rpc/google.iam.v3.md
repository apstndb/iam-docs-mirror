---
name: documents/docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3
uri: https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3
title: Package google.iam.v3
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

- [`AccessPolicies`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.AccessPolicies) (interface)
- [`PolicyBindings`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PolicyBindings) (interface)
- [`PrincipalAccessBoundaryPolicies`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PrincipalAccessBoundaryPolicies) (interface)
- [`CreatePolicyBindingRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.CreatePolicyBindingRequest) (message)
- [`CreatePrincipalAccessBoundaryPolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.CreatePrincipalAccessBoundaryPolicyRequest) (message)
- [`DeletePolicyBindingRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.DeletePolicyBindingRequest) (message)
- [`DeletePrincipalAccessBoundaryPolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.DeletePrincipalAccessBoundaryPolicyRequest) (message)
- [`GetPolicyBindingRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.GetPolicyBindingRequest) (message)
- [`GetPrincipalAccessBoundaryPolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.GetPrincipalAccessBoundaryPolicyRequest) (message)
- [`ListPolicyBindingsRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.ListPolicyBindingsRequest) (message)
- [`ListPolicyBindingsResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.ListPolicyBindingsResponse) (message)
- [`ListPrincipalAccessBoundaryPoliciesRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.ListPrincipalAccessBoundaryPoliciesRequest) (message)
- [`ListPrincipalAccessBoundaryPoliciesResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.ListPrincipalAccessBoundaryPoliciesResponse) (message)
- [`OperationMetadata`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.OperationMetadata) (message)
- [`PolicyBinding`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PolicyBinding) (message)
- [`PolicyBinding.PolicyKind`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PolicyBinding.PolicyKind) (enum)
- [`PolicyBinding.Target`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PolicyBinding.Target) (message)
- [`PrincipalAccessBoundaryPolicy`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PrincipalAccessBoundaryPolicy) (message)
- [`PrincipalAccessBoundaryPolicyDetails`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PrincipalAccessBoundaryPolicyDetails) (message)
- [`PrincipalAccessBoundaryPolicyRule`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PrincipalAccessBoundaryPolicyRule) (message)
- [`PrincipalAccessBoundaryPolicyRule.Effect`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PrincipalAccessBoundaryPolicyRule.Effect) (enum)
- [`SearchPrincipalAccessBoundaryPolicyBindingsRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.SearchPrincipalAccessBoundaryPolicyBindingsRequest) (message)
- [`SearchPrincipalAccessBoundaryPolicyBindingsResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.SearchPrincipalAccessBoundaryPolicyBindingsResponse) (message)
- [`SearchTargetPolicyBindingsRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.SearchTargetPolicyBindingsRequest) (message)
- [`SearchTargetPolicyBindingsResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.SearchTargetPolicyBindingsResponse) (message)
- [`UpdatePolicyBindingRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.UpdatePolicyBindingRequest) (message)
- [`UpdatePrincipalAccessBoundaryPolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.UpdatePrincipalAccessBoundaryPolicyRequest) (message)

## AccessPolicies

Manages Identity and Access Management (IAM) access policies.

## PolicyBindings

An interface for managing Identity and Access Management (IAM) policy bindings.

**CreatePolicyBinding**

`rpc CreatePolicyBinding( `[`CreatePolicyBindingRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.CreatePolicyBindingRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Creates a policy binding and returns a long-running operation. Callers will need the IAM permissions on both the policy and target. After the binding is created, the policy is applied to the target.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**DeletePolicyBinding**

`rpc DeletePolicyBinding( `[`DeletePolicyBindingRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.DeletePolicyBindingRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Deletes a policy binding and returns a long-running operation. Callers will need the IAM permissions on both the policy and target. After the binding is deleted, the policy no longer applies to the target.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**GetPolicyBinding**

`rpc GetPolicyBinding( `[`GetPolicyBindingRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.GetPolicyBindingRequest)` ) returns ( `[`PolicyBinding`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PolicyBinding)` )`

Gets a policy binding.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.policybindings.get`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**ListPolicyBindings**

`rpc ListPolicyBindings( `[`ListPolicyBindingsRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.ListPolicyBindingsRequest)` ) returns ( `[`ListPolicyBindingsResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.ListPolicyBindingsResponse)` )`

Lists policy bindings.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

- `iam.policybindings.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**SearchTargetPolicyBindings**

`rpc SearchTargetPolicyBindings( `[`SearchTargetPolicyBindingsRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.SearchTargetPolicyBindingsRequest)` ) returns ( `[`SearchTargetPolicyBindingsResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.SearchTargetPolicyBindingsResponse)` )`

Search policy bindings by target. Returns all policy binding objects bound directly to target.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**UpdatePolicyBinding**

`rpc UpdatePolicyBinding( `[`UpdatePolicyBindingRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.UpdatePolicyBindingRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Updates a policy binding and returns a long-running operation. Callers will need the IAM permissions on the policy and target in the binding to update. Target and policy are immutable and cannot be updated.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

## PrincipalAccessBoundaryPolicies

Manages Identity and Access Management (IAM) principal access boundary policies.

**CreatePrincipalAccessBoundaryPolicy**

`rpc CreatePrincipalAccessBoundaryPolicy( `[`CreatePrincipalAccessBoundaryPolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.CreatePrincipalAccessBoundaryPolicyRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Creates a principal access boundary policy, and returns a long running operation.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

- `iam.principalaccessboundarypolicies.create`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**DeletePrincipalAccessBoundaryPolicy**

`rpc DeletePrincipalAccessBoundaryPolicy( `[`DeletePrincipalAccessBoundaryPolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.DeletePrincipalAccessBoundaryPolicyRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Deletes a principal access boundary policy.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.principalaccessboundarypolicies.delete`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**GetPrincipalAccessBoundaryPolicy**

`rpc GetPrincipalAccessBoundaryPolicy( `[`GetPrincipalAccessBoundaryPolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.GetPrincipalAccessBoundaryPolicyRequest)` ) returns ( `[`PrincipalAccessBoundaryPolicy`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PrincipalAccessBoundaryPolicy)` )`

Gets a principal access boundary policy.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.principalaccessboundarypolicies.get`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**ListPrincipalAccessBoundaryPolicies**

`rpc ListPrincipalAccessBoundaryPolicies( `[`ListPrincipalAccessBoundaryPoliciesRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.ListPrincipalAccessBoundaryPoliciesRequest)` ) returns ( `[`ListPrincipalAccessBoundaryPoliciesResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.ListPrincipalAccessBoundaryPoliciesResponse)` )`

Lists principal access boundary policies.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

- `iam.principalaccessboundarypolicies.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**SearchPrincipalAccessBoundaryPolicyBindings**

`rpc SearchPrincipalAccessBoundaryPolicyBindings( `[`SearchPrincipalAccessBoundaryPolicyBindingsRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.SearchPrincipalAccessBoundaryPolicyBindingsRequest)` ) returns ( `[`SearchPrincipalAccessBoundaryPolicyBindingsResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.SearchPrincipalAccessBoundaryPolicyBindingsResponse)` )`

Returns all policy bindings that bind a specific policy if a user has searchPolicyBindings permission on that policy.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.principalaccessboundarypolicies.searchPolicyBindings`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

**UpdatePrincipalAccessBoundaryPolicy**

`rpc UpdatePrincipalAccessBoundaryPolicy( `[`UpdatePrincipalAccessBoundaryPolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.UpdatePrincipalAccessBoundaryPolicyRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Updates a principal access boundary policy.

Authorization scopes  
Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

<!-- -->

IAM Permissions  
Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.principalaccessboundarypolicies.update`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .

## CreatePolicyBindingRequest

Request message for CreatePolicyBinding method.

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
<p>Required. The parent resource where this policy binding will be created. The binding parent is the closest Resource Manager resource (project, folder or organization) to the binding target.</p>
<p>Format:</p>
<ul>
<li><code>projects/{project_id}/locations/{location}</code></li>
<li><code>projects/{project_number}/locations/{location}</code></li>
<li><code>folders/{folder_id}/locations/{location}</code></li>
<li><code>organizations/{organization_id}/locations/{location}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>policy_binding_id</code></td>
<td><p><code>string</code></p>
<p>Required. The ID to use for the policy binding, which will become the final component of the policy binding's resource name.</p>
<p>This value must start with a lowercase letter followed by up to 62 lowercase letters, numbers, hyphens, or dots. Pattern, /[a-z][a-z0-9-.]{2,62}/.</p></td>
</tr>
<tr class="odd">
<td><code>policy_binding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PolicyBinding"><code>PolicyBinding</code></a></p>
<p>Required. The policy binding to create.</p></td>
</tr>
<tr class="even">
<td><code>validate_only</code></td>
<td><p><code>bool</code></p>
<p>Optional. If set, validate the request and preview the creation, but do not actually post it.</p></td>
</tr>
</tbody>
</table>

## CreatePrincipalAccessBoundaryPolicyRequest

Request message for CreatePrincipalAccessBoundaryPolicyRequest method.

| Fields                                |                                                                                                                                                                                                                                                                                                                                  |
|---------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`                              | `string` Required. The parent resource where this principal access boundary policy will be created. Only organizations are supported. Format: `organizations/{organization_id}/locations/{location}`                                                                                                                             |
| `principal_access_boundary_policy_id` | `string` Required. The ID to use for the principal access boundary policy, which will become the final component of the principal access boundary policy's resource name. This value must start with a lowercase letter followed by up to 62 lowercase letters, numbers, hyphens, or dots. Pattern, /\[a-z\]\[a-z0-9-.\]{2,62}/. |
| `principal_access_boundary_policy`    | [`PrincipalAccessBoundaryPolicy`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PrincipalAccessBoundaryPolicy) Required. The principal access boundary policy to create.                                                                                                                      |
| `validate_only`                       | `bool` Optional. If set, validate the request and preview the creation, but do not actually post it.                                                                                                                                                                                                                             |

## DeletePolicyBindingRequest

Request message for DeletePolicyBinding method.

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
<p>Required. The name of the policy binding to delete.</p>
<p>Format:</p>
<ul>
<li><code>projects/{project_id}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
<li><code>projects/{project_number}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
<li><code>folders/{folder_id}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
<li><code>organizations/{organization_id}/locations/{location}/policyBindings/{policy_binding_id}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>etag</code></td>
<td><p><code>string</code></p>
<p>Optional. The etag of the policy binding. If this is provided, it must match the server's etag.</p></td>
</tr>
<tr class="odd">
<td><code>validate_only</code></td>
<td><p><code>bool</code></p>
<p>Optional. If set, validate the request and preview the deletion, but do not actually post it.</p></td>
</tr>
</tbody>
</table>

## DeletePrincipalAccessBoundaryPolicyRequest

Request message for DeletePrincipalAccessBoundaryPolicy method.

| Fields          |                                                                                                                                                                                                                     |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`          | `string` Required. The name of the principal access boundary policy to delete. Format: `organizations/{organization_id}/locations/{location}/principalAccessBoundaryPolicies/{principal_access_boundary_policy_id}` |
| `etag`          | `string` Optional. The etag of the principal access boundary policy. If this is provided, it must match the server's etag.                                                                                          |
| `validate_only` | `bool` Optional. If set, validate the request and preview the deletion, but do not actually post it.                                                                                                                |
| `force`         | `bool` Optional. If set to true, the request will force the deletion of the policy even if the policy is referenced in policy bindings.                                                                             |

## GetPolicyBindingRequest

Request message for GetPolicyBinding method.

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

## GetPrincipalAccessBoundaryPolicyRequest

Request message for GetPrincipalAccessBoundaryPolicy method.

| Fields |                                                                                                                                                                                                                       |
|--------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name` | `string` Required. The name of the principal access boundary policy to retrieve. Format: `organizations/{organization_id}/locations/{location}/principalAccessBoundaryPolicies/{principal_access_boundary_policy_id}` |

## ListPolicyBindingsRequest

Request message for ListPolicyBindings method.

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
<p>Required. The parent resource, which owns the collection of policy bindings.</p>
<p>Format:</p>
<ul>
<li><code>projects/{project_id}/locations/{location}</code></li>
<li><code>projects/{project_number}/locations/{location}</code></li>
<li><code>folders/{folder_id}/locations/{location}</code></li>
<li><code>organizations/{organization_id}/locations/{location}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>page_size</code></td>
<td><p><code>int32</code></p>
<p>Optional. The maximum number of policy bindings to return. The service may return fewer than this value.</p>
<p>The default value is 50. The maximum value is 1000.</p></td>
</tr>
<tr class="odd">
<td><code>page_token</code></td>
<td><p><code>string</code></p>
<p>Optional. A page token, received from a previous <code>ListPolicyBindings</code> call. Provide this to retrieve the subsequent page.</p>
<p>When paginating, all other parameters provided to <code>ListPolicyBindings</code> must match the call that provided the page token.</p></td>
</tr>
<tr class="even">
<td><code>filter</code></td>
<td><p><code>string</code></p>
<p>Optional. An expression for filtering the results of the request. Filter rules are case insensitive. Some eligible fields for filtering are the following:</p>
<ul>
<li><code>target</code></li>
<li><code>policy</code></li>
</ul>
<p>Some examples of filter queries:</p>
<ul>
<li><code>target:ex*</code> : The binding target's name starts with "ex".</li>
<li><code>target:example</code> : The binding target's name is <code>example</code> .</li>
<li><code>policy:example</code> : The binding policy's name is <code>example</code> .</li>
</ul></td>
</tr>
</tbody>
</table>

## ListPolicyBindingsResponse

Response message for ListPolicyBindings method.

| Fields              |                                                                                                                                                                  |
|---------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policy_bindings[]` | [`PolicyBinding`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PolicyBinding) The policy bindings from the specified parent. |
| `next_page_token`   | `string` Optional. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.                |

## ListPrincipalAccessBoundaryPoliciesRequest

Request message for ListPrincipalAccessBoundaryPolicies method.

| Fields       |                                                                                                                                                                                                                                                                                               |
|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`     | `string` Required. The parent resource, which owns the collection of principal access boundary policies. Format: `organizations/{organization_id}/locations/{location}`                                                                                                                       |
| `page_size`  | `int32` Optional. The maximum number of principal access boundary policies to return. The service may return fewer than this value. If unspecified, at most 50 principal access boundary policies will be returned. The maximum value is 1000; values above 1000 will be coerced to 1000.     |
| `page_token` | `string` Optional. A page token, received from a previous `ListPrincipalAccessBoundaryPolicies` call. Provide this to retrieve the subsequent page. When paginating, all other parameters provided to `ListPrincipalAccessBoundaryPolicies` must match the call that provided the page token. |

## ListPrincipalAccessBoundaryPoliciesResponse

Response message for ListPrincipalAccessBoundaryPolicies method.

| Fields                                 |                                                                                                                                                                                                                     |
|----------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `principal_access_boundary_policies[]` | [`PrincipalAccessBoundaryPolicy`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PrincipalAccessBoundaryPolicy) The principal access boundary policies from the specified parent. |
| `next_page_token`                      | `string` Optional. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.                                                                   |

## OperationMetadata

Represents the metadata of the long-running operation.

| Fields                   |                                                                                                                                                                                                                                                                                                                                                                                     |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `create_time`            | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time the operation was created.                                                                                                                                                                                                                                                  |
| `end_time`               | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time the operation finished running.                                                                                                                                                                                                                                             |
| `target`                 | `string` Output only. Server-defined resource path for the target of the                                                                                                                                                                                                                                                                                                            |
| `verb`                   | `string` Output only. Name of the verb executed by the operation.                                                                                                                                                                                                                                                                                                                   |
| `status_message`         | `string` Output only. Human-readable status of the operation, if any.                                                                                                                                                                                                                                                                                                               |
| `requested_cancellation` | `bool` Output only. Identifies whether the user has requested cancellation of the operation. Operations that have successfully been cancelled have \[Operation.error\]\[\] value with a [`google.rpc.Status.code`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.rpc#google.rpc.Status.FIELDS.int32.google.rpc.Status.code) of 1, corresponding to `Code.CANCELLED` . |
| `api_version`            | `string` Output only. API version used to start the operation.                                                                                                                                                                                                                                                                                                                      |

## PolicyBinding

IAM policy binding resource.

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
<td><code>display_name</code></td>
<td><p><code>string</code></p>
<p>Optional. The description of the policy binding. Must be less than or equal to 63 characters.</p></td>
</tr>
<tr class="odd">
<td><code>annotations</code></td>
<td><p><code>map&lt;string, string&gt;</code></p>
<p>Optional. User-defined annotations. See <a href="https://google.aip.dev/148#annotations">https://google.aip.dev/148#annotations</a> for more details such as format and size limitations</p></td>
</tr>
<tr class="even">
<td><code>target</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PolicyBinding.Target"><code>Target</code></a></p>
<p>Required. Immutable. The full resource name of the resource to which the policy will be bound. Immutable once set.</p></td>
</tr>
<tr class="odd">
<td><code>policy_kind</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PolicyBinding.PolicyKind"><code>PolicyKind</code></a></p>
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
<td><code>policy_uid</code></td>
<td><p><code>string</code></p>
<p>Output only. The globally unique ID of the policy to be bound.</p></td>
</tr>
<tr class="even">
<td><code>condition</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/rpc/google.type#google.type.Expr"><code>Expr</code></a></p>
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
<td><code>create_time</code></td>
<td><p><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a></p>
<p>Output only. The time when the policy binding was created.</p></td>
</tr>
<tr class="even">
<td><code>update_time</code></td>
<td><p><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a></p>
<p>Output only. The time when the policy binding was most recently updated.</p></td>
</tr>
</tbody>
</table>

## PolicyKind

The different policy kinds supported in this binding.

| Enums                       |                                            |
|-----------------------------|--------------------------------------------|
| `POLICY_KIND_UNSPECIFIED`   | Unspecified policy kind; Not a valid state |
| `PRINCIPAL_ACCESS_BOUNDARY` | Principal access boundary policy kind      |

## Target

The full resource name of the resource to which the policy will be bound. Immutable once set.

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
<td><code>principal_set</code></td>
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
</tbody>
</table>

## PrincipalAccessBoundaryPolicy

An IAM principal access boundary policy resource.

| Fields         |                                                                                                                                                                                                                                 |
|----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`         | `string` Identifier. The resource name of the principal access boundary policy. The following format is supported: `organizations/{organization_id}/locations/{location}/principalAccessBoundaryPolicies/{policy_id}`           |
| `uid`          | `string` Output only. The globally unique ID of the principal access boundary policy.                                                                                                                                           |
| `etag`         | `string` Optional. The etag for the principal access boundary. If this is provided on update, it must match the server's etag.                                                                                                  |
| `display_name` | `string` Optional. The description of the principal access boundary policy. Must be less than or equal to 63 characters.                                                                                                        |
| `annotations`  | `map<string, string>` Optional. User defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations                                                                     |
| `create_time`  | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time when the principal access boundary policy was created.                                                                  |
| `update_time`  | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time when the principal access boundary policy was most recently updated.                                                    |
| `details`      | [`PrincipalAccessBoundaryPolicyDetails`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PrincipalAccessBoundaryPolicyDetails) Optional. The details for the principal access boundary policy. |

## PrincipalAccessBoundaryPolicyDetails

Principal access boundary policy details

| Fields                |                                                                                                                                                                                                                                                                          |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `rules[]`             | [`PrincipalAccessBoundaryPolicyRule`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PrincipalAccessBoundaryPolicyRule) Required. A list of principal access boundary policy rules. The number of rules in a policy is limited to 500. |
| `enforcement_version` | `string` Optional. The version number (for example, `1` or `latest` ) that indicates which permissions are able to be blocked by the policy. If empty, the PAB policy version will be set to the most recent version number at the time of the policy's creation.        |

## PrincipalAccessBoundaryPolicyRule

Principal access boundary policy rule that defines the resource boundary.

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
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>Optional. The description of the principal access boundary policy rule. Must be less than or equal to 256 characters.</p></td>
</tr>
<tr class="even">
<td><code>resources[]</code></td>
<td><p><code>string</code></p>
<p>Required. A list of Resource Manager resources. If a resource is listed in the rule, then the rule applies for that resource and its descendants. The number of resources in a policy is limited to 500 across all rules in the policy.</p>
<p>The following resource types are supported:</p>
<ul>
<li>Organizations, such as <code>//cloudresourcemanager.googleapis.com/organizations/123</code> .</li>
<li>Folders, such as <code>//cloudresourcemanager.googleapis.com/folders/123</code> .</li>
<li>Projects, such as <code>//cloudresourcemanager.googleapis.com/projects/123</code> or <code>//cloudresourcemanager.googleapis.com/projects/my-project-id</code> .</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>effect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PrincipalAccessBoundaryPolicyRule.Effect"><code>Effect</code></a></p>
<p>Required. The access relationship of principals to the resources in this rule.</p></td>
</tr>
</tbody>
</table>

## Effect

An effect to describe the access relationship.

| Enums                |                                              |
|----------------------|----------------------------------------------|
| `EFFECT_UNSPECIFIED` | Effect unspecified.                          |
| `ALLOW`              | Allows access to the resources in this rule. |

## SearchPrincipalAccessBoundaryPolicyBindingsRequest

Request message for SearchPrincipalAccessBoundaryPolicyBindings rpc.

| Fields       |                                                                                                                                                                                                                                                                                                                             |
|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`       | `string` Required. The name of the principal access boundary policy. Format: `organizations/{organization_id}/locations/{location}/principalAccessBoundaryPolicies/{principal_access_boundary_policy_id}`                                                                                                                   |
| `page_size`  | `int32` Optional. The maximum number of policy bindings to return. The service may return fewer than this value. If unspecified, at most 50 policy bindings will be returned. The maximum value is 1000; values above 1000 will be coerced to 1000.                                                                         |
| `page_token` | `string` Optional. A page token, received from a previous `SearchPrincipalAccessBoundaryPolicyBindingsRequest` call. Provide this to retrieve the subsequent page. When paginating, all other parameters provided to `SearchPrincipalAccessBoundaryPolicyBindingsRequest` must match the call that provided the page token. |

## SearchPrincipalAccessBoundaryPolicyBindingsResponse

Response message for SearchPrincipalAccessBoundaryPolicyBindings rpc.

| Fields              |                                                                                                                                                                            |
|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policy_bindings[]` | [`PolicyBinding`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PolicyBinding) The policy bindings that reference the specified policy. |
| `next_page_token`   | `string` Optional. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.                          |

## SearchTargetPolicyBindingsRequest

Request message for SearchTargetPolicyBindings method.

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
<td><code>target</code></td>
<td><p><code>string</code></p>
<p>Required. The target resource, which is bound to the policy in the binding.</p>
<p>Format:</p>
<ul>
<li><code>//iam.googleapis.com/locations/global/workforcePools/POOL_ID</code></li>
<li><code>//iam.googleapis.com/projects/PROJECT_NUMBER/locations/global/workloadIdentityPools/POOL_ID</code></li>
<li><code>//iam.googleapis.com/locations/global/workspace/WORKSPACE_ID</code></li>
<li><code>//cloudresourcemanager.googleapis.com/projects/{project_number}</code></li>
<li><code>//cloudresourcemanager.googleapis.com/folders/{folder_id}</code></li>
<li><code>//cloudresourcemanager.googleapis.com/organizations/{organization_id}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>page_size</code></td>
<td><p><code>int32</code></p>
<p>Optional. The maximum number of policy bindings to return. The service may return fewer than this value.</p>
<p>The default value is 50. The maximum value is 1000.</p></td>
</tr>
<tr class="odd">
<td><code>page_token</code></td>
<td><p><code>string</code></p>
<p>Optional. A page token, received from a previous <code>SearchTargetPolicyBindingsRequest</code> call. Provide this to retrieve the subsequent page.</p>
<p>When paginating, all other parameters provided to <code>SearchTargetPolicyBindingsRequest</code> must match the call that provided the page token.</p></td>
</tr>
<tr class="even">
<td><code>parent</code></td>
<td><p><code>string</code></p>
<p>Required. The parent resource where this search will be performed. This should be the nearest Resource Manager resource (project, folder, or organization) to the target.</p>
<p>Format:</p>
<ul>
<li><code>projects/{project_id}/locations/{location}</code></li>
<li><code>projects/{project_number}/locations/{location}</code></li>
<li><code>folders/{folder_id}/locations/{location}</code></li>
<li><code>organizations/{organization_id}/locations/{location}</code></li>
</ul></td>
</tr>
</tbody>
</table>

## SearchTargetPolicyBindingsResponse

Response message for SearchTargetPolicyBindings method.

| Fields              |                                                                                                                                                                      |
|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policy_bindings[]` | [`PolicyBinding`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PolicyBinding) The policy bindings bound to the specified target. |
| `next_page_token`   | `string` Optional. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.                    |

## UpdatePolicyBindingRequest

Request message for UpdatePolicyBinding method.

| Fields           |                                                                                                                                                                                                                                               |
|------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policy_binding` | [`PolicyBinding`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PolicyBinding) Required. The policy binding to update. The policy binding's `name` field is used to identify the policy binding to update. |
| `validate_only`  | `bool` Optional. If set, validate the request and preview the update, but do not actually post it.                                                                                                                                            |
| `update_mask`    | [`FieldMask`](https://protobuf.dev/reference/protobuf/google.protobuf/#field-mask) Optional. The list of fields to update                                                                                                                     |

## UpdatePrincipalAccessBoundaryPolicyRequest

Request message for UpdatePrincipalAccessBoundaryPolicy method.

| Fields                             |                                                                                                                                                                                                                                                                                                           |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `principal_access_boundary_policy` | [`PrincipalAccessBoundaryPolicy`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3#google.iam.v3.PrincipalAccessBoundaryPolicy) Required. The principal access boundary policy to update. The principal access boundary policy's `name` field is used to identify the policy to update. |
| `validate_only`                    | `bool` Optional. If set, validate the request and preview the update, but do not actually post it.                                                                                                                                                                                                        |
| `update_mask`                      | [`FieldMask`](https://protobuf.dev/reference/protobuf/google.protobuf/#field-mask) Optional. The list of fields to update                                                                                                                                                                                 |
