---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies
title: 'REST Resource: folders.locations.accessPolicies'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: AccessPolicy](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.SCHEMA_REPRESENTATION)
      - [AccessPolicyDetails](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.AccessPolicyDetails)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.AccessPolicyDetails.SCHEMA_REPRESENTATION)
      - [AccessPolicyRule](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.AccessPolicyRule)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.AccessPolicyRule.SCHEMA_REPRESENTATION)
      - [Effect](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.Effect)
      - [Operation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.Operation)
          - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.Operation.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#METHODS_SUMMARY)

## Resource: AccessPolicy

An IAM access policy resource.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;uid&quot;: string,&quot;etag&quot;: string,&quot;displayName&quot;: string,&quot;annotations&quot;: {string: string,...},&quot;createTime&quot;: string,&quot;updateTime&quot;: string,&quot;details&quot;: {object (AccessPolicyDetails)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Identifier. The resource name of the access policy.

The following formats are supported:

  - `projects/{projectId}/locations/{location}/accessPolicies/{policyId}`
  - `projects/{projectNumber}/locations/{location}/accessPolicies/{policyId}`
  - `folders/{folderId}/locations/{location}/accessPolicies/{policyId}`
  - `organizations/{organizationId}/locations/{location}/accessPolicies/{policyId}`

`uid`

`string`

Output only. The globally unique ID of the access policy.

`etag`

`string`

Optional. The etag for the access policy. If this is provided on update, it must match the server's etag.

`displayName`

`string`

Optional. The description of the access policy. Must be less than or equal to 63 characters.

`annotations`

`map (key: string, value: string)`

Optional. User defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`createTime`

` string ( Timestamp  ` format)

Output only. The time when the access policy was created.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`updateTime`

` string ( Timestamp  ` format)

Output only. The time when the access policy was most recently updated.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`details`

` object ( AccessPolicyDetails  ` )

Optional. The details for the access policy.

### AccessPolicyDetails

Access policy details.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;rules&quot;: [{object (AccessPolicyRule)}]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`rules[]`

` object ( AccessPolicyRule  ` )

Required. A list of access policy rules.

### AccessPolicyRule

Access Policy Rule that determines the behavior of the policy.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;principals&quot;: [string],&quot;excludedPrincipals&quot;: [string],&quot;operation&quot;: {object (Operation)},&quot;conditions&quot;: {string: {object (Expr)},...},&quot;description&quot;: string,&quot;effect&quot;: enum (Effect)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`principals[]`

`string`

Required. The identities for which this rule's effect governs using one or more permissions on Google Cloud resources. This field can contain the following values:

  - `principal://goog/subject/{email_id}` : A specific Google Account. Includes Gmail, Cloud Identity, and Google Workspace user accounts. For example, `principal://goog/subject/alice@example.com` .

  - `principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}` : A Google Cloud service account. For example, `principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com` .

  - `principalSet://goog/group/{groupId}` : A Google group. For example, `principalSet://goog/group/admins@example.com` .

  - `principalSet://goog/cloudIdentityCustomerId/{customerId}` : All of the principals associated with the specified Google Workspace or Cloud Identity customer ID. For example, `principalSet://goog/cloudIdentityCustomerId/C01Abc35` .

If an identifier that was previously set on a policy is soft deleted, then calls to read that policy will return the identifier with a deleted prefix. Users cannot set identifiers with this syntax.

  - `deleted:principal://goog/subject/{email_id}?uid={uid}` : A specific Google Account that was deleted recently. For example, `deleted:principal://goog/subject/alice@example.com?uid=1234567890` . If the Google Account is recovered, this identifier reverts to the standard identifier for a Google Account.

  - `deleted:principalSet://goog/group/{groupId}?uid={uid}` : A Google group that was deleted recently. For example, `deleted:principalSet://goog/group/admins@example.com?uid=1234567890` . If the Google group is restored, this identifier reverts to the standard identifier for a Google group.

  - `deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/{service_account_id}?uid={uid}` : A Google Cloud service account that was deleted recently. For example, `deleted:principal://iam.googleapis.com/projects/-/serviceAccounts/my-service-account@iam.gserviceaccount.com?uid=1234567890` . If the service account is undeleted, this identifier reverts to the standard identifier for a service account.

`excludedPrincipals[]`

`string`

Optional. The identities that are excluded from the access policy rule, even if they are listed in the `principals` . For example, you could add a Google group to the `principals` , then exclude specific users who belong to that group.

`operation`

` object ( Operation  ` )

Required. Attributes that are used to determine whether this rule applies to a request.

`conditions`

` map (key: string, value: object ( Expr  ` ))

Optional. The conditions that determine whether this rule applies to a request. Conditions are identified by their key, which is the FQDN of the service that they are relevant to. For example:

    "conditions": {
     "iam.googleapis.com": <cel expression>
    }

Each rule is evaluated independently. If this rule does not apply to a request, other rules might still apply. Currently supported keys are as follows:

  - `eventarc.googleapis.com` : Can use `CEL` functions that evaluate resource fields.

  - `iam.googleapis.com` : Can use `CEL` functions that evaluate [resource tags](https://cloud.google.com/iam/help/conditions/resource-tags) and combine them using boolean and logical operators. Other functions and operators are not supported.

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`description`

`string`

Optional. Customer specified description of the rule. Must be less than or equal to 256 characters.

`effect`

` enum ( Effect  ` )

Required. The effect of the rule.

### Effect

An effect to describe the access relationship.

Enums

`EFFECT_UNSPECIFIED`

The effect is unspecified.

`DENY`

The policy will deny access if it evaluates to true.

`ALLOW`

The policy will grant access if it evaluates to true.

### Operation

Attributes that are used to determine whether this rule applies to a request.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{
  &quot;permissions&quot;: [
    string
  ],
  &quot;excludedPermissions&quot;: [
    string
  ]
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`permissions[]`

`string`

Optional. The permissions that are explicitly affected by this rule. Each permission uses the format `{service_fqdn}/{resource}.{verb}` , where `{service_fqdn}` is the fully qualified domain name for the service. Currently supported permissions are as follows:

  - `eventarc.googleapis.com/messageBuses.publish` .

`excludedPermissions[]`

`string`

Optional. Specifies the permissions that this rule excludes from the set of affected permissions given by `permissions` . If a permission appears in `permissions` *and* in `excludedPermissions` then it will *not* be subject to the policy effect.

The excluded permissions can be specified using the same syntax as `permissions` .

## Methods

### `            create           `

Creates an access policy, and returns a long running operation.

### `            delete           `

Deletes an access policy.

### `            get           `

Gets an access policy.

### `            list           `

Lists access policies.

### `            patch           `

Updates an access policy.

### `            searchPolicyBindings           `

Returns all policy bindings that bind a specific policy if a user has searchPolicyBindings permission on that policy.
