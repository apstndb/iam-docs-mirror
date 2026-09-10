---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders
title: 'REST Resource: projects.locations.authProviders'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: AuthProvider](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders#AuthProvider)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders#AuthProvider.SCHEMA_REPRESENTATION)
  - [AuthProviderTypeParams](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders#AuthProviderTypeParams)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders#AuthProviderTypeParams.SCHEMA_REPRESENTATION)
  - [ThreeLeggedOAuth](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders#ThreeLeggedOAuth)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders#ThreeLeggedOAuth.SCHEMA_REPRESENTATION)
  - [TwoLeggedOAuth](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders#TwoLeggedOAuth)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders#TwoLeggedOAuth.SCHEMA_REPRESENTATION)
  - [ApiKeyParams](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders#ApiKeyParams)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders#ApiKeyParams.SCHEMA_REPRESENTATION)
  - [GeminiEnterpriseAuthProviderParams](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders#GeminiEnterpriseAuthProviderParams)
  - [State](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders#State)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders#METHODS_SUMMARY)

## Resource: AuthProvider

Represents an auth provider.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;createTime&quot;: string,&quot;updateTime&quot;: string,&quot;labels&quot;: {string: string,...},&quot;authProviderTypeParams&quot;: {object (AuthProviderTypeParams)},&quot;allowedScopes&quot;: [string],&quot;blockedScopes&quot;: [string],&quot;description&quot;: string,&quot;deleted&quot;: boolean,&quot;expireTime&quot;: string,&quot;state&quot;: enum (State),&quot;workloadIds&quot;: [string]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Identifier. The full resource name of the auth provider. Format: projects/{project}/locations/{location}/authProviders/{authProvider}

`createTime`

` string ( Timestamp  ` format)

Output only. The creation timestamp.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`updateTime`

` string ( Timestamp  ` format)

Output only. The update timestamp.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`labels`

`map (key: string, value: string)`

Optional. Labels as key-value pairs.

An object containing a list of `"key": value` pairs. Example: `{ "name": "wrench", "mass": "1.3kg", "count": "3" }` .

`authProviderTypeParams`

` object ( AuthProviderTypeParams  ` )

Required. Parameters specific to the auth provider type.

`allowedScopes[]`

`string`

Optional. List of scopes that are allowed to be requested for this auth provider. If this list is non-empty, only scopes within this list may be requested. If this list is empty, all scopes may be requested. Scopes appearing in `blockedScopes` are disallowed even if they appear in `allowedScopes` . The number of allowed scopes is limited to 200.

`blockedScopes[]`

`string`

Optional. List of scopes that are blocked from being requested for this auth provider. If a scope appears in this list, it will not be requested, even if it also appears in `allowedScopes` . `blockedScopes` takes precedence over `allowedScopes` . The number of blocked scopes is limited to 200.

`description`

`string`

Optional. Description of the resource. Must be less than 256 characters.

`deleted`

`boolean`

Output only. Set to `true` if the auth provider is deleted.

`expireTime`

` string ( Timestamp  ` format)

Output only. The time when the auth provider will expire.

Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: `"2014-10-02T15:01:23Z"` , `"2014-10-02T15:01:23.045123456Z"` or `"2014-10-02T15:01:23+05:30"` .

`state`

` enum ( State  ` )

Output only. The state of the auth provider.

`workloadIds[]`

`string`

Optional. Input only. Identifiers for the agents that will use this auth provider, starting with `principal://` . For example: `principal://agents.global.org-${ORG_ID}.system.id.goog/resources/aiplatform/projects/{PROJECT_ID}/locations/{LOCATIONS}/reasoningEngines/{ID}`

## AuthProviderTypeParams

Required. Parameters specific to the auth provider type.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{// Union field type can be only one of the following:&quot;threeLeggedOauth&quot;: {object (ThreeLeggedOAuth)},&quot;twoLeggedOauth&quot;: {object (TwoLeggedOAuth)},&quot;apiKey&quot;: {object (ApiKeyParams)},&quot;geAuthProvider&quot;: {object (GeminiEnterpriseAuthProviderParams)}// End of list of possible types for union field type.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

Union field `type` . The auth provider type. `type` can be only one of the following:

`threeLeggedOauth`

` object ( ThreeLeggedOAuth  ` )

Parameters for 3-legged OAuth (3LO) authentication.

`twoLeggedOauth`

` object ( TwoLeggedOAuth  ` )

Parameters for 2-legged OAuth (2LO) authentication.

`apiKey`

` object ( ApiKeyParams  ` )

Parameters for API key authentication.

`geAuthProvider`

` object ( GeminiEnterpriseAuthProviderParams  ` )

Parameters for Gemini Enterprise authentication.

## ThreeLeggedOAuth

Configuration for 3-legged OAuth (3LO) authentication.

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
  &quot;clientSecret&quot;: string,
  &quot;clientId&quot;: string,
  &quot;redirectUrl&quot;: string,
  &quot;authorizationUrl&quot;: string,
  &quot;tokenUrl&quot;: string,
  &quot;enablePkce&quot;: boolean,
  &quot;defaultContinueUri&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`clientSecret`

`string`

Optional. Input only. The client secret of the OAuth client.

`clientId`

`string`

Optional. The client ID of the OAuth client.

`redirectUrl`

`string`

Output only. The redirect URL this auth provider uses for the OAuth exchange. This is deterministic based on the name of the auth provider.

`authorizationUrl`

`string`

Optional. The authorization endpoint to send users to for consenting to delegate to the agent. For example, "https://auth.atlassian.com/authorize".

`tokenUrl`

`string`

Optional. The token endpoint for requesting tokens on behalf of an end user. For example, "https://auth.atlassian.com/oauth/token".

`enablePkce`

`boolean`

Optional. Enables Proof Key for Code Exchange (PKCE) for the OAuth flow to prevent authorization code interception attacks.

`defaultContinueUri`

`string`

Optional. The default continue URI for the 3LO flow, used when no continue URI is provided in the RetrieveCredentials request.

## TwoLeggedOAuth

Configuration for 2-legged OAuth (2LO) authentication.

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
  &quot;clientSecret&quot;: string,
  &quot;clientId&quot;: string,
  &quot;tokenUrl&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`clientSecret`

`string`

Optional. Input only. The client secret of the OAuth client.

`clientId`

`string`

Optional. The client ID of the OAuth client.

`tokenUrl`

`string`

Optional. The token endpoint of the OAuth client.

## ApiKeyParams

Configuration for API key authentication.

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
  &quot;apiKey&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`apiKey`

`string`

Optional. Input only. The API key for this auth provider.

## GeminiEnterpriseAuthProviderParams

This type has no fields.

Configuration for Gemini Enterprise authentication.

## State

Represents the state of the auth provider.

Enums

`STATE_UNSPECIFIED`

Unspecified state.

`ENABLED`

Enabled and can be used.

`DISABLED`

Disabled and cannot be used.

## Methods

### `            create           `

Creates a new auth provider in a given project and location.

### `            delete           `

Deletes a single auth provider.

### `            disable           `

Disables a single auth provider.

### `            enable           `

Enables a single auth provider.

### `            get           `

Gets details of a single auth provider.

### `            getIamPolicy           `

Gets the access control policy for a resource.

### `            list           `

Lists auth providers in a given project and location.

### `            patch           `

Updates the parameters of a single auth provider.

### `            query           `

Queries which auth providers are used by a given workload ID.

### `            queryWorkloads           `

Queries which workloads are using a given auth provider.

### `            revokeAuthorization           `

Revokes all authorizations for a specific user on an auth provider.

### `            setIamPolicy           `

Sets the access control policy on the specified resource.

### `            testIamPermissions           `

Returns permissions that a caller has on the specified resource.

### `            undelete           `

Undeletes a single auth provider.
