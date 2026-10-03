---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/list
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/list
title: 'Method: projects.serviceAccounts.keys.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/list#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/list#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/list#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/list#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/list#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/list#body.ListServiceAccountKeysResponse.SCHEMA_REPRESENTATION)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/list#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/list#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys/list#try-it)

Lists every [`ServiceAccountKey`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountKey) for a service account.

### HTTP request

`GET https://iam.googleapis.com/v1/{name=projects/*/serviceAccounts/*}/keys`

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
<li><code>iam.serviceAccountKeys.list</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Query parameters

| Parameters   |                                                                                                                                                                                                                                                                                            |
|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `keyTypes[]` | `enum ( `[`KeyType`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#KeyType)` )` Filters the types of keys the user wants to include in the list response. Duplicate key types are not allowed. If no key type is provided, all keys are returned. |

### Request body

The request body must be empty.

### Response body

The service account keys list response.

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "keys": [
    {
      object (ServiceAccountKey)
    }
  ]
}
```

| Fields   |                                                                                                                                                                                         |
|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `keys[]` | `object ( `[`ServiceAccountKey`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts.keys#ServiceAccountKey)` )` The public keys for the service account. |

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
