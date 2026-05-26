---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients
title: 'REST Resource: projects.locations.oauthClients'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: OauthClient](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient.SCHEMA_REPRESENTATION)
  - [State](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#State)
  - [ClientType](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#ClientType)
  - [GrantType](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#GrantType)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#METHODS_SUMMARY)

## Resource: OauthClient

Represents an `  OauthClient  ` . Used to access Google Cloud resources on behalf of a Workforce Identity Federation user by using OAuth 2.0 Protocol to obtain an access token from Google Cloud.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;state&quot;: enum (State),&quot;disabled&quot;: boolean,&quot;clientId&quot;: string,&quot;displayName&quot;: string,&quot;description&quot;: string,&quot;clientType&quot;: enum (ClientType),&quot;allowedGrantTypes&quot;: [enum (GrantType)],&quot;allowedScopes&quot;: [string],&quot;allowedRedirectUris&quot;: [string],&quot;expireTime&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Immutable. Identifier. The resource name of the `  OauthClient  ` .

Format: `projects/{project}/locations/{location}/oauthClients/{oauthClient}` .

`state`

` enum ( State  ` )

Output only. The state of the `  OauthClient  ` .

`disabled`

`boolean`

Optional. Whether the `  OauthClient  ` is disabled. You cannot use a disabled OAuth client.

`clientId`

`string`

Output only. The system-generated `  OauthClient  ` id.

`displayName`

`string`

Optional. A user-specified display name of the `  OauthClient  ` .

Cannot exceed 32 characters.

`description`

`string`

Optional. A user-specified description of the `  OauthClient  ` .

Cannot exceed 256 characters.

`clientType`

` enum ( ClientType  ` )

Immutable. The type of `  OauthClient  ` . Either public or private. For private clients, the client secret can be managed using the dedicated `  OauthClientCredential  ` resource.

`allowedGrantTypes[]`

` enum ( GrantType  ` )

Required. The list of OAuth grant types is allowed for the `  OauthClient  ` .

`allowedScopes[]`

`string`

Required. The list of scopes that the `  OauthClient  ` is allowed to request during OAuth flows.

The following scopes are supported:

  - `https://www.googleapis.com/auth/cloud-platform` : See, edit, configure, and delete your Google Cloud data and see the email address for your Google Account.

`allowedRedirectUris[]`

`string`

Required. The list of redirect uris that is allowed to redirect back when authorization process is completed.

`expireTime`

` string ( Timestamp  ` format)

Output only. Time after which the `  OauthClient  ` will be permanently purged and cannot be recovered.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

## State

The current state of the `  OauthClient  ` .

Enums

`STATE_UNSPECIFIED`

Default value. This value is unused.

`ACTIVE`

The `  OauthClient  ` is active.

`DELETED`

The `  OauthClient  ` is soft-deleted. Soft-deleted `  OauthClient  ` is permanently deleted after approximately 30 days unless restored via `oauthClients.undelete` .

## ClientType

The type of `  OauthClient  ` .

Enums

`CLIENT_TYPE_UNSPECIFIED`

Should not be used.

`PUBLIC_CLIENT`

Public client has no secret.

`CONFIDENTIAL_CLIENT`

Private client.

## GrantType

The OAuth grant type.

Enums

`GRANT_TYPE_UNSPECIFIED`

Should not be used.

`AUTHORIZATION_CODE_GRANT`

Authorization code grant.

`REFRESH_TOKEN_GRANT`

Refresh token grant.

## Methods

### `            create           `

Creates a new `  OauthClient  ` .

### `            delete           `

Deletes an `  OauthClient  ` .

### `            get           `

Gets an individual `  OauthClient  ` .

### `            list           `

Lists all non-deleted `  OauthClient  ` s in a project.

### `            patch           `

Updates an existing `  OauthClient  ` .

### `            undelete           `

Undeletes an `  OauthClient  ` , as long as it was deleted fewer than 30 days ago.
