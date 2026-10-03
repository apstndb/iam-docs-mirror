---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/create
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/create
title: 'Method: projects.serviceAccounts.keys.create'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/create#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/create#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/create#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/create#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/create#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/create#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/create#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/create#try-it)

Creates a [`ServiceAccountKey`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountKey) .

### HTTP request

`POST https://iam.googleapis.com/v1/{name=projects/*/serviceAccounts/*}/keys`

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
<p>Required. The resource name of the service account.</p>
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
<li><code>iam.serviceAccountKeys.create</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "privateKeyType": enum (ServiceAccountPrivateKeyType),
  "keyAlgorithm": enum (ServiceAccountKeyAlgorithm)
}
```

| Fields           |                                                                                                                                                                                                                                                                                                             |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `privateKeyType` | `enum ( `[`ServiceAccountPrivateKeyType`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountPrivateKeyType)` )` The output format of the private key. The default value is `TYPE_GOOGLE_CREDENTIALS_FILE` , which is the Google Credentials File format. |
| `keyAlgorithm`   | `enum ( `[`ServiceAccountKeyAlgorithm`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountKeyAlgorithm)` )` Which type of key and algorithm to use for the key. The default is currently a 2K RSA key. However this may change in the future.            |

### Response body

If successful, the response body contains a newly created instance of [`ServiceAccountKey`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountKey) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
