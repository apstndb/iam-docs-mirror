---
name: documents/docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3beta
uri: https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v3beta
title: Package google.iam.v3beta
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

  - `  AccessPolicies  ` (interface)
  - `  PolicyBindings  ` (interface)
  - `  PrincipalAccessBoundaryPolicies  ` (interface)
  - `  AccessPolicy  ` (message)
  - `  AccessPolicyDetails  ` (message)
  - `  AccessPolicyRule  ` (message)
  - `  AccessPolicyRule.Effect  ` (enum)
  - `  AccessPolicyRule.Operation  ` (message)
  - `  CreateAccessPolicyRequest  ` (message)
  - `  CreatePolicyBindingRequest  ` (message)
  - `  CreatePrincipalAccessBoundaryPolicyRequest  ` (message)
  - `  DeleteAccessPolicyRequest  ` (message)
  - `  DeletePolicyBindingRequest  ` (message)
  - `  DeletePrincipalAccessBoundaryPolicyRequest  ` (message)
  - `  GetAccessPolicyRequest  ` (message)
  - `  GetPolicyBindingRequest  ` (message)
  - `  GetPrincipalAccessBoundaryPolicyRequest  ` (message)
  - `  ListAccessPoliciesRequest  ` (message)
  - `  ListAccessPoliciesResponse  ` (message)
  - `  ListPolicyBindingsRequest  ` (message)
  - `  ListPolicyBindingsResponse  ` (message)
  - `  ListPrincipalAccessBoundaryPoliciesRequest  ` (message)
  - `  ListPrincipalAccessBoundaryPoliciesResponse  ` (message)
  - `  OperationMetadata  ` (message)
  - `  PolicyBinding  ` (message)
  - `  PolicyBinding.PolicyKind  ` (enum)
  - `  PolicyBinding.Target  ` (message)
  - `  PrincipalAccessBoundaryPolicy  ` (message)
  - `  PrincipalAccessBoundaryPolicyDetails  ` (message)
  - `  PrincipalAccessBoundaryPolicyRule  ` (message)
  - `  PrincipalAccessBoundaryPolicyRule.Effect  ` (enum)
  - `  SearchAccessPolicyBindingsRequest  ` (message)
  - `  SearchAccessPolicyBindingsResponse  ` (message)
  - `  SearchPrincipalAccessBoundaryPolicyBindingsRequest  ` (message)
  - `  SearchPrincipalAccessBoundaryPolicyBindingsResponse  ` (message)
  - `  SearchTargetPolicyBindingsRequest  ` (message)
  - `  SearchTargetPolicyBindingsResponse  ` (message)
  - `  UpdateAccessPolicyRequest  ` (message)
  - `  UpdatePolicyBindingRequest  ` (message)
  - `  UpdatePrincipalAccessBoundaryPolicyRequest  ` (message)

## AccessPolicies

Manages Identity and Access Management (IAM) access policies.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreateAccessPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreateAccessPolicy(              CreateAccessPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Creates an access policy, and returns a long running operation.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>DeleteAccessPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeleteAccessPolicy(              DeleteAccessPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes an access policy.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>GetAccessPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetAccessPolicy(              GetAccessPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             AccessPolicy            </code> )</p>
<p>Gets an access policy.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>ListAccessPolicies</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListAccessPolicies(              ListAccessPoliciesRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListAccessPoliciesResponse            </code> )</p>
<p>Lists access policies.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>SearchAccessPolicyBindings</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc SearchAccessPolicyBindings(              SearchAccessPolicyBindingsRequest            </code> ) returns ( <code dir="ltr" translate="no">             SearchAccessPolicyBindingsResponse            </code> )</p>
<p>Returns all policy bindings that bind a specific policy if a user has searchPolicyBindings permission on that policy.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>UpdateAccessPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdateAccessPolicy(              UpdateAccessPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Updates an access policy.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

## PolicyBindings

An interface for managing Identity and Access Management (IAM) policy bindings.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreatePolicyBinding</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreatePolicyBinding(              CreatePolicyBindingRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Creates a policy binding and returns a long-running operation. Callers will need the IAM permissions on both the policy and target. After the binding is created, the policy is applied to the target.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>DeletePolicyBinding</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeletePolicyBinding(              DeletePolicyBindingRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes a policy binding and returns a long-running operation. Callers will need the IAM permissions on both the policy and target. After the binding is deleted, the policy no longer applies to the target.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>GetPolicyBinding</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetPolicyBinding(              GetPolicyBindingRequest            </code> ) returns ( <code dir="ltr" translate="no">             PolicyBinding            </code> )</p>
<p>Gets a policy binding.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.policybindings.get</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>ListPolicyBindings</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListPolicyBindings(              ListPolicyBindingsRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListPolicyBindingsResponse            </code> )</p>
<p>Lists policy bindings.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">parent</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.policybindings.list</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>SearchTargetPolicyBindings</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc SearchTargetPolicyBindings(              SearchTargetPolicyBindingsRequest            </code> ) returns ( <code dir="ltr" translate="no">             SearchTargetPolicyBindingsResponse            </code> )</p>
<p>Search policy bindings by target. Returns all policy binding objects bound directly to target.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>UpdatePolicyBinding</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdatePolicyBinding(              UpdatePolicyBindingRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Updates a policy binding and returns a long-running operation. Callers will need the IAM permissions on the policy and target in the binding to update. Target and policy are immutable and cannot be updated.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

## PrincipalAccessBoundaryPolicies

Manages Identity and Access Management (IAM) principal access boundary policies.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreatePrincipalAccessBoundaryPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreatePrincipalAccessBoundaryPolicy(              CreatePrincipalAccessBoundaryPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Creates a principal access boundary policy, and returns a long running operation.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">parent</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.principalaccessboundarypolicies.create</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>DeletePrincipalAccessBoundaryPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeletePrincipalAccessBoundaryPolicy(              DeletePrincipalAccessBoundaryPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes a principal access boundary policy.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.principalaccessboundarypolicies.delete</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>GetPrincipalAccessBoundaryPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetPrincipalAccessBoundaryPolicy(              GetPrincipalAccessBoundaryPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             PrincipalAccessBoundaryPolicy            </code> )</p>
<p>Gets a principal access boundary policy.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.principalaccessboundarypolicies.get</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>ListPrincipalAccessBoundaryPolicies</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListPrincipalAccessBoundaryPolicies(              ListPrincipalAccessBoundaryPoliciesRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListPrincipalAccessBoundaryPoliciesResponse            </code> )</p>
<p>Lists principal access boundary policies.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">parent</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.principalaccessboundarypolicies.list</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>SearchPrincipalAccessBoundaryPolicyBindings</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc SearchPrincipalAccessBoundaryPolicyBindings(              SearchPrincipalAccessBoundaryPolicyBindingsRequest            </code> ) returns ( <code dir="ltr" translate="no">             SearchPrincipalAccessBoundaryPolicyBindingsResponse            </code> )</p>
<p>Returns all policy bindings that bind a specific policy if a user has searchPolicyBindings permission on that policy.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.principalaccessboundarypolicies.searchPolicyBindings</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>UpdatePrincipalAccessBoundaryPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdatePrincipalAccessBoundaryPolicy(              UpdatePrincipalAccessBoundaryPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Updates a principal access boundary policy.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires the following OAuth scope:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl>
<dl>
<dt>IAM Permissions</dt>
<dd><p>Requires the following <a href="https://cloud.google.com/iam/docs">IAM</a> permission on the <code dir="ltr" translate="no">name</code> resource:</p>
<ul>
<li><code dir="ltr" translate="no">iam.principalaccessboundarypolicies.update</code></li>
</ul>
<p>For more information, see the <a href="https://cloud.google.com/iam/docs">IAM documentation</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

## AccessPolicy

An IAM access policy resource.

Fields

`name`

`string`

Identifier. The resource name of the access policy.

The following formats are supported:

  - `projects/{project_id}/locations/{location}/accessPolicies/{policy_id}`
  - `projects/{project_number}/locations/{location}/accessPolicies/{policy_id}`
  - `folders/{folder_id}/locations/{location}/accessPolicies/{policy_id}`
  - `organizations/{organization_id}/locations/{location}/accessPolicies/{policy_id}`

`uid`

`string`

Output only. The globally unique ID of the access policy.

`etag`

`string`

Optional. The etag for the access policy. If this is provided on update, it must match the server's etag.

`display_name`

`string`

Optional. The description of the access policy. Must be less than or equal to 63 characters.

`annotations`

`map<string, string>`

Optional. User defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations

`create_time`

`  Timestamp  `

Output only. The time when the access policy was created.

`update_time`

`  Timestamp  `

Output only. The time when the access policy was most recently updated.

`details`

`  AccessPolicyDetails  `

Optional. The details for the access policy.

## AccessPolicyDetails

Access policy details.

Fields

`rules[]`

`  AccessPolicyRule  `

Required. A list of access policy rules.

## AccessPolicyRule

Access Policy Rule that determines the behavior of the policy.

Fields

`principals[]`

`string`

Required. The identities for which this rule's effect governs using one or more permissions on Google Cloud resources. This field can contain the following values:

  - `principal://goog/subject/{email_id}` : A specific Google Account. Includes Gmail, Cloud Identity, and Google Workspace user accounts. For example, `principal://goog/subject/alice@example.com` .

  - `principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}` : A Google Cloud service account. For example, `principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com` .

  - `principalSet://goog/group/{group_id}` : A Google group. For example, `principalSet://goog/group/admins@example.com` .

  - `principalSet://goog/cloudIdentityCustomerId/{customer_id}` : All of the principals associated with the specified Google Workspace or Cloud Identity customer ID. For example, `principalSet://goog/cloudIdentityCustomerId/C01Abc35` .

If an identifier that was previously set on a policy is soft deleted, then calls to read that policy will return the identifier with a deleted prefix. Users cannot set identifiers with this syntax.

  - `deleted:principal://goog/subject/{email_id}?uid={uid}` : A specific Google Account that was deleted recently. For example, `deleted:principal://goog/subject/alice@example.com?uid=1234567890` . If the Google Account is recovered, this identifier reverts to the standard identifier for a Google Account.

  - `deleted:principalSet://goog/group/{group_id}?uid={uid}` : A Google group that was deleted recently. For example, `deleted:principalSet://goog/group/admins@example.com?uid=1234567890` . If the Google group is restored, this identifier reverts to the standard identifier for a Google group.

  - `deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}?uid={uid}` : A Google Cloud service account that was deleted recently. For example, `deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com?uid=1234567890` . If the service account is undeleted, this identifier reverts to the standard identifier for a service account.

`excluded_principals[]`

`string`

Optional. The identities that are excluded from the access policy rule, even if they are listed in the `principals` . For example, you could add a Google group to the `principals` , then exclude specific users who belong to that group.

`operation`

`  Operation  `

Required. Attributes that are used to determine whether this rule applies to a request.

`conditions`

` map<string, Expr  ` \>

Optional. The conditions that determine whether this rule applies to a request. Conditions are identified by their key, which is the FQDN of the service that they are relevant to. For example:

    "conditions": {
     "iam.googleapis.com": <cel expression>
    }

Each rule is evaluated independently. If this rule does not apply to a request, other rules might still apply. Currently supported keys are as follows:

  - `eventarc.googleapis.com` : Can use `CEL` functions that evaluate resource fields.

  - `iam.googleapis.com` : Can use `CEL` functions that evaluate [resource tags](https://cloud.google.com/iam/help/conditions/resource-tags) and combine them using boolean and logical operators. Other functions and operators are not supported.

`description`

`string`

Optional. Customer specified description of the rule. Must be less than or equal to 256 characters.

`effect`

`  Effect  `

Required. The effect of the rule.

## Effect

An effect to describe the access relationship.

Enums

`EFFECT_UNSPECIFIED`

The effect is unspecified.

`DENY`

The policy will deny access if it evaluates to true.

`ALLOW`

The policy will grant access if it evaluates to true.

## Operation

Attributes that are used to determine whether this rule applies to a request.

Fields

`permissions[]`

`string`

Optional. The permissions that are explicitly affected by this rule. Each permission uses the format `{service_fqdn}/{resource}.{verb}` , where `{service_fqdn}` is the fully qualified domain name for the service. Currently supported permissions are as follows:

  - `eventarc.googleapis.com/messageBuses.publish` .

`excluded_permissions[]`

`string`

Optional. Specifies the permissions that this rule excludes from the set of affected permissions given by `permissions` . If a permission appears in `permissions` *and* in `excluded_permissions` then it will *not* be subject to the policy effect.

The excluded permissions can be specified using the same syntax as `permissions` .

## CreateAccessPolicyRequest

Request message for CreateAccessPolicy method.

Fields

`parent`

`string`

Required. The parent resource where this access policy will be created.

Format: `projects/{project_id}/locations/{location}` `projects/{project_number}/locations/{location}` `folders/{folder_id}/locations/{location}` `organizations/{organization_id}/locations/{location}`

`access_policy_id`

`string`

Required. The ID to use for the access policy, which will become the final component of the access policy's resource name.

This value must start with a lowercase letter followed by up to 62 lowercase letters, numbers, hyphens, or dots. Pattern, /\[a-z\]\[a-z0-9-.\]{2,62}/.

This value must be unique among all access policies with the same parent.

`access_policy`

`  AccessPolicy  `

Required. The access policy to create.

`validate_only`

`bool`

Optional. If set, validate the request and preview the creation, but do not actually post it.

## CreatePolicyBindingRequest

Request message for CreatePolicyBinding method.

Fields

`parent`

`string`

Required. The parent resource where this policy binding will be created. The binding parent is the closest Resource Manager resource (project, folder or organization) to the binding target.

Format:

  - `projects/{project_id}/locations/{location}`
  - `projects/{project_number}/locations/{location}`
  - `folders/{folder_id}/locations/{location}`
  - `organizations/{organization_id}/locations/{location}`

`policy_binding_id`

`string`

Required. The ID to use for the policy binding, which will become the final component of the policy binding's resource name.

This value must start with a lowercase letter followed by up to 62 lowercase letters, numbers, hyphens, or dots. Pattern, /\[a-z\]\[a-z0-9-.\]{2,62}/.

`policy_binding`

`  PolicyBinding  `

Required. The policy binding to create.

`validate_only`

`bool`

Optional. If set, validate the request and preview the creation, but do not actually post it.

## CreatePrincipalAccessBoundaryPolicyRequest

Request message for CreatePrincipalAccessBoundaryPolicyRequest method.

Fields

`parent`

`string`

Required. The parent resource where this principal access boundary policy will be created. Only organizations are supported.

Format: `organizations/{organization_id}/locations/{location}`

`principal_access_boundary_policy_id`

`string`

Required. The ID to use for the principal access boundary policy, which will become the final component of the principal access boundary policy's resource name.

This value must start with a lowercase letter followed by up to 62 lowercase letters, numbers, hyphens, or dots. Pattern, /\[a-z\]\[a-z0-9-.\]{2,62}/.

`principal_access_boundary_policy`

`  PrincipalAccessBoundaryPolicy  `

Required. The principal access boundary policy to create.

`validate_only`

`bool`

Optional. If set, validate the request and preview the creation, but do not actually post it.

## DeleteAccessPolicyRequest

Request message for DeleteAccessPolicy method.

Fields

`name`

`string`

Required. The name of the access policy to delete.

Format: `projects/{project_id}/locations/{location}/accessPolicies/{access_policy_id}` `projects/{project_number}/locations/{location}/accessPolicies/{access_policy_id}` `folders/{folder_id}/locations/{location}/accessPolicies/{access_policy_id}` `organizations/{organization_id}/locations/{location}/accessPolicies/{access_policy_id}`

`etag`

`string`

Optional. The etag of the access policy. If this is provided, it must match the server's etag.

`validate_only`

`bool`

Optional. If set, validate the request and preview the deletion, but do not actually post it.

`force`

`bool`

Optional. If set to true, the request will force the deletion of the Policy even if the Policy references PolicyBindings.

## DeletePolicyBindingRequest

Request message for DeletePolicyBinding method.

Fields

`name`

`string`

Required. The name of the policy binding to delete.

Format:

  - `projects/{project_id}/locations/{location}/policyBindings/{policy_binding_id}`
  - `projects/{project_number}/locations/{location}/policyBindings/{policy_binding_id}`
  - `folders/{folder_id}/locations/{location}/policyBindings/{policy_binding_id}`
  - `organizations/{organization_id}/locations/{location}/policyBindings/{policy_binding_id}`

`etag`

`string`

Optional. The etag of the policy binding. If this is provided, it must match the server's etag.

`validate_only`

`bool`

Optional. If set, validate the request and preview the deletion, but do not actually post it.

## DeletePrincipalAccessBoundaryPolicyRequest

Request message for DeletePrincipalAccessBoundaryPolicy method.

Fields

`name`

`string`

Required. The name of the principal access boundary policy to delete.

Format: `organizations/{organization_id}/locations/{location}/principalAccessBoundaryPolicies/{principal_access_boundary_policy_id}`

`etag`

`string`

Optional. The etag of the principal access boundary policy. If this is provided, it must match the server's etag.

`validate_only`

`bool`

Optional. If set, validate the request and preview the deletion, but do not actually post it.

`force`

`bool`

Optional. If set to true, the request will force the deletion of the policy even if the policy is referenced in policy bindings.

## GetAccessPolicyRequest

Request message for GetAccessPolicy method.

Fields

`name`

`string`

Required. The name of the access policy to retrieve.

Format: `projects/{project_id}/locations/{location}/accessPolicies/{access_policy_id}` `projects/{project_number}/locations/{location}/accessPolicies/{access_policy_id}` `folders/{folder_id}/locations/{location}/accessPolicies/{access_policy_id}` `organizations/{organization_id}/locations/{location}/accessPolicies/{access_policy_id}`

## GetPolicyBindingRequest

Request message for GetPolicyBinding method.

Fields

`name`

`string`

Required. The name of the policy binding to retrieve.

Format:

  - `projects/{project_id}/locations/{location}/policyBindings/{policy_binding_id}`
  - `projects/{project_number}/locations/{location}/policyBindings/{policy_binding_id}`
  - `folders/{folder_id}/locations/{location}/policyBindings/{policy_binding_id}`
  - `organizations/{organization_id}/locations/{location}/policyBindings/{policy_binding_id}`

## GetPrincipalAccessBoundaryPolicyRequest

Request message for GetPrincipalAccessBoundaryPolicy method.

Fields

`name`

`string`

Required. The name of the principal access boundary policy to retrieve.

Format: `organizations/{organization_id}/locations/{location}/principalAccessBoundaryPolicies/{principal_access_boundary_policy_id}`

## ListAccessPoliciesRequest

Request message for ListAccessPolicies method.

Fields

`parent`

`string`

Required. The parent resource, which owns the collection of access policy resources.

Format: `projects/{project_id}/locations/{location}` `projects/{project_number}/locations/{location}` `folders/{folder_id}/locations/{location}` `organizations/{organization_id}/locations/{location}`

`page_size`

`int32`

Optional. The maximum number of access policies to return. The service may return fewer than this value.

If unspecified, at most 50 access policies will be returned. Valid value ranges from 1 to 1000; values above 1000 will be coerced to 1000.

`page_token`

`string`

Optional. A page token, received from a previous `ListAccessPolicies` call. Provide this to retrieve the subsequent page.

When paginating, all other parameters provided to `ListAccessPolicies` must match the call that provided the page token.

## ListAccessPoliciesResponse

Response message for ListAccessPolicies method.

Fields

`access_policies[]`

`  AccessPolicy  `

The access policies from the specified parent.

`next_page_token`

`string`

Optional. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## ListPolicyBindingsRequest

Request message for ListPolicyBindings method.

Fields

`parent`

`string`

Required. The parent resource, which owns the collection of policy bindings.

Format:

  - `projects/{project_id}/locations/{location}`
  - `projects/{project_number}/locations/{location}`
  - `folders/{folder_id}/locations/{location}`
  - `organizations/{organization_id}/locations/{location}`

`page_size`

`int32`

Optional. The maximum number of policy bindings to return. The service may return fewer than this value.

The default value is 50. The maximum value is 1000.

`page_token`

`string`

Optional. A page token, received from a previous `ListPolicyBindings` call. Provide this to retrieve the subsequent page.

When paginating, all other parameters provided to `ListPolicyBindings` must match the call that provided the page token.

`filter`

`string`

Optional. An expression for filtering the results of the request. Filter rules are case insensitive. Some eligible fields for filtering are the following:

  - `target`
  - `policy`

Some examples of filter queries:

  - `target:ex*` : The binding target's name starts with "ex".
  - `target:example` : The binding target's name is `example` .
  - `policy:example` : The binding policy's name is `example` .

## ListPolicyBindingsResponse

Response message for ListPolicyBindings method.

Fields

`policy_bindings[]`

`  PolicyBinding  `

The policy bindings from the specified parent.

`next_page_token`

`string`

Optional. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## ListPrincipalAccessBoundaryPoliciesRequest

Request message for ListPrincipalAccessBoundaryPolicies method.

Fields

`parent`

`string`

Required. The parent resource, which owns the collection of principal access boundary policies.

Format: `organizations/{organization_id}/locations/{location}`

`page_size`

`int32`

Optional. The maximum number of principal access boundary policies to return. The service may return fewer than this value.

If unspecified, at most 50 principal access boundary policies will be returned. The maximum value is 1000; values above 1000 will be coerced to 1000.

`page_token`

`string`

Optional. A page token, received from a previous `ListPrincipalAccessBoundaryPolicies` call. Provide this to retrieve the subsequent page.

When paginating, all other parameters provided to `ListPrincipalAccessBoundaryPolicies` must match the call that provided the page token.

## ListPrincipalAccessBoundaryPoliciesResponse

Response message for ListPrincipalAccessBoundaryPolicies method.

Fields

`principal_access_boundary_policies[]`

`  PrincipalAccessBoundaryPolicy  `

The principal access boundary policies from the specified parent.

`next_page_token`

`string`

Optional. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## OperationMetadata

Represents the metadata of the long-running operation.

Fields

`create_time`

`  Timestamp  `

Output only. The time the operation was created.

`end_time`

`  Timestamp  `

Output only. The time the operation finished running.

`target`

`string`

Output only. Server-defined resource path for the target of the

`verb`

`string`

Output only. Name of the verb executed by the operation.

`status_message`

`string`

Output only. Human-readable status of the operation, if any.

`requested_cancellation`

`bool`

Output only. Identifies whether the user has requested cancellation of the operation. Operations that have successfully been cancelled have \[Operation.error\]\[\] value with a `  google.rpc.Status.code  ` of 1, corresponding to `Code.CANCELLED` .

`api_version`

`string`

Output only. API version used to start the operation.

## PolicyBinding

IAM policy binding resource.

Fields

`name`

`string`

Identifier. The name of the policy binding, in the format `{binding_parent/locations/{location}/policyBindings/{policy_binding_id}` . The binding parent is the closest Resource Manager resource (project, folder, or organization) to the binding target.

Format:

  - `projects/{project_id}/locations/{location}/policyBindings/{policy_binding_id}`
  - `projects/{project_number}/locations/{location}/policyBindings/{policy_binding_id}`
  - `folders/{folder_id}/locations/{location}/policyBindings/{policy_binding_id}`
  - `organizations/{organization_id}/locations/{location}/policyBindings/{policy_binding_id}`

`uid`

`string`

Output only. The globally unique ID of the policy binding. Assigned when the policy binding is created.

`etag`

`string`

Optional. The etag for the policy binding. If this is provided on update, it must match the server's etag.

`display_name`

`string`

Optional. The description of the policy binding. Must be less than or equal to 63 characters.

`annotations`

`map<string, string>`

Optional. User-defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations

`target`

`  Target  `

Required. Immutable. The full resource name of the resource to which the policy will be bound. Immutable once set.

`policy_kind`

`  PolicyKind  `

Immutable. The kind of the policy to attach in this binding. This field must be one of the following:

  - Left empty (will be automatically set to the policy kind)
  - The input policy kind

`policy`

`string`

Required. Immutable. The resource name of the policy to be bound. The binding parent and policy must belong to the same organization.

`policy_uid`

`string`

Output only. The globally unique ID of the policy to be bound.

`condition`

`  Expr  `

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

`create_time`

`  Timestamp  `

Output only. The time when the policy binding was created.

`update_time`

`  Timestamp  `

Output only. The time when the policy binding was most recently updated.

## PolicyKind

The different policy kinds supported in this binding.

Enums

`POLICY_KIND_UNSPECIFIED`

Unspecified policy kind; Not a valid state

`PRINCIPAL_ACCESS_BOUNDARY`

Principal access boundary policy kind

`ACCESS`

Access policy kind.

## Target

The full resource name of the resource to which the policy will be bound. Immutable once set.

Fields

Union field `target` . The different types of targets that can be bound to a policy. `target` can be only one of the following:

`principal_set`

`string`

Immutable. The full resource name that's used for principal access boundary policy bindings. The principal set must be directly parented by the policy binding's parent or same as the parent if the target is a project, folder, or organization.

Examples:

  - For bindings parented by an organization:
      - Organization: `//cloudresourcemanager.googleapis.com/organizations/ORGANIZATION_ID`
      - Workforce Identity: `//iam.googleapis.com/locations/global/workforcePools/WORKFORCE_POOL_ID`
      - Workspace Identity: `//iam.googleapis.com/locations/global/workspace/WORKSPACE_ID`
  - For bindings parented by a folder:
      - Folder: `//cloudresourcemanager.googleapis.com/folders/FOLDER_ID`
  - For bindings parented by a project:
      - Project:
          - `//cloudresourcemanager.googleapis.com/projects/PROJECT_NUMBER`
          - `//cloudresourcemanager.googleapis.com/projects/PROJECT_ID`
      - Workload Identity Pool: `//iam.googleapis.com/projects/PROJECT_NUMBER/locations/LOCATION/workloadIdentityPools/WORKLOAD_POOL_ID`

`resource`

`string`

Immutable. The full resource name that's used for access policy bindings.

Examples:

  - Organization: `//cloudresourcemanager.googleapis.com/organizations/ORGANIZATION_ID`
  - Folder: `//cloudresourcemanager.googleapis.com/folders/FOLDER_ID`
  - Project:
      - `//cloudresourcemanager.googleapis.com/projects/PROJECT_NUMBER`
      - `//cloudresourcemanager.googleapis.com/projects/PROJECT_ID`

## PrincipalAccessBoundaryPolicy

An IAM principal access boundary policy resource.

Fields

`name`

`string`

Identifier. The resource name of the principal access boundary policy.

The following format is supported: `organizations/{organization_id}/locations/{location}/principalAccessBoundaryPolicies/{policy_id}`

`uid`

`string`

Output only. The globally unique ID of the principal access boundary policy.

`etag`

`string`

Optional. The etag for the principal access boundary. If this is provided on update, it must match the server's etag.

`display_name`

`string`

Optional. The description of the principal access boundary policy. Must be less than or equal to 63 characters.

`annotations`

`map<string, string>`

Optional. User defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations

`create_time`

`  Timestamp  `

Output only. The time when the principal access boundary policy was created.

`update_time`

`  Timestamp  `

Output only. The time when the principal access boundary policy was most recently updated.

`details`

`  PrincipalAccessBoundaryPolicyDetails  `

Optional. The details for the principal access boundary policy.

## PrincipalAccessBoundaryPolicyDetails

Principal access boundary policy details

Fields

`rules[]`

`  PrincipalAccessBoundaryPolicyRule  `

Required. A list of principal access boundary policy rules. The number of rules in a policy is limited to 500.

`enforcement_version`

`string`

Optional. The version number (for example, `1` or `latest` ) that indicates which permissions are able to be blocked by the policy. If empty, the PAB policy version will be set to the most recent version number at the time of the policy's creation.

## PrincipalAccessBoundaryPolicyRule

Principal access boundary policy rule that defines the resource boundary.

Fields

`description`

`string`

Optional. The description of the principal access boundary policy rule. Must be less than or equal to 256 characters.

`resources[]`

`string`

Required. A list of Resource Manager resources. If a resource is listed in the rule, then the rule applies for that resource and its descendants. The number of resources in a policy is limited to 500 across all rules in the policy.

The following resource types are supported:

  - Organizations, such as `//cloudresourcemanager.googleapis.com/organizations/123` .
  - Folders, such as `//cloudresourcemanager.googleapis.com/folders/123` .
  - Projects, such as `//cloudresourcemanager.googleapis.com/projects/123` or `//cloudresourcemanager.googleapis.com/projects/my-project-id` .

`effect`

`  Effect  `

Required. The access relationship of principals to the resources in this rule.

## Effect

An effect to describe the access relationship.

Enums

`EFFECT_UNSPECIFIED`

Effect unspecified.

`ALLOW`

Allows access to the resources in this rule.

## SearchAccessPolicyBindingsRequest

Request message for SearchAccessPolicyBindings rpc.

Fields

`name`

`string`

Required. The name of the access policy. Format: `organizations/{organization_id}/locations/{location}/accessPolicies/{access_policy_id}` `folders/{folder_id}/locations/{location}/accessPolicies/{access_policy_id}` `projects/{project_id}/locations/{location}/accessPolicies/{access_policy_id}` `projects/{project_number}/locations/{location}/accessPolicies/{access_policy_id}`

`page_size`

`int32`

Optional. The maximum number of policy bindings to return. The service may return fewer than this value.

If unspecified, at most 50 policy bindings will be returned. The maximum value is 1000; values above 1000 will be coerced to 1000.

`page_token`

`string`

Optional. A page token, received from a previous `SearchAccessPolicyBindingsRequest` call. Provide this to retrieve the subsequent page.

When paginating, all other parameters provided to `SearchAccessPolicyBindingsRequest` must match the call that provided the page token.

## SearchAccessPolicyBindingsResponse

Response message for SearchAccessPolicyBindings rpc.

Fields

`policy_bindings[]`

`  PolicyBinding  `

The policy bindings that reference the specified policy.

`next_page_token`

`string`

Optional. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## SearchPrincipalAccessBoundaryPolicyBindingsRequest

Request message for SearchPrincipalAccessBoundaryPolicyBindings rpc.

Fields

`name`

`string`

Required. The name of the principal access boundary policy. Format: `organizations/{organization_id}/locations/{location}/principalAccessBoundaryPolicies/{principal_access_boundary_policy_id}`

`page_size`

`int32`

Optional. The maximum number of policy bindings to return. The service may return fewer than this value.

If unspecified, at most 50 policy bindings will be returned. The maximum value is 1000; values above 1000 will be coerced to 1000.

`page_token`

`string`

Optional. A page token, received from a previous `SearchPrincipalAccessBoundaryPolicyBindingsRequest` call. Provide this to retrieve the subsequent page.

When paginating, all other parameters provided to `SearchPrincipalAccessBoundaryPolicyBindingsRequest` must match the call that provided the page token.

## SearchPrincipalAccessBoundaryPolicyBindingsResponse

Response message for SearchPrincipalAccessBoundaryPolicyBindings rpc.

Fields

`policy_bindings[]`

`  PolicyBinding  `

The policy bindings that reference the specified policy.

`next_page_token`

`string`

Optional. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## SearchTargetPolicyBindingsRequest

Request message for SearchTargetPolicyBindings method.

Fields

`target`

`string`

Required. The target resource, which is bound to the policy in the binding.

Format:

  - `//iam.googleapis.com/locations/global/workforcePools/POOL_ID`
  - `//iam.googleapis.com/projects/PROJECT_NUMBER/locations/global/workloadIdentityPools/POOL_ID`
  - `//iam.googleapis.com/locations/global/workspace/WORKSPACE_ID`
  - `//cloudresourcemanager.googleapis.com/projects/{project_number}`
  - `//cloudresourcemanager.googleapis.com/folders/{folder_id}`
  - `//cloudresourcemanager.googleapis.com/organizations/{organization_id}`

`page_size`

`int32`

Optional. The maximum number of policy bindings to return. The service may return fewer than this value.

The default value is 50. The maximum value is 1000.

`page_token`

`string`

Optional. A page token, received from a previous `SearchTargetPolicyBindingsRequest` call. Provide this to retrieve the subsequent page.

When paginating, all other parameters provided to `SearchTargetPolicyBindingsRequest` must match the call that provided the page token.

`parent`

`string`

Required. The parent resource where this search will be performed. This should be the nearest Resource Manager resource (project, folder, or organization) to the target.

Format:

  - `projects/{project_id}/locations/{location}`
  - `projects/{project_number}/locations/{location}`
  - `folders/{folder_id}/locations/{location}`
  - `organizations/{organization_id}/locations/{location}`

`filter`

`string`

Optional. Filtering currently only supports the kind of policies to return, and must be in the format "policy\_kind={policy\_kind}".

If String is empty, bindings bound to all kinds of policies would be returned.

The only supported values are the following:

  - "policy\_kind=PRINCIPAL\_ACCESS\_BOUNDARY",
  - "policy\_kind=ACCESS"

## SearchTargetPolicyBindingsResponse

Response message for SearchTargetPolicyBindings method.

Fields

`policy_bindings[]`

`  PolicyBinding  `

The policy bindings bound to the specified target.

`next_page_token`

`string`

Optional. A token, which can be sent as `page_token` to retrieve the next page. If this field is omitted, there are no subsequent pages.

## UpdateAccessPolicyRequest

Request message for UpdateAccessPolicy method.

Fields

`access_policy`

`  AccessPolicy  `

Required. The access policy to update.

The access policy's `name` field is used to identify the policy to update.

`validate_only`

`bool`

Optional. If set, validate the request and preview the update, but do not actually post it.

## UpdatePolicyBindingRequest

Request message for UpdatePolicyBinding method.

Fields

`policy_binding`

`  PolicyBinding  `

Required. The policy binding to update.

The policy binding's `name` field is used to identify the policy binding to update.

`validate_only`

`bool`

Optional. If set, validate the request and preview the update, but do not actually post it.

`update_mask`

`  FieldMask  `

Optional. The list of fields to update

## UpdatePrincipalAccessBoundaryPolicyRequest

Request message for UpdatePrincipalAccessBoundaryPolicy method.

Fields

`principal_access_boundary_policy`

`  PrincipalAccessBoundaryPolicy  `

Required. The principal access boundary policy to update.

The principal access boundary policy's `name` field is used to identify the policy to update.

`validate_only`

`bool`

Optional. If set, validate the request and preview the update, but do not actually post it.

`update_mask`

`  FieldMask  `

Optional. The list of fields to update
