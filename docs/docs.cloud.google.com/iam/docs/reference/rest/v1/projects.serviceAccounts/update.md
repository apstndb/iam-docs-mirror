---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/update
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/update
title: 'Method: projects.serviceAccounts.update'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/update#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/update#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/update#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/update#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/update#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/update#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/update#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/update#try-it)

**Note:** We are in the process of deprecating this method. Use [`serviceAccounts.patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/patch#google.iam.admin.v1.IAM.PatchServiceAccount) instead.

Updates a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .

You can update only the `displayName` field.

### HTTP request

`PUT https://iam.googleapis.com/v1/{name=projects/*/serviceAccounts/*}`

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
<p>When possible, avoid using the <code>-</code> wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account <code>projects/-/serviceAccounts/fake@example.com</code> , which does not exist, the response contains an HTTP <code>403 Forbidden</code> error instead of a <code>404 Not Found</code> error.</p></td>
</tr>
</tbody>
</table>

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "projectId": string,
  "uniqueId": string,
  "email": string,
  "displayName": string,
  "etag": string,
  "description": string,
  "oauth2ClientId": string,
  "disabled": boolean
}
```

| Fields                    |                                                                                                                                                                                                                                                                                                                                                         |
|---------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `projectId`               | `string` Output only. The ID of the project that owns the service account.                                                                                                                                                                                                                                                                              |
| `uniqueId`                | `string` Output only. The unique, stable numeric ID for the service account. Each service account retains its unique ID even if you delete the service account. For example, if you delete a service account, then create a new service account with the same name, the new service account has a different unique ID than the deleted service account. |
| `email`                   | `string` Output only. The email address of the service account.                                                                                                                                                                                                                                                                                         |
| `displayName`             | `string` Optional. A user-specified, human-readable name for the service account. The maximum length is 100 UTF-8 bytes.                                                                                                                                                                                                                                |
| `etag `**`(deprecated)`** | `string ( `[`bytes`](https://developers.google.com/discovery/v1/type-format)` format)` Deprecated. Do not use. A base64-encoded string.                                                                                                                                                                                                                 |
| `description`             | `string` Optional. A user-specified, human-readable description of the service account. The maximum length is 256 UTF-8 bytes.                                                                                                                                                                                                                          |
| `oauth2ClientId`          | `string` Output only. The OAuth 2.0 client ID for the service account.                                                                                                                                                                                                                                                                                  |
| `disabled`                | `boolean` Output only. Whether the service account is disabled.                                                                                                                                                                                                                                                                                         |

### Response body

If successful, the response body contains an instance of [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
