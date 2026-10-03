---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/delete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/delete
title: 'Method: projects.roles.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/delete#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/delete#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/delete#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/delete#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/delete#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/delete#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/delete#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/delete#try-it)

Deletes a custom [`Role`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role) .

When you delete a custom role, the following changes occur immediately:

- You cannot bind a principal to the custom role in an IAM [`Policy`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/Policy) .
- Existing bindings to the custom role are not changed, but they have no effect.
- By default, the response from [`roles.list`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/list#google.iam.admin.v1.IAM.ListRoles) does not include the custom role.

A deleted custom role still counts toward the [custom role limit](https://cloud.google.com/iam/help/limits) until it is permanently deleted. You have 7 days to undelete the custom role. After 7 days, the following changes occur:

- The custom role is permanently deleted and cannot be recovered.
- If an IAM policy contains a binding to the custom role, the binding is permanently removed.
- The custom role no longer counts toward your custom role limit.

### HTTP request

`DELETE https://iam.googleapis.com/v1/{name=projects/*/roles/*}`

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
<p>The <code>name</code> parameter's value depends on the target resource for the request, namely <a href="https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles">projects</a> or <a href="https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles">organizations</a> . Each resource type's <code>name</code> value format is described below:</p>
<ul>
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/delete">projects.roles.delete</a> : <code>projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}</code> . This method deletes only <a href="https://cloud.google.com/iam/docs/understanding-custom-roles">custom roles</a> that have been created at the project level. Example request URL: <code>https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}</code></p></li>
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/delete">organizations.roles.delete</a> : <code>organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}</code> . This method deletes only <a href="https://cloud.google.com/iam/docs/understanding-custom-roles">custom roles</a> that have been created at the organization level. Example request URL: <code>https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}</code></p></li>
</ul>
<p>Note: Wildcard (*) values are invalid; you must specify a complete project ID or organization ID.</p>
<p>Authorization requires the following <a href="https://cloud.google.com/iam/docs/">IAM</a> permission on the specified resource <code>name</code> :</p>
<ul>
<li><code>iam.roles.delete</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Query parameters

| Parameters |                                                                                                                                                                 |
|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `etag`     | `string ( `[`bytes`](https://developers.google.com/discovery/v1/type-format)` format)` Used to perform a consistent read-modify-write. A base64-encoded string. |

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of [`Role`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
