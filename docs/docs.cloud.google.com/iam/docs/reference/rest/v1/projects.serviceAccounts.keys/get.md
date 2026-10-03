---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get
title: 'Method: projects.serviceAccounts.keys.get'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#body.aspect)
- [ServiceAccountPublicKeyType](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#ServiceAccountPublicKeyType)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#try-it)

Gets a [`ServiceAccountKey`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountKey) .

### HTTP request

`GET https://iam.googleapis.com/v1/{name=projects/*/serviceAccounts/*/keys/*}`

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
<p>Required. The resource name of the service account key.</p>
<p>Use one of the following formats:</p>
<ul>
<li><code>projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}/keys/{KEY_ID}</code></li>
<li><code>projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}/keys/{KEY_ID}</code></li>
</ul>
<p>As an alternative, you can use the <code>-</code> wildcard character instead of the project ID:</p>
<ul>
<li><code>projects/-/serviceAccounts/{EMAIL_ADDRESS}/keys/{KEY_ID}</code></li>
<li><code>projects/-/serviceAccounts/{UNIQUE_ID}/keys/{KEY_ID}</code></li>
</ul>
<p>When possible, avoid using the <code>-</code> wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account key <code>projects/-/serviceAccounts/fake@example.com/keys/fake-key</code> , which does not exist, the response contains an HTTP <code>403 Forbidden</code> error instead of a <code>404 Not Found</code> error.</p>
<p>Authorization requires the following <a href="https://cloud.google.com/iam/docs/">IAM</a> permission on the specified resource <code>name</code> :</p>
<ul>
<li><code>iam.serviceAccountKeys.get</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Query parameters

| Parameters      |                                                                                                                                                                                                                                                                                                   |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `publicKeyType` | `enum ( `[`ServiceAccountPublicKeyType`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/get#ServiceAccountPublicKeyType)` )` Optional. The output format of the public key. The default is `TYPE_NONE` , which means that the public key is not returned. |

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of [`ServiceAccountKey`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountKey) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

## ServiceAccountPublicKeyType

Supported public key output formats.

| Enums                 |                               |
|-----------------------|-------------------------------|
| `TYPE_NONE`           | Do not return the public key. |
| `TYPE_X509_PEM_FILE`  | X509 PEM format.              |
| `TYPE_RAW_PUBLIC_KEY` | raw public key.               |
