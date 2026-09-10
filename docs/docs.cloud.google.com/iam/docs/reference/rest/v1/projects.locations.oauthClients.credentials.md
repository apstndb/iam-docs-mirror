---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials
title: 'REST Resource: projects.locations.oauthClients.credentials'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: OauthClientCredential](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#OauthClientCredential.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients.credentials#METHODS_SUMMARY)

## Resource: OauthClientCredential

Represents an `  OauthClientCredential  ` . Used to authenticate an `  OauthClient  ` while accessing Google Cloud resources on behalf of a user by using OAuth 2.0 Protocol.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;disabled&quot;: boolean,&quot;displayName&quot;: string,// Union field credential can be only one of the following:&quot;clientSecret&quot;: string// End of list of possible types for union field credential.}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

Immutable. Identifier. The resource name of the `  OauthClientCredential  ` .

Format: `projects/{project}/locations/{location}/oauthClients/{oauthClient}/credentials/{credential}`

`disabled`

`boolean`

Optional. Whether the `  OauthClientCredential  ` is disabled. You cannot use a disabled `  OauthClientCredential  ` .

`displayName`

`string`

Optional. A user-specified display name of the `  OauthClientCredential  ` .

Cannot exceed 32 characters.

Union field `credential` .

`credential` can be only one of the following:

`clientSecret`

`string`

Output only. The system-generated OAuth client secret.

The client secret must be stored securely. If the client secret is leaked, you must delete and re-create the client credential. To learn more, see [OAuth client and credential security risks and mitigations](https://cloud.google.com/iam/docs/workforce-oauth-app#security)

## Methods

### `            create           `

Creates a new `  OauthClientCredential  ` .

### `            delete           `

Deletes an `  OauthClientCredential  ` .

### `            get           `

Gets an individual `  OauthClientCredential  ` .

### `            list           `

Lists all `  OauthClientCredential  ` s in an `  OauthClient  ` .

### `            patch           `

Updates an existing `  OauthClientCredential  ` .
