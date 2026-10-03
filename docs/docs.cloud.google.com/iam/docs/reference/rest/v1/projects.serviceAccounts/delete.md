---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/delete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/delete
title: 'Method: projects.serviceAccounts.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/delete#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/delete#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/delete#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/delete#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/delete#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/delete#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/delete#try-it)

Deletes a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .

**Warning:** After you delete a service account, you might not be able to undelete it. If you know that you need to re-enable the service account in the future, use [`serviceAccounts.disable`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/disable#google.iam.admin.v1.IAM.DisableServiceAccount) instead.

If you delete a service account, IAM permanently removes the service account 30 days later. Google Cloud cannot recover the service account after it is permanently removed, even if you file a support request.

To help avoid unplanned outages, we recommend that you disable the service account before you delete it. Use [`serviceAccounts.disable`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/disable#google.iam.admin.v1.IAM.DisableServiceAccount) to disable the service account, then wait at least 24 hours and watch for unintended consequences. If there are no unintended consequences, you can delete the service account.

### HTTP request

`DELETE https://iam.googleapis.com/v1/{name=projects/*/serviceAccounts/*}`

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
<li><code>iam.serviceAccounts.delete</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Request body

The request body must be empty.

### Response body

If successful, the response body is an empty JSON object.

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
