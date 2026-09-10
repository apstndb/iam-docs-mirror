---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies
title: 'REST Resource: policies'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: Policy](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies#Policy)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies#Policy.SCHEMA_REPRESENTATION)
  - [PolicyRule](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies#PolicyRule)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies#PolicyRule.SCHEMA_REPRESENTATION)
  - [DenyRule](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies#DenyRule)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies#DenyRule.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies#METHODS_SUMMARY)

## Resource: Policy

Data for an IAM policy.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;uid&quot;: string,&quot;kind&quot;: string,&quot;displayName&quot;: string,&quot;annotations&quot;: {string: string,...},&quot;etag&quot;: string,&quot;createTime&quot;: string,&quot;updateTime&quot;: string,&quot;deleteTime&quot;: string,&quot;rules&quot;: [{object (PolicyRule)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Immutable. The resource name of the `Policy` , which must be unique. Format: `policies/{attachmentPoint}/denypolicies/{policyId}`

The attachment point is identified by its URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-deny-policy` .

For organizations and folders, use the numeric ID in the full resource name. For projects, requests can use the alphanumeric or the numeric ID. Responses always contain the numeric ID.

`uid`

`string`

Immutable. The globally unique ID of the `Policy` . Assigned automatically when the `Policy` is created.

`kind`

`string`

Output only. The kind of the `Policy` . Always contains the value `DenyPolicy` .

`displayName`

`string`

A user-specified description of the `Policy` . This value can be up to 63 characters.

`annotations`

`map (key: string, value: string)`

A key-value map to store arbitrary metadata for the `Policy` . Keys can be up to 63 characters. Values can be up to 255 characters.

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`etag`

`string`

An opaque tag that identifies the current version of the `Policy` . IAM uses this value to help manage concurrent updates, so they do not cause one update to be overwritten by another.

If this field is present in a `CreatePolicyRequest` , the value is ignored.

`createTime`

` string ( Timestamp  ` format)

Output only. The time when the `Policy` was created.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`updateTime`

` string ( Timestamp  ` format)

Output only. The time when the `Policy` was last updated.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`deleteTime`

` string ( Timestamp  ` format)

Output only. The time when the `Policy` was deleted. Empty if the policy is not deleted.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`rules[]`

` object ( PolicyRule  ` )

A list of rules that specify the behavior of the `Policy` . All of the rules should be of the `kind` specified in the `Policy` .

## PolicyRule

A single rule in a `Policy` .

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;description&quot;: string,// Union field kind can be only one of the following:&quot;denyRule&quot;: {object (DenyRule)}// End of list of possible types for union field kind.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`description`

`string`

A user-specified description of the rule. This value can be up to 256 characters.

Union field `kind` .

`kind` can be only one of the following:

`denyRule`

` object ( DenyRule  ` )

A rule for a deny policy.

## DenyRule

A deny rule in an IAM deny policy.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;deniedPrincipals&quot;: [string],&quot;exceptionPrincipals&quot;: [string],&quot;deniedPermissions&quot;: [string],&quot;exceptionPermissions&quot;: [string],&quot;denialCondition&quot;: {object (Expr)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`deniedPrincipals[]`

`string`

The identities that are prevented from using one or more permissions on Google Cloud resources. This field can contain the following values:

  - `principal://goog/subject/{email_id}` : A specific Google Account. Includes Gmail, Cloud Identity, and Google Workspace user accounts. For example, `principal://goog/subject/alice@example.com` .

  - `principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}` : A Google Cloud service account. For example, `principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com` .

  - `principalSet://goog/group/{groupId}` : A Google group. For example, `principalSet://goog/group/admins@example.com` .

  - `principalSet://goog/public:all` : A special identifier that represents any principal that is on the internet, even if they do not have a Google Account or are not logged in.

  - `principalSet://goog/cloudIdentityCustomerId/{customerId}` : All of the principals associated with the specified Google Workspace or Cloud Identity customer ID. For example, `principalSet://goog/cloudIdentityCustomerId/C01Abc35` .

  - `principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}` : A single identity in a workforce identity pool.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/group/{groupId}` : All workforce identities in a group.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/attribute.{attribute_name}/{attribute_value}` : All workforce identities with a specific attribute value.

  - `principalSet://iam.googleapis.com/locations/global/workforcePools/{pool_id}/*` : All identities in a workforce identity pool.

  - `principal://iam.googleapis.com/projects/{projectNumber}/locations/global/workloadIdentityPools/{pool_id}/subject/{subject_attribute_value}` : A single identity in a workload identity pool.

  - `principalSet://iam.googleapis.com/projects/{projectNumber}/locations/global/workloadIdentityPools/{pool_id}/group/{groupId}` : A workload identity pool group.

  - `principalSet://iam.googleapis.com/projects/{projectNumber}/locations/global/workloadIdentityPools/{pool_id}/attribute.{attribute_name}/{attribute_value}` : All identities in a workload identity pool with a certain attribute.

  - `principalSet://iam.googleapis.com/projects/{projectNumber}/locations/global/workloadIdentityPools/{pool_id}/*` : All identities in a workload identity pool.

  - `principalSet://cloudresourcemanager.googleapis.com/[projects|folders|organizations]/{projectNumber|folder_number|org_number}/type/ServiceAccount` : All service accounts grouped under a resource (project, folder, or organization).

  - `principalSet://cloudresourcemanager.googleapis.com/[projects|folders|organizations]/{projectNumber|folder_number|org_number}/type/ServiceAgent` : All service agents grouped under a resource (project, folder, or organization).

  - `deleted:principal://goog/subject/{email_id}?uid={uid}` : A specific Google Account that was deleted recently. For example, `deleted:principal://goog/subject/alice@example.com?uid=1234567890` . If the Google Account is recovered, this identifier reverts to the standard identifier for a Google Account.

  - `deleted:principalSet://goog/group/{groupId}?uid={uid}` : A Google group that was deleted recently. For example, `deleted:principalSet://goog/group/admins@example.com?uid=1234567890` . If the Google group is restored, this identifier reverts to the standard identifier for a Google group.

  - `deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}?uid={uid}` : A Google Cloud service account that was deleted recently. For example, `deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com?uid=1234567890` . If the service account is undeleted, this identifier reverts to the standard identifier for a service account.

  - `deleted:principal://iam.googleapis.com/locations/global/workforcePools/{pool_id}/subject/{subject_attribute_value}` : Deleted single identity in a workforce identity pool. For example, `deleted:principal://iam.googleapis.com/locations/global/workforcePools/my-pool-id/subject/my-subject-attribute-value` .

`exceptionPrincipals[]`

`string`

The identities that are excluded from the deny rule, even if they are listed in the `deniedPrincipals` . For example, you could add a Google group to the `deniedPrincipals` , then exclude specific users who belong to that group.

This field can contain the same values as the `deniedPrincipals` field, excluding `principalSet://goog/public:all` , which represents all users on the internet.

`deniedPermissions[]`

`string`

The permissions that are explicitly denied by this rule. Each permission uses the format `{service_fqdn}/{resource}.{verb}` , where `{service_fqdn}` is the fully qualified domain name for the service. For example, `iam.googleapis.com/roles.list` .

`exceptionPermissions[]`

`string`

Specifies the permissions that this rule excludes from the set of denied permissions given by `deniedPermissions` . If a permission appears in `deniedPermissions` *and* in `exceptionPermissions` then it will *not* be denied.

The excluded permissions can be specified using the same syntax as `deniedPermissions` .

`denialCondition`

` object ( Expr  ` )

The condition that determines whether this deny rule applies to a request. If the condition expression evaluates to `true` , then the deny rule is applied; otherwise, the deny rule is not applied.

Each deny rule is evaluated independently. If this deny rule does not apply to a request, other deny rules might still apply.

The condition can use CEL functions that evaluate [resource tags](https://cloud.google.com/iam/help/conditions/resource-tags) . Other functions and operators are not supported.

## Methods

### `            createPolicy           `

Creates a policy.

### `            delete           `

Deletes a policy.

### `            get           `

Gets a policy.

### `            listPolicies           `

Retrieves the policies of the specified kind that are attached to a resource.

### `            update           `

Updates the specified policy.
