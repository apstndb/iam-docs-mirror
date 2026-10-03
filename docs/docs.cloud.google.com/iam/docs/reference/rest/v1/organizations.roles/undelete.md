---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/undelete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/undelete
title: 'Method: organizations.roles.undelete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/undelete#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/undelete#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/undelete#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/undelete#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/undelete#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/undelete#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/undelete#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/undelete#try-it)

Undeletes a custom [`Role`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role) .

### HTTP request

`POST https://iam.googleapis.com/v1/{name=organizations/*/roles/*}:undelete`

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
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/undelete">projects.roles.undelete</a> : <code>projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}</code> . This method undeletes only <a href="https://cloud.google.com/iam/docs/understanding-custom-roles">custom roles</a> that have been created at the project level. Example request URL: <code>https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}</code></p></li>
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/undelete">organizations.roles.undelete</a> : <code>organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}</code> . This method undeletes only <a href="https://cloud.google.com/iam/docs/understanding-custom-roles">custom roles</a> that have been created at the organization level. Example request URL: <code>https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}</code></p></li>
</ul>
<p>Note: Wildcard (*) values are invalid; you must specify a complete project ID or organization ID.</p>
<p>Authorization requires the following <a href="https://cloud.google.com/iam/docs/">IAM</a> permission on the specified resource <code>name</code> :</p>
<ul>
<li><code>iam.roles.undelete</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "etag": string
}
```

| Fields |                                                                                                                                                                 |
|--------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `etag` | `string ( `[`bytes`](https://developers.google.com/discovery/v1/type-format)` format)` Used to perform a consistent read-modify-write. A base64-encoded string. |

### Response body

If successful, the response body contains an instance of [`Role`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
