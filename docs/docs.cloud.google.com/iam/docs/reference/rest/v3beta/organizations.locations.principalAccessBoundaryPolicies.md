---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.principalAccessBoundaryPolicies
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.principalAccessBoundaryPolicies
title: 'REST Resource: organizations.locations.principalAccessBoundaryPolicies'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: PrincipalAccessBoundaryPolicy](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicy)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicy.SCHEMA_REPRESENTATION)
  - [PrincipalAccessBoundaryPolicyDetails](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicyDetails)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicyDetails.SCHEMA_REPRESENTATION)
  - [PrincipalAccessBoundaryPolicyRule](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicyRule)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.principalAccessBoundaryPolicies#PrincipalAccessBoundaryPolicyRule.SCHEMA_REPRESENTATION)
  - [Effect](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.principalAccessBoundaryPolicies#Effect)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.principalAccessBoundaryPolicies#METHODS_SUMMARY)

## Resource: PrincipalAccessBoundaryPolicy

An IAM principal access boundary policy resource.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;uid&quot;: string,&quot;etag&quot;: string,&quot;displayName&quot;: string,&quot;annotations&quot;: {string: string,...},&quot;createTime&quot;: string,&quot;updateTime&quot;: string,&quot;details&quot;: {object (PrincipalAccessBoundaryPolicyDetails)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Identifier. The resource name of the principal access boundary policy.

The following format is supported: `organizations/{organizationId}/locations/{location}/principalAccessBoundaryPolicies/{policyId}`

`uid`

`string`

Output only. The globally unique ID of the principal access boundary policy.

`etag`

`string`

Optional. The etag for the principal access boundary. If this is provided on update, it must match the server's etag.

`displayName`

`string`

Optional. The description of the principal access boundary policy. Must be less than or equal to 63 characters.

`annotations`

`map (key: string, value: string)`

Optional. User defined annotations. See <https://google.aip.dev/148#annotations> for more details such as format and size limitations

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`createTime`

` string ( Timestamp  ` format)

Output only. The time when the principal access boundary policy was created.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`updateTime`

` string ( Timestamp  ` format)

Output only. The time when the principal access boundary policy was most recently updated.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`details`

` object ( PrincipalAccessBoundaryPolicyDetails  ` )

Optional. The details for the principal access boundary policy.

## PrincipalAccessBoundaryPolicyDetails

Principal access boundary policy details

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;rules&quot;: [{object (PrincipalAccessBoundaryPolicyRule)}],&quot;enforcementVersion&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`rules[]`

` object ( PrincipalAccessBoundaryPolicyRule  ` )

Required. A list of principal access boundary policy rules. The number of rules in a policy is limited to 500.

`enforcementVersion`

`string`

Optional. The version number (for example, `1` or `latest` ) that indicates which permissions are able to be blocked by the policy. If empty, the PAB policy version will be set to the most recent version number at the time of the policy's creation.

## PrincipalAccessBoundaryPolicyRule

Principal access boundary policy rule that defines the resource boundary.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;description&quot;: string,&quot;resources&quot;: [string],&quot;effect&quot;: enum (Effect)}</code></pre></td>
</tr>
</tbody>
</table>

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

` enum ( Effect  ` )

Required. The access relationship of principals to the resources in this rule.

## Effect

An effect to describe the access relationship.

Enums

`EFFECT_UNSPECIFIED`

Effect unspecified.

`ALLOW`

Allows access to the resources in this rule.

## Methods

### `            create           `

Creates a principal access boundary policy, and returns a long running operation.

### `            delete           `

Deletes a principal access boundary policy.

### `            get           `

Gets a principal access boundary policy.

### `            list           `

Lists principal access boundary policies.

### `            patch           `

Updates a principal access boundary policy.

### `            searchPolicyBindings           `

Returns all policy bindings that bind a specific policy if a user has searchPolicyBindings permission on that policy.
