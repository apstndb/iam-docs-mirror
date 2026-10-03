---
name: documents/docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta
uri: https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta
title: Package google.iam.v2beta
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

## Index

- [`Policies`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.Policies) (interface)
- [`CreatePolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.CreatePolicyRequest) (message)
- [`DeletePolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.DeletePolicyRequest) (message)
- [`DenyRule`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.DenyRule) (message)
- [`GetPolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.GetPolicyRequest) (message)
- [`ListPoliciesRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.ListPoliciesRequest) (message)
- [`ListPoliciesResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.ListPoliciesResponse) (message)
- [`Policy`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.Policy) (message)
- [`PolicyOperationMetadata`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.PolicyOperationMetadata) (message)
- [`PolicyRule`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.PolicyRule) (message)
- [`UpdatePolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.UpdatePolicyRequest) (message)

## Policies

An interface for managing Identity and Access Management (IAM) policies.

**CreatePolicy**

`rpc CreatePolicy( `[`CreatePolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.CreatePolicyRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Creates a policy.

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**DeletePolicy**

`rpc DeletePolicy( `[`DeletePolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.DeletePolicyRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Deletes a policy. This action is permanent.

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**GetPolicy**

`rpc GetPolicy( `[`GetPolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.GetPolicyRequest)` ) returns ( `[`Policy`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.Policy)` )`

Gets a policy.

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**ListPolicies**

`rpc ListPolicies( `[`ListPoliciesRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.ListPoliciesRequest)` ) returns ( `[`ListPoliciesResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.ListPoliciesResponse)` )`

Retrieves the policies of the specified kind that are attached to a resource.

The response lists only policy metadata. In particular, policy rules are omitted.

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

**UpdatePolicy**

`rpc UpdatePolicy( `[`UpdatePolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.UpdatePolicyRequest)` ) returns ( `[`Operation`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.longrunning#google.longrunning.Operation)` )`

Updates the specified policy.

You can update only the rules and the display name for the policy.

To update a policy, you should use a read-modify-write loop:

1.  Use [`GetPolicy`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.Policies.GetPolicy) to read the current version of the policy.
2.  Modify the policy as needed.
3.  Use `UpdatePolicy` to write the updated policy.

This pattern helps prevent conflicts between concurrent updates.

Authorization scopes  
Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

## CreatePolicyRequest

Request message for `CreatePolicy` .

| Fields      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`    | `string` Required. The resource that the policy is attached to, along with the kind of policy to create. Format: `policies/{attachment_point}/denypolicies` The attachment point is identified by its URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies` . For organizations and folders, use the numeric ID in the full resource name. For projects, you can use the alphanumeric or the numeric ID. |
| `policy`    | [`Policy`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.Policy) Required. The policy to create.                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `policy_id` | `string` The ID to use for this policy, which will become the final component of the policy's resource name. The ID must contain 3 to 63 characters. It can contain lowercase letters and numbers, as well as dashes ( `-` ) and periods ( `.` ). The first character must be a lowercase letter.                                                                                                                                                                                                                                                                  |

## DeletePolicyRequest

Request message for `DeletePolicy` .

| Fields |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|--------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name` | `string` Required. The resource name of the policy to delete. Format: `policies/{attachment_point}/denypolicies/{policy_id}` Use the URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-policy` . For organizations and folders, use the numeric ID in the full resource name. For projects, you can use the alphanumeric or the numeric ID. |
| `etag` | `string` Optional. The expected `etag` of the policy to delete. If the value does not match the value that is stored in IAM, the request fails with a `409` error code and `ABORTED` status. If you omit this field, the policy is deleted regardless of its current `etag` .                                                                                                                                                                                                                               |

## DenyRule

A deny rule in an IAM deny policy.

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
<td><code>denied_principals[]</code></td>
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
<td><code>exception_principals[]</code></td>
<td><p><code>string</code></p>
<p>The identities that are excluded from the deny rule, even if they are listed in the <code>denied_principals</code> . For example, you could add a Google group to the <code>denied_principals</code> , then exclude specific users who belong to that group.</p>
<p>This field can contain the same values as the <code>denied_principals</code> field, excluding <code>principalSet://goog/public:all</code> , which represents all users on the internet.</p></td>
</tr>
<tr class="odd">
<td><code>denied_permissions[]</code></td>
<td><p><code>string</code></p>
<p>The permissions that are explicitly denied by this rule. Each permission uses the format <code>{service_fqdn}/{resource}.{verb}</code> , where <code>{service_fqdn}</code> is the fully qualified domain name for the service. For example, <code>iam.googleapis.com/roles.list</code> .</p></td>
</tr>
<tr class="even">
<td><code>exception_permissions[]</code></td>
<td><p><code>string</code></p>
<p>Specifies the permissions that this rule excludes from the set of denied permissions given by <code>denied_permissions</code> . If a permission appears in <code>denied_permissions</code> <em>and</em> in <code>exception_permissions</code> then it will <em>not</em> be denied.</p>
<p>The excluded permissions can be specified using the same syntax as <code>denied_permissions</code> .</p></td>
</tr>
<tr class="odd">
<td><code>denial_condition</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/reference/rpc/google.type#google.type.Expr"><code>Expr</code></a></p>
<p>The condition that determines whether this deny rule applies to a request. If the condition expression evaluates to <code>true</code> , then the deny rule is applied; otherwise, the deny rule is not applied.</p>
<p>Each deny rule is evaluated independently. If this deny rule does not apply to a request, other deny rules might still apply.</p>
<p>The condition can use CEL functions that evaluate <a href="https://cloud.google.com/iam/help/conditions/resource-tags">resource tags</a> . Other functions and operators are not supported.</p></td>
</tr>
</tbody>
</table>

## GetPolicyRequest

Request message for `GetPolicy` .

| Fields |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|--------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name` | `string` Required. The resource name of the policy to retrieve. Format: `policies/{attachment_point}/denypolicies/{policy_id}` Use the URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-policy` . For organizations and folders, use the numeric ID in the full resource name. For projects, you can use the alphanumeric or the numeric ID. |

## ListPoliciesRequest

Request message for `ListPolicies` .

| Fields       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|--------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`     | `string` Required. The resource that the policy is attached to, along with the kind of policy to list. Format: `policies/{attachment_point}/denypolicies` The attachment point is identified by its URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies` . For organizations and folders, use the numeric ID in the full resource name. For projects, you can use the alphanumeric or the numeric ID. |
| `page_size`  | `int32` The maximum number of policies to return. IAM ignores this value and uses the value 1000.                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `page_token` | `string` A page token received in a [`ListPoliciesResponse`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.ListPoliciesResponse) . Provide this token to retrieve the next page.                                                                                                                                                                                                                                                                                                                                      |

## ListPoliciesResponse

Response message for `ListPolicies` .

| Fields            |                                                                                                                                                                                                                                                                       |
|-------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policies[]`      | [`Policy`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.Policy) Metadata for the policies that are attached to the resource.                                                                                              |
| `next_page_token` | `string` A page token that you can use in a [`ListPoliciesRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.ListPoliciesRequest) to retrieve the next page. If this field is omitted, there are no additional pages. |

## Policy

Data for an IAM policy.

| Fields         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`         | `string` Immutable. The resource name of the `Policy` , which must be unique. Format: `policies/{attachment_point}/denypolicies/{policy_id}` The attachment point is identified by its URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-deny-policy` . For organizations and folders, use the numeric ID in the full resource name. For projects, requests can use the alphanumeric or the numeric ID. Responses always contain the numeric ID. |
| `uid`          | `string` Immutable. The globally unique ID of the `Policy` . Assigned automatically when the `Policy` is created.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `kind`         | `string` Output only. The kind of the `Policy` . Always contains the value `DenyPolicy` .                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `display_name` | `string` A user-specified description of the `Policy` . This value can be up to 63 characters.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| `annotations`  | `map<string, string>` A key-value map to store arbitrary metadata for the `Policy` . Keys can be up to 63 characters. Values can be up to 255 characters.                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `etag`         | `string` An opaque tag that identifies the current version of the `Policy` . IAM uses this value to help manage concurrent updates, so they do not cause one update to be overwritten by another. If this field is present in a [`CreatePolicyRequest`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.CreatePolicyRequest) , the value is ignored.                                                                                                                                                                                                                    |
| `create_time`  | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time when the `Policy` was created.                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `update_time`  | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time when the `Policy` was last updated.                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `delete_time`  | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Output only. The time when the `Policy` was deleted. Empty if the policy is not deleted.                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `rules[]`      | [`PolicyRule`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.PolicyRule) A list of rules that specify the behavior of the `Policy` . All of the rules should be of the `kind` specified in the `Policy` .                                                                                                                                                                                                                                                                                                                                                             |

## PolicyOperationMetadata

Metadata for long-running `Policy` operations.

| Fields        |                                                                                                                                                  |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| `create_time` | [`Timestamp`](https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp) Timestamp when the `google.longrunning.Operation` was created. |

## PolicyRule

A single rule in a `Policy` .

| Fields                                                        |                                                                                                                                           |
|---------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| `description`                                                 | `string` A user-specified description of the rule. This value can be up to 256 characters.                                                |
| Union field `kind` . `kind` can be only one of the following: |                                                                                                                                           |
| `deny_rule`                                                   | [`DenyRule`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.DenyRule) A rule for a deny policy. |

## UpdatePolicyRequest

Request message for `UpdatePolicy` .

| Fields   |                                                                                                                                                                                                                                                                                                                                             |
|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policy` | [`Policy`](https://docs.cloud.google.com/iam/docs/reference/rpc/google.iam.v2beta#google.iam.v2beta.Policy) Required. The policy to update. To prevent conflicting updates, the `etag` value must match the value that is stored in IAM. If the `etag` values do not match, the request fails with a `409` error code and `ABORTED` status. |
