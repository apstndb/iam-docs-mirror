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

Represents an [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) . Used to access Google Cloud resources on behalf of a Workforce Identity Federation user by using OAuth 2.0 Protocol to obtain an access token from Google Cloud.

**JSON representation**

```
{
  "name": string,
  "state": enum (State),
  "disabled": boolean,
  "clientId": string,
  "displayName": string,
  "description": string,
  "clientType": enum (ClientType),
  "allowedGrantTypes": [
    enum (GrantType)
  ],
  "allowedScopes": [
    string
  ],
  "allowedRedirectUris": [
    string
  ],
  "expireTime": string
}
```

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
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>Immutable. Identifier. The resource name of the <a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient"><code>OauthClient</code></a> .</p>
<p>Format: <code>projects/{project}/locations/{location}/oauthClients/{oauthClient}</code> .</p></td>
</tr>
<tr class="even">
<td><code>state</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#State"><code>State</code></a><code> )</code></p>
<p>Output only. The state of the <a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient"><code>OauthClient</code></a> .</p></td>
</tr>
<tr class="odd">
<td><code>disabled</code></td>
<td><p><code>boolean</code></p>
<p>Optional. Whether the <a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient"><code>OauthClient</code></a> is disabled. You cannot use a disabled OAuth client.</p></td>
</tr>
<tr class="even">
<td><code>clientId</code></td>
<td><p><code>string</code></p>
<p>Output only. The system-generated <a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient"><code>OauthClient</code></a> id.</p></td>
</tr>
<tr class="odd">
<td><code>displayName</code></td>
<td><p><code>string</code></p>
<p>Optional. A user-specified display name of the <a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient"><code>OauthClient</code></a> .</p>
<p>Cannot exceed 32 characters.</p></td>
</tr>
<tr class="even">
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>Optional. A user-specified description of the <a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient"><code>OauthClient</code></a> .</p>
<p>Cannot exceed 256 characters.</p></td>
</tr>
<tr class="odd">
<td><code>clientType</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#ClientType"><code>ClientType</code></a><code> )</code></p>
<p>Immutable. The type of <a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient"><code>OauthClient</code></a> . Either public or private. For private clients, the client secret can be managed using the dedicated <a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential"><code>OauthClientCredential</code></a> resource.</p></td>
</tr>
<tr class="even">
<td><code>allowedGrantTypes[]</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#GrantType"><code>GrantType</code></a><code> )</code></p>
<p>Required. The list of OAuth grant types is allowed for the <a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient"><code>OauthClient</code></a> .</p></td>
</tr>
<tr class="odd">
<td><code>allowedScopes[]</code></td>
<td><p><code>string</code></p>
<p>Required. The list of scopes that the <a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient"><code>OauthClient</code></a> is allowed to request during OAuth flows.</p>
<p>The following scopes are supported:</p>
<ul>
<li><code>https://www.googleapis.com/auth/cloud-platform</code> : See, edit, configure, and delete your Google Cloud data and see the email address for your Google Account.</li>
</ul></td>
</tr>
<tr class="even">
<td><code>allowedRedirectUris[]</code></td>
<td><p><code>string</code></p>
<p>Required. The list of redirect uris that is allowed to redirect back when authorization process is completed.</p></td>
</tr>
<tr class="odd">
<td><code>expireTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. Time after which the <a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient"><code>OauthClient</code></a> will be permanently purged and cannot be recovered.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
</tbody>
</table>

## State

The current state of the [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) .

| Enums               |                                                                                                                                                                                                                                                                                                                                                                                |
|---------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `STATE_UNSPECIFIED` | Default value. This value is unused.                                                                                                                                                                                                                                                                                                                                           |
| `ACTIVE`            | The [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) is active.                                                                                                                                                                                                                                           |
| `DELETED`           | The [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) is soft-deleted. Soft-deleted [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) is permanently deleted after approximately 30 days unless restored via `oauthClients.undelete` . |

## ClientType

The type of [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) .

| Enums                     |                              |
|---------------------------|------------------------------|
| `CLIENT_TYPE_UNSPECIFIED` | Should not be used.          |
| `PUBLIC_CLIENT`           | Public client has no secret. |
| `CONFIDENTIAL_CLIENT`     | Private client.              |

## GrantType

The OAuth grant type.

| Enums                      |                           |
|----------------------------|---------------------------|
| `GRANT_TYPE_UNSPECIFIED`   | Should not be used.       |
| `AUTHORIZATION_CODE_GRANT` | Authorization code grant. |
| `REFRESH_TOKEN_GRANT`      | Refresh token grant.      |

| Methods                                                                                                         |                                                                                                                                                                                        |
|-----------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/create)     | Creates a new [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) .                                                  |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/delete)     | Deletes an [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) .                                                     |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/get)           | Gets an individual [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) .                                             |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/list)         | Lists all non-deleted [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) s in a project.                            |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/patch)       | Updates an existing [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) .                                            |
| [`undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/undelete) | Undeletes an [`OauthClient`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients#OauthClient) , as long as it was deleted fewer than 30 days ago. |
