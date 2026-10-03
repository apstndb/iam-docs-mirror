---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create
title: 'Method: projects.roles.create'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create#try-it)

Creates a new custom [`Role`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role) .

### HTTP request

`POST https://iam.googleapis.com/v1/{parent=projects/*}/roles`

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
<td><code>parent</code></td>
<td><p><code>string</code></p>
<p>The <code>parent</code> parameter's value depends on the target resource for the request, namely <a href="https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles">projects</a> or <a href="https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles">organizations</a> . Each resource type's <code>parent</code> value format is described below:</p>
<ul>
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create">projects.roles.create</a> : <code>projects/{PROJECT_ID}</code> . This method creates project-level <a href="https://cloud.google.com/iam/docs/understanding-custom-roles">custom roles</a> . Example request URL: <code>https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles</code></p></li>
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create">organizations.roles.create</a> : <code>organizations/{ORGANIZATION_ID}</code> . This method creates organization-level <a href="https://cloud.google.com/iam/docs/understanding-custom-roles">custom roles</a> . Example request URL: <code>https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles</code></p></li>
</ul>
<p>Note: Wildcard (*) values are invalid; you must specify a complete project ID or organization ID.</p>
<p>Authorization requires the following <a href="https://cloud.google.com/iam/docs/">IAM</a> permission on the specified resource <code>parent</code> :</p>
<ul>
<li><code>iam.roles.create</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "roleId": string,
  "role": {
    object (Role)
  }
}
```

| Fields   |                                                                                                                                                                                                               |
|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `roleId` | `string` The role ID to use for this role. A role ID may contain alphanumeric characters, underscores ( `_` ), and periods ( `.` ). It must contain a minimum of 3 characters and a maximum of 64 characters. |
| `role`   | `object ( `[`Role`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role)` )` The Role resource to create.                                                                       |

### Response body

If successful, the response body contains a newly created instance of [`Role`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
