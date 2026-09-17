---
name: documents/docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/ExchangeTokenResponse
uri: https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/ExchangeTokenResponse
title: ExchangeTokenResponse
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/ExchangeTokenResponse#SCHEMA_REPRESENTATION)

Response message for `  common.token  ` . see [Response](https://www.rfc-editor.org/rfc/rfc6749#section-5.1)

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
  &quot;access_token&quot;: string,
  &quot;refresh_token&quot;: string,
  &quot;expires_in&quot;: integer,
  &quot;token_type&quot;: string,
  &quot;scope&quot;: string,
  &quot;id_token&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`access_token`

`string`

An OAuth 2.0 security token, issued by Google, in response to the OAuth token exchange request for the authorization code and refresh token flows.

The returned [access token](https://www.rfc-editor.org/rfc/rfc6749#section-4.1.4) . Tokens can vary in size, depending, in part, on the size of mapped claims, up to a maximum of 12288 bytes (12 KB). Google reserves the right to change the token size and the maximum length at any time.

`refresh_token`

`string`

A refresh token, issued by Google, in response to the OAuth token exchange request for the refresh token flow.

`expires_in`

`integer`

The amount of time, in seconds, between the time when the access token was issued and the time when the access token will expire.

`token_type`

`string`

The type of token. Field reserved for RFC compliance. See [Token Type](https://www.rfc-editor.org/rfc/rfc6749#section-5.1)

`scope`

`string`

A list of scopes associated with the returned token.

`id_token`

`string`

Google issued ID token in response to the OAuth token exchange request for ID token flow.
