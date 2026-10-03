---
name: documents/docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/token
uri: https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/token
title: 'Method: common.token'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/token#body.HTTP_TEMPLATE)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/token#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/token#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/token#body.response_body)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/token#try-it)

Exchanges a credential for a Google-generated [OAuth 2.0 access token](https://www.rfc-editor.org/rfc/rfc6749#section-5) or [refreshes an access token](https://www.rfc-editor.org/rfc/rfc6749#section-6) following the [OAuth 2.0 Authorization Framework](https://www.rfc-editor.org/rfc/rfc6749) .

This endpoint supports Google Cloud's unified OAuth flow, accommodating both federated users (for example, from Workforce Identity Federation) and Google Accounts for accessing Google Cloud resources.

The provided credential can be: - An authorization code issued by Google Cloud's unified authorization endpoint. - A refresh token previously issued by this token endpoint.

### HTTP request

`POST https://cloudoauth.googleapis.com/v1/common/token`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "grantType": string,
  "scope": string,
  "clientId": string,
  "redirectUri": string,
  "codeVerifier": string,
  "code": string,
  "refreshToken": string,
  "clientSecret": string,
  "parent": string
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
<td><code>grantType</code></td>
<td><p><code>string</code></p>
<p>Required. The grant types are as follows:</p>
<ul>
<li><p><code>authorization_code</code> : an authorization code flow, for example, exchange of authorization code for the OAuth access token</p></li>
<li><p><code>refreshToken</code> : a refresh token flow, for example, obtain a new access token by providing the refresh token. See <a href="https://www.rfc-editor.org/rfc/rfc6749#section-6">Grant Type</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><code>scope</code></td>
<td><p><code>string</code></p>
<p>Optional. A list of scopes that are requested for the token to be returned. See <a href="https://www.rfc-editor.org/rfc/rfc6749#section-3.3">Scope</a> . Must be a list of space-delimited, case-sensitive strings. Note: Currently, specifying scopes in the request is not supported.</p></td>
</tr>
<tr class="odd">
<td><code>clientId</code></td>
<td><p><code>string</code></p>
<p>Optional. The client identifier for the OAuth 2.0 client that requested the provided token. It is required when the <a href="https://www.rfc-editor.org/rfc/rfc6749#section-1.1">client</a> is not authenticating with the authorization server, for example, when authentication method is <a href="https://www.rfc-editor.org/rfc/rfc6749#section-3.2.1">client authentication</a> .</p></td>
</tr>
<tr class="even">
<td><code>redirectUri</code></td>
<td><p><code>string</code></p>
<p>Optional. The redirect URI. Required if <code>grantType</code> is <code>authorization_code</code> . See <a href="https://www.rfc-editor.org/rfc/rfc6749#section-4.1.3">Redirect URI</a></p></td>
</tr>
<tr class="odd">
<td><code>codeVerifier</code></td>
<td><p><code>string</code></p>
<p>Optional. The code verifier for the PKCE request. Application (Client) originally generates it before the authorization request. PKCE is used to protect authorization code from interception attacks. See <a href="https://www.rfc-editor.org/rfc/rfc7636#section-1.1">PKCE</a> and <a href="https://www.rfc-editor.org/rfc/rfc7636#section-3">PKCE</a> . Required if <code>grantType</code> is <code>authorization_code</code> .</p></td>
</tr>
<tr class="even">
<td><code>code</code></td>
<td><p><code>string</code></p>
<p>Optional. The authorization code that was previously obtained from Google Cloud's unified authorization endpoint. Required if the flow is authorization code flow, for example, if <code>grantType</code> is <code>authorization_code</code> .</p></td>
</tr>
<tr class="odd">
<td><code>refreshToken</code></td>
<td><p><code>string</code></p>
<p>Optional. Credential used to obtain a new access token when the current access token becomes invalid or expires. Required when using refresh token flow, for example, if <code>grantType</code> is <code>refreshToken</code> . See <a href="https://www.rfc-editor.org/rfc/rfc6749#section-1.5">Refresh Token Grant</a> and <a href="https://www.rfc-editor.org/rfc/rfc6749#section-6">Refresh Token</a></p></td>
</tr>
<tr class="even">
<td><code>clientSecret</code></td>
<td><p><code>string</code></p>
<p>Optional. To use a client secret for client authentication in the request-body, the client uses the <code>clientSecret</code> parameter. Otherwise, leave this parameter unset to use HTTP Basic authentication.</p>
<p>Note: According to the RFC, the client must not use more than one authentication method for any given request; using both will result in an error. Also, it is recommended to use the HTTP Basic authentication scheme instead of this parameter, if feasible.</p>
<p>For more information, see <a href="https://datatracker.ietf.org/doc/html/rfc6749#section-2.3.1">https://datatracker.ietf.org/doc/html/rfc6749#section-2.3.1</a></p></td>
</tr>
<tr class="odd">
<td><code>parent</code></td>
<td><p><code>string</code></p>
<p>Optional. The resource name of the parent organization. Format: <code>organizations/{organization_id}</code> This field is populated only for tenant-specific token requests.</p></td>
</tr>
</tbody>
</table>

### Response body

If successful, the response body contains an instance of [`ExchangeTokenResponse`](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/ExchangeTokenResponse) .
