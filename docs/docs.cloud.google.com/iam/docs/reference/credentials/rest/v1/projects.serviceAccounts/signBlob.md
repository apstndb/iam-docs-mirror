---
name: documents/docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/signBlob
uri: https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/signBlob
title: 'Method: projects.serviceAccounts.signBlob'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/signBlob#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/signBlob#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/signBlob#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/signBlob#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/signBlob#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/signBlob#body.SignBlobResponse.SCHEMA_REPRESENTATION)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/signBlob#body.aspect)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/credentials/rest/v1/projects.serviceAccounts/signBlob#try-it)

Signs a blob using a service account's system-managed private key.

### HTTP request

`POST https://iamcredentials.googleapis.com/v1/{name=projects/*/serviceAccounts/*}:signBlob`

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
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>Required. The resource name of the service account for which the credentials are requested, in the following format: <code>projects/-/serviceAccounts/{ACCOUNT_EMAIL_OR_UNIQUEID}</code> . The <code>-</code> wildcard character is required; replacing it with a project ID is invalid.</p>
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
  "delegates": [
    string
  ],
  "payload": string
}
```

| Fields        |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `delegates[]` | `string` The sequence of service accounts in a delegation chain. Each service account must be granted the `roles/iam.serviceAccountTokenCreator` role on its next service account in the chain. The last service account in the chain must be granted the `roles/iam.serviceAccountTokenCreator` role on the service account that is specified in the `name` field of the request. The delegates must have the following format: `projects/-/serviceAccounts/{ACCOUNT_EMAIL_OR_UNIQUEID}` . The `-` wildcard character is required; replacing it with a project ID is invalid. |
| `payload`     | `string ( `[`bytes`](https://developers.google.com/discovery/v1/type-format)` format)` Required. The bytes to sign. A base64-encoded string.                                                                                                                                                                                                                                                                                                                                                                                                                                   |

### Response body

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "keyId": string,
  "signedBlob": string
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
<td><code>keyId</code></td>
<td><p><code>string</code></p>
<p>The ID of the key used to sign the blob. The key used for signing will remain valid for at least 12 hours after the blob is signed. To verify the signature, you can retrieve the public key in several formats from the following endpoints:</p>
<ul>
<li>RSA public key wrapped in an X.509 v3 certificate: <code>https://www.googleapis.com/service_accounts/v1/metadata/x509/{ACCOUNT_EMAIL}</code></li>
<li>Raw key in JSON format: <code>https://www.googleapis.com/service_accounts/v1/metadata/raw/{ACCOUNT_EMAIL}</code></li>
<li>JSON Web Key (JWK): <code>https://www.googleapis.com/service_accounts/v1/metadata/jwk/{ACCOUNT_EMAIL}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>signedBlob</code></td>
<td><p><code>string ( </code><a href="https://developers.google.com/discovery/v1/type-format"><code>bytes</code></a><code> format)</code></p>
<p>The signature for the blob. Does not include the original blob.</p>
<p>After the key pair referenced by the <code>keyId</code> response field expires, Google no longer exposes the public key that can be used to verify the blob. As a result, the receiver can no longer verify the signature.</p>
<p>A base64-encoded string.</p></td>
</tr>
</tbody>
</table>

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
