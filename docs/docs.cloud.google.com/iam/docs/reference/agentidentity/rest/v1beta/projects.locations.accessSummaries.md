---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries
title: 'REST Resource: projects.locations.accessSummaries'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: AccessSummary](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries#AccessSummary)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries#AccessSummary.SCHEMA_REPRESENTATION)
  - [AuthProviderType](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries#AuthProviderType)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries#METHODS_SUMMARY)

## Resource: AccessSummary

Represents an access summary.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;firstAccessTime&quot;: string,&quot;lastAccessTime&quot;: string,&quot;labels&quot;: {string: string,...},&quot;userId&quot;: string,&quot;workloadId&quot;: string,&quot;tokenUrl&quot;: string,&quot;scopes&quot;: [string],&quot;authProvider&quot;: string,&quot;purgeTime&quot;: string,&quot;authProviderType&quot;: enum (AuthProviderType)}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Output only. Identifier. The resource name of the access summary.

`firstAccessTime`

` string ( Timestamp  ` format)

Output only. The first time this user interacted with this workload, rounded to the previous hour.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`lastAccessTime`

` string ( Timestamp  ` format)

Output only. The most recent time this user interacted with this workload, rounded to the previous hour.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`labels`

`map (key: string, value: string)`

Optional. Labels as key-value pairs.

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`userId`

`string`

Output only. The user ID provided by the workload application for this user. Not verified by Google.

`workloadId`

`string`

Output only. The identity bound to the workload that this user interacted with to produce this access summary. Typically an agentic SPIFFE ID.

`tokenUrl`

`string`

Output only. The URL of the authentication server that was accessed.

`scopes[]`

`string`

Output only. All scopes that have been used by this user with this workload. The number of scopes is limited to 200.

`authProvider`

`string`

Output only. The auth provider that this access summary is associated with.

`purgeTime`

` string ( Timestamp  ` format)

Output only. The time when this access summary is permanently deleted.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`authProviderType`

` enum ( AuthProviderType  ` )

Output only. The auth provider type used to create this access summary.

## AuthProviderType

The type of the auth provider. New values may be added to this enum in the future.

Enums

`AUTH_PROVIDER_TYPE_UNSPECIFIED`

Unspecified auth provider type.

`AUTH_PROVIDER_TYPE_THREE_LEGGED_OAUTH`

3-legged OAuth (3LO) auth provider type.

`AUTH_PROVIDER_TYPE_TWO_LEGGED_OAUTH`

2-legged OAuth (2LO) auth provider type.

`AUTH_PROVIDER_TYPE_API_KEY`

API key auth provider type.

`AUTH_PROVIDER_TYPE_GEMINI_ENTERPRISE`

Gemini Enterprise auth provider type.

## Methods

### `            get           `

Gets details of a single access summary.

### `            list           `

Lists access summaries in a given project and location.
