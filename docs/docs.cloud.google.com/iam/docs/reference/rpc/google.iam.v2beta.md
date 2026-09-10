---
name: documents/docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta
uri: https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta
title: Package google.iam.v2beta
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

  - `  Policies  ` (interface)
  - `  CreatePolicyRequest  ` (message)
  - `  DeletePolicyRequest  ` (message)
  - `  DenyRule  ` (message)
  - `  GetPolicyRequest  ` (message)
  - `  ListPoliciesRequest  ` (message)
  - `  ListPoliciesResponse  ` (message)
  - `  Policy  ` (message)
  - `  PolicyOperationMetadata  ` (message)
  - `  PolicyRule  ` (message)
  - `  UpdatePolicyRequest  ` (message)

## Policies

An interface for managing Identity and Access Management (IAM) policies.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>CreatePolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc CreatePolicy(              CreatePolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Creates a policy.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
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
<th>DeletePolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc DeletePolicy(              DeletePolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Deletes a policy. This action is permanent.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
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
<th>GetPolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc GetPolicy(              GetPolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Policy            </code> )</p>
<p>Gets a policy.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
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
<th>ListPolicies</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc ListPolicies(              ListPoliciesRequest            </code> ) returns ( <code dir="ltr" translate="no">             ListPoliciesResponse            </code> )</p>
<p>Retrieves the policies of the specified kind that are attached to a resource.</p>
<p>The response lists only policy metadata. In particular, policy rules are omitted.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
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
<th>UpdatePolicy</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><code dir="ltr" translate="no">rpc UpdatePolicy(              UpdatePolicyRequest            </code> ) returns ( <code dir="ltr" translate="no">             Operation            </code> )</p>
<p>Updates the specified policy.</p>
<p>You can update only the rules and the display name for the policy.</p>
<p>To update a policy, you should use a read-modify-write loop:</p>
<ol>
<li>Use <code dir="ltr" translate="no">             GetPolicy            </code> to read the current version of the policy.</li>
<li>Modify the policy as needed.</li>
<li>Use <code dir="ltr" translate="no">UpdatePolicy</code> to write the updated policy.</li>
</ol>
<p>This pattern helps prevent conflicts between concurrent updates.</p>
<dl>
<dt>Authorization scopes</dt>
<dd><p>Requires one of the following OAuth scopes:</p>
<ul>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/cloud-platform</code></li>
<li><code dir="ltr" translate="no">https://www.googleapis.com/auth/iam</code></li>
</ul>
<p>For more information, see the <a href="https://docs.cloud.google.com/docs/authentication#authorization-gcp">Authentication Overview</a> .</p>
</dd>
</dl></td>
</tr>
</tbody>
</table>

## CreatePolicyRequest

Request message for `CreatePolicy` .

Fields

`parent`

`string`

Required. The resource that the policy is attached to, along with the kind of policy to create. Format: `policies/{attachment_point}/denypolicies`

The attachment point is identified by its URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies` .

For organizations and folders, use the numeric ID in the full resource name. For projects, you can use the alphanumeric or the numeric ID.

`policy`

`  Policy  `

Required. The policy to create.

`policy_id`

`string`

The ID to use for this policy, which will become the final component of the policy's resource name. The ID must contain 3 to 63 characters. It can contain lowercase letters and numbers, as well as dashes ( `-` ) and periods ( `.` ). The first character must be a lowercase letter.

## DeletePolicyRequest

Request message for `DeletePolicy` .

Fields

`name`

`string`

Required. The resource name of the policy to delete. Format: `policies/{attachment_point}/denypolicies/{policy_id}`

Use the URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-policy` .

For organizations and folders, use the numeric ID in the full resource name. For projects, you can use the alphanumeric or the numeric ID.

`etag`

`string`

Optional. The expected `etag` of the policy to delete. If the value does not match the value that is stored in IAM, the request fails with a `409` error code and `ABORTED` status.

If you omit this field, the policy is deleted regardless of its current `etag` .

## DenyRule

A deny rule in an IAM deny policy.

Fields

`denied_principals[]`

`string`

The identities that are prevented from using one or more permissions on Google Cloud resources. This field can contain the following values:

  - `principal://goog/subject/{email_id}` : A specific Google Account. Includes Gmail, Cloud Identity, and Google Workspace user accounts. For example, `principal://goog/subject/alice@example.com` .

  - `principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}` : A Google Cloud service account. For example, `principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com` .

  - `principalSet://goog/group/{group_id}` : A Google group. For example, `principalSet://goog/group/admins@example.com` .

  - `principalSet://goog/public:all` : A special identifier that represents any principal that is on the internet, even if they do not have a Google Account or are not logged in.

  - `principalSet://goog/cloudIdentityCustomerId/{customer_id}` : All of the principals associated with the specified Google Workspace or Cloud Identity customer ID. For example, `principalSet://goog/cloudIdentityCustomerId/C01Abc35` .

  - `principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}` : A single identity in a workforce identity pool.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/group/{group_id}` : All workforce identities in a group.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/attribute.{attribute_name}/{attribute_value}` : All workforce identities with a specific attribute value.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/*` : All identities in a workforce identity pool.

  - `principal://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/subject/{subject_attribute_value}` : A single identity in a workload identity pool.

  - `principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/group/{group_id}` : A workload identity pool group.

  - `principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/attribute.{attribute_name}/{attribute_value}` : All identities in a workload identity pool with a certain attribute.

  - `principalSet://iam.googleapis.com/projects/{project_number}/locations/global/workloadIdentityPools/{pool_id}/*` : All identities in a workload identity pool.

  - `principalSet://cloudresourcemanager.googleapis.com/[projects|folders|organizations]/{project_number|folder_number|org_number}/type/ServiceAccount` : All service accounts grouped under a resource (project, folder, or organization).

  - `principalSet://cloudresourcemanager.googleapis.com/[projects|folders|organizations]/{project_number|folder_number|org_number}/type/ServiceAgent` : All service agents grouped under a resource (project, folder, or organization).

  - `deleted:principal://goog/subject/{email_id}?uid={uid}` : A specific Google Account that was deleted recently. For example, `deleted:principal://goog/subject/alice@example.com?uid=1234567890` . If the Google Account is recovered, this identifier reverts to the standard identifier for a Google Account.

  - `deleted:principalSet://goog/group/{group_id}?uid={uid}` : A Google group that was deleted recently. For example, `deleted:principalSet://goog/group/admins@example.com?uid=1234567890` . If the Google group is restored, this identifier reverts to the standard identifier for a Google group.

  - `deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}?uid={uid}` : A Google Cloud service account that was deleted recently. For example, `deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com?uid=1234567890` . If the service account is undeleted, this identifier reverts to the standard identifier for a service account.

  - `deleted:principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}` : Deleted single identity in a workforce identity pool. For example, `deleted:principal://iam.googleapis.com/locations/global/workforcePools/my-pool-id/subject/my-subject-attribute-value` .

`exception_principals[]`

`string`

The identities that are excluded from the deny rule, even if they are listed in the `denied_principals` . For example, you could add a Google group to the `denied_principals` , then exclude specific users who belong to that group.

This field can contain the same values as the `denied_principals` field, excluding `principalSet://goog/public:all` , which represents all users on the internet.

`denied_permissions[]`

`string`

The permissions that are explicitly denied by this rule. Each permission uses the format `{service_fqdn}/{resource}.{verb}` , where `{service_fqdn}` is the fully qualified domain name for the service. For example, `iam.googleapis.com/roles.list` .

`exception_permissions[]`

`string`

Specifies the permissions that this rule excludes from the set of denied permissions given by `denied_permissions` . If a permission appears in `denied_permissions` *and* in `exception_permissions` then it will *not* be denied.

The excluded permissions can be specified using the same syntax as `denied_permissions` .

`denial_condition`

`  Expr  `

The condition that determines whether this deny rule applies to a request. If the condition expression evaluates to `true` , then the deny rule is applied; otherwise, the deny rule is not applied.

Each deny rule is evaluated independently. If this deny rule does not apply to a request, other deny rules might still apply.

The condition can use CEL functions that evaluate [resource tags](https://cloud.google.com/iam/help/conditions/resource-tags) . Other functions and operators are not supported.

## GetPolicyRequest

Request message for `GetPolicy` .

Fields

`name`

`string`

Required. The resource name of the policy to retrieve. Format: `policies/{attachment_point}/denypolicies/{policy_id}`

Use the URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-policy` .

For organizations and folders, use the numeric ID in the full resource name. For projects, you can use the alphanumeric or the numeric ID.

## ListPoliciesRequest

Request message for `ListPolicies` .

Fields

`parent`

`string`

Required. The resource that the policy is attached to, along with the kind of policy to list. Format: `policies/{attachment_point}/denypolicies`

The attachment point is identified by its URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies` .

For organizations and folders, use the numeric ID in the full resource name. For projects, you can use the alphanumeric or the numeric ID.

`page_size`

`int32`

The maximum number of policies to return. IAM ignores this value and uses the value 1000.

`page_token`

`string`

A page token received in a `  ListPoliciesResponse  ` . Provide this token to retrieve the next page.

## ListPoliciesResponse

Response message for `ListPolicies` .

Fields

`policies[]`

`  Policy  `

Metadata for the policies that are attached to the resource.

`next_page_token`

`string`

A page token that you can use in a `  ListPoliciesRequest  ` to retrieve the next page. If this field is omitted, there are no additional pages.

## Policy

Data for an IAM policy.

Fields

`name`

`string`

Immutable. The resource name of the `Policy` , which must be unique. Format: `policies/{attachment_point}/denypolicies/{policy_id}`

The attachment point is identified by its URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-deny-policy` .

For organizations and folders, use the numeric ID in the full resource name. For projects, requests can use the alphanumeric or the numeric ID. Responses always contain the numeric ID.

`uid`

`string`

Immutable. The globally unique ID of the `Policy` . Assigned automatically when the `Policy` is created.

`kind`

`string`

Output only. The kind of the `Policy` . Always contains the value `DenyPolicy` .

`display_name`

`string`

A user-specified description of the `Policy` . This value can be up to 63 characters.

`annotations`

`map<string, string>`

A key-value map to store arbitrary metadata for the `Policy` . Keys can be up to 63 characters. Values can be up to 255 characters.

`etag`

`string`

An opaque tag that identifies the current version of the `Policy` . IAM uses this value to help manage concurrent updates, so they do not cause one update to be overwritten by another.

If this field is present in a `  CreatePolicyRequest  ` , the value is ignored.

`create_time`

`  Timestamp  `

Output only. The time when the `Policy` was created.

`update_time`

`  Timestamp  `

Output only. The time when the `Policy` was last updated.

`delete_time`

`  Timestamp  `

Output only. The time when the `Policy` was deleted. Empty if the policy is not deleted.

`rules[]`

`  PolicyRule  `

A list of rules that specify the behavior of the `Policy` . All of the rules should be of the `kind` specified in the `Policy` .

## PolicyOperationMetadata

Metadata for long-running `Policy` operations.

Fields

`create_time`

`  Timestamp  `

Timestamp when the `google.longrunning.Operation` was created.

## PolicyRule

A single rule in a `Policy` .

Fields

`description`

`string`

A user-specified description of the rule. This value can be up to 256 characters.

Union field `kind` .

`kind` can be only one of the following:

`deny_rule`

`  DenyRule  `

A rule for a deny policy.

## UpdatePolicyRequest

Request message for `UpdatePolicy` .

Fields

`policy`

`  Policy  `

Required. The policy to update.

To prevent conflicting updates, the `etag` value must match the value that is stored in IAM. If the `etag` values do not match, the request fails with a `409` error code and `ABORTED` status.
