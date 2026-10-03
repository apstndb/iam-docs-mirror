---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signJwt
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signJwt
title: 'Method: projects.serviceAccounts.signJwt'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signJwt#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signJwt#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signJwt#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signJwt#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signJwt#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signJwt#body.SignJwtResponse.SCHEMA_REPRESENTATION)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signJwt#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signJwt#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signJwt#try-it)

> This method is deprecated. Use the [signJwt](https://cloud.google.com/iam/help/rest-credentials/v1/projects.serviceAccounts/signJwt) method in the IAM Service Account Credentials API instead. If you currently use this method, see the [migration guide](https://cloud.google.com/iam/help/credentials/migrate-api) for instructions.

Signs a JSON Web Token (JWT) using the system-managed private key for a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .

### HTTP request

`POST https://iam.googleapis.com/v1/{name=projects/*/serviceAccounts/*}:signJwt`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Parameters</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>name </code><strong><code>(deprecated)</code></strong></td>
<td><p><code>string</code></p>
<p>Required. Deprecated. <a href="https://cloud.google.com/iam/help/credentials/migrate-api">Migrate to Service Account Credentials API</a> .</p>
<p>The resource name of the service account.</p>
<p>Use one of the following formats:</p>
<ul>
<li><code>projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}</code></li>
<li><code>projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}</code></li>
</ul>
<p>As an alternative, you can use the <code>-</code> wildcard character instead of the project ID:</p>
<ul>
<li><code>projects/-/serviceAccounts/{EMAIL_ADDRESS}</code></li>
<li><code>projects/-/serviceAccounts/{UNIQUE_ID}</code></li>
</ul>
<p>When possible, avoid using the <code>-</code> wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account <code>projects/-/serviceAccounts/fake@example.com</code> , which does not exist, the response contains an HTTP <code>403 Forbidden</code> error instead of a <code>404 Not Found</code> error.</p>
<p>Authorization requires the following <a href="https://cloud.google.com/iam/docs/">IAM</a> permission on the specified resource <code>name</code> :</p>
<ul>
<li><code>iam.serviceAccounts.signJwt</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "payload": string
}
```

| Fields                       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `payload `**`(deprecated)`** | `string` Required. Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) . The JWT payload to sign. Must be a serialized JSON object that contains a JWT Claims Set. For example: `{"sub": "user@example.com", "iat": 313435}` If the JWT Claims Set contains an expiration time ( `exp` ) claim, it must be an integer timestamp that is not in the past and no more than 12 hours in the future. If the JWT Claims Set does not contain an expiration time ( `exp` ) claim, this claim is added automatically, with a timestamp that is 1 hour in the future. |

### Response body

Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The service account sign JWT response.

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "keyId": string,
  "signedJwt": string
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
<td><code>keyId </code><strong><code>(deprecated)</code></strong></td>
<td><p><code>string</code></p>
<blockquote>
<p>This item is deprecated!</p>
</blockquote>
<p>Deprecated. <a href="https://cloud.google.com/iam/help/credentials/migrate-api">Migrate to Service Account Credentials API</a> .</p>
<p>The id of the key used to sign the JWT.</p></td>
</tr>
<tr class="even">
<td><code>signedJwt </code><strong><code>(deprecated)</code></strong></td>
<td><p><code>string</code></p>
<blockquote>
<p>This item is deprecated!</p>
</blockquote>
<p>Deprecated. <a href="https://cloud.google.com/iam/help/credentials/migrate-api">Migrate to Service Account Credentials API</a> .</p>
<p>The signed JWT.</p></td>
</tr>
</tbody>
</table>

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
