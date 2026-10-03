---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list
title: 'Method: projects.serviceAccounts.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list#body.ListServiceAccountsResponse.SCHEMA_REPRESENTATION)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list#try-it)

Lists every [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) that belongs to a specific project.

### HTTP request

`GET https://iam.googleapis.com/v1/{name=projects/*}/serviceAccounts`

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
<p>Required. The resource name of the project associated with the service accounts, such as <code>projects/my-project-123</code> .</p>
<p>Authorization requires the following <a href="https://cloud.google.com/iam/docs/">IAM</a> permission on the specified resource <code>name</code> :</p>
<ul>
<li><code>iam.serviceAccounts.list</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Query parameters

| Parameters  |                                                                                                                                                                                                                                                                                                                                                                                                                           |
|-------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `pageSize`  | `integer` Optional limit on the number of service accounts to include in the response. Further accounts can subsequently be obtained by including the [`ListServiceAccountsResponse.next_page_token`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list#body.ListServiceAccountsResponse.FIELDS.next_page_token) in a subsequent request. The default is 20, and the maximum is 100. |
| `pageToken` | `string` Optional pagination token returned in an earlier [`ListServiceAccountsResponse.next_page_token`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list#body.ListServiceAccountsResponse.FIELDS.next_page_token) .                                                                                                                                                               |

### Request body

The request body must be empty.

### Response body

The service account list response.

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "accounts": [
    {
      object (ServiceAccount)
    }
  ],
  "nextPageToken": string
}
```

| Fields          |                                                                                                                                                                                                                                      |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `accounts[]`    | `object ( `[`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount)` )` The list of matching service accounts.                                                           |
| `nextPageToken` | `string` To retrieve the next page of results, set [`ListServiceAccountsRequest.page_token`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list#body.QUERY_PARAMETERS.page_token) to this value. |

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
