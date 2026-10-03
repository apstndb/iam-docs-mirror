---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list
title: 'Method: organizations.roles.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list#try-it)

Lists every predefined [`Role`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles#Role) that IAM supports, or every custom role that is defined for an organization or project.

### HTTP request

`GET https://iam.googleapis.com/v1/{parent=organizations/*}/roles`

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
<p>The <code>parent</code> parameter's value depends on the target resource for the request, namely <a href="https://cloud.google.com/iam/docs/reference/rest/v1/roles">roles</a> , <a href="https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles">projects</a> , or <a href="https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles">organizations</a> . Each resource type's <code>parent</code> value format is described below:</p>
<ul>
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/roles/list">roles.list</a> : An empty string. This method doesn't require a resource; it simply returns all <a href="https://cloud.google.com/iam/docs/understanding-roles#predefined_roles">predefined roles</a> in IAM. Example request URL: <code>https://iam.googleapis.com/v1/roles</code></p></li>
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/list">projects.roles.list</a> : <code>projects/{PROJECT_ID}</code> . This method lists all project-level <a href="https://cloud.google.com/iam/docs/understanding-custom-roles">custom roles</a> . Example request URL: <code>https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles</code></p></li>
<li><p><a href="https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list">organizations.roles.list</a> : <code>organizations/{ORGANIZATION_ID}</code> . This method lists all organization-level <a href="https://cloud.google.com/iam/docs/understanding-custom-roles">custom roles</a> . Example request URL: <code>https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles</code></p></li>
</ul>
<p>Note: Wildcard (*) values are invalid; you must specify a complete project ID or organization ID.</p>
<p>Authorization requires the following <a href="https://cloud.google.com/iam/docs/">IAM</a> permission on the specified resource <code>parent</code> :</p>
<ul>
<li><code>iam.roles.list</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Query parameters

| Parameters    |                                                                                                                                                                                                                                                                                                                                                              |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `pageSize`    | `integer` Optional limit on the number of roles to include in the response. The default is 300, and the maximum is 1,000.                                                                                                                                                                                                                                    |
| `pageToken`   | `string` Optional pagination token returned in an earlier ListRolesResponse.                                                                                                                                                                                                                                                                                 |
| `view`        | `enum ( `[`RoleView`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/RoleView)` )` Optional view for the returned Role objects. When `FULL` is specified, the `includedPermissions` field is returned, which includes a list of all permissions in the role. The default value is `BASIC` , which does not return the `includedPermissions` field. |
| `showDeleted` | `boolean` Include Roles that have been deleted.                                                                                                                                                                                                                                                                                                              |

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of [`ListRolesResponse`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/ListRolesResponse) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
