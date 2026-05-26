---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies
title: 'REST Resource: organizations.locations.accessPolicies'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: AccessPolicy](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies#AccessPolicy)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies#AccessPolicy.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies#METHODS_SUMMARY)

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
