---
name: documents/docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/token
uri: https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/token
title: 'Method: organizations.token'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/token#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/token#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/token#body.request_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/token#body.request_body.SCHEMA_REPRESENTATION)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/token#body.response_body)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/token#try-it)

Exchanges a credential for a Google-generated [OAuth 2.0 access token](https://www.rfc-editor.org/rfc/rfc6749#section-5) or [refreshes an access token](https://www.rfc-editor.org/rfc/rfc6749#section-6) following the [OAuth 2.0 Authorization Framework](https://www.rfc-editor.org/rfc/rfc6749) .

This endpoint supports Google Cloud's unified OAuth flow, accommodating both federated users (for example, from Workforce Identity Federation) and Google Accounts for accessing Google Cloud resources.

The provided credential can be: - An authorization code issued by Google Cloud's unified authorization endpoint. - A refresh token previously issued by this token endpoint.

### HTTP request

`POST https://cloudoauth.googleapis.com/v1/{parent=organizations/*}/token`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Optional. The resource name of the parent organization. Format: `organizations/{organization_id}` This field is populated only for tenant-specific token requests.

### Request body

The request body contains data with the following structure:

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
  &quot;grantType&quot;: string,
  &quot;scope&quot;: string,
  &quot;clientId&quot;: string,
  &quot;redirectUri&quot;: string,
  &quot;codeVerifier&quot;: string,
  &quot;code&quot;: string,
  &quot;refreshToken&quot;: string,
  &quot;clientSecret&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`grantType`

`string`

Required. The grant types are as follows:

  - `authorization_code` : an authorization code flow, for example, exchange of authorization code for the OAuth access token

  - `refreshToken` : a refresh token flow, for example, obtain a new access token by providing the refresh token. See [Grant Type](https://www.rfc-editor.org/rfc/rfc6749#section-6)

`scope`

`string`

Optional. A list of scopes that are requested for the token to be returned. See [Scope](https://www.rfc-editor.org/rfc/rfc6749#section-3.3) . Must be a list of space-delimited, case-sensitive strings. Note: Currently, specifying scopes in the request is not supported.

`clientId`

`string`

Optional. The client identifier for the OAuth 2.0 client that requested the provided token. It is required when the [client](https://www.rfc-editor.org/rfc/rfc6749#section-1.1) is not authenticating with the authorization server, for example, when authentication method is [client authentication](https://www.rfc-editor.org/rfc/rfc6749#section-3.2.1) .

`redirectUri`

`string`

Optional. The redirect URI. Required if `grantType` is `authorization_code` . See [Redirect URI](https://www.rfc-editor.org/rfc/rfc6749#section-4.1.3)

`codeVerifier`

`string`

Optional. The code verifier for the PKCE request. Application (Client) originally generates it before the authorization request. PKCE is used to protect authorization code from interception attacks. See [PKCE](https://www.rfc-editor.org/rfc/rfc7636#section-1.1) and [PKCE](https://www.rfc-editor.org/rfc/rfc7636#section-3) . Required if `grantType` is `authorization_code` .

`code`

`string`

Optional. The authorization code that was previously obtained from Google Cloud's unified authorization endpoint. Required if the flow is authorization code flow, for example, if `grantType` is `authorization_code` .

`refreshToken`

`string`

Optional. Credential used to obtain a new access token when the current access token becomes invalid or expires. Required when using refresh token flow, for example, if `grantType` is `refreshToken` . See [Refresh Token Grant](https://www.rfc-editor.org/rfc/rfc6749#section-1.5) and [Refresh Token](https://www.rfc-editor.org/rfc/rfc6749#section-6)

`clientSecret`

`string`

Optional. To use a client secret for client authentication in the request-body, the client uses the `clientSecret` parameter. Otherwise, leave this parameter unset to use HTTP Basic authentication.

Note: According to the RFC, the client must not use more than one authentication method for any given request; using both will result in an error. Also, it is recommended to use the HTTP Basic authentication scheme instead of this parameter, if feasible.

For more information, see <https://datatracker.ietf.org/doc/html/rfc6749#section-2.3.1>

### Response body

If successful, the response body contains an instance of `  ExchangeTokenResponse  ` .
