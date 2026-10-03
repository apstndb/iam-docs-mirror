---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signBlob
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signBlob
title: 'Method: projects.serviceAccounts.signBlob'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signBlob#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signBlob#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signBlob#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signBlob#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signBlob#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signBlob#body.SignBlobResponse.SCHEMA_REPRESENTATION)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signBlob#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signBlob#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signBlob#try-it)

> This method is deprecated. Use the [signBlob](https://cloud.google.com/iam/help/rest-credentials/v1/projects.serviceAccounts/signBlob) method in the IAM Service Account Credentials API instead. If you currently use this method, see the [migration guide](https://cloud.google.com/iam/help/credentials/migrate-api) for instructions.

Signs a blob using the system-managed private key for a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .

### HTTP request

`POST https://iam.googleapis.com/v1/{name=projects/*/serviceAccounts/*}:signBlob`

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
<li><code>iam.serviceAccounts.signBlob</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "bytesToSign": string
}
```

| Fields                           |                                                                                                                                                                                                                                                                    |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `bytesToSign `**`(deprecated)`** | `string ( `[`bytes`](https://developers.google.com/discovery/v1/type-format)` format)` Required. Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) . The bytes to sign. A base64-encoded string. |

### Response body

Deprecated. [Migrate to Service Account Credentials API](https://cloud.google.com/iam/help/credentials/migrate-api) .

The service account sign blob response.

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "keyId": string,
  "signature": string
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
<p>The id of the key used to sign the blob.</p></td>
</tr>
<tr class="even">
<td><code>signature </code><strong><code>(deprecated)</code></strong></td>
<td><p><code>string ( </code><a href="https://developers.google.com/discovery/v1/type-format"><code>bytes</code></a><code> format)</code></p>
<blockquote>
<p>This item is deprecated!</p>
</blockquote>
<p>Deprecated. <a href="https://cloud.google.com/iam/help/credentials/migrate-api">Migrate to Service Account Credentials API</a> .</p>
<p>The signed blob.</p>
<p>A base64-encoded string.</p></td>
</tr>
</tbody>
</table>

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
