---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions
title: 'Method: permissions.queryTestablePermissions'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#body.HTTP_TEMPLATE)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#body.request_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#body.request_body.SCHEMA_REPRESENTATION)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#body.response_body)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#body.QueryTestablePermissionsResponse.SCHEMA_REPRESENTATION)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#body.aspect)
- [Permission](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#Permission)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#Permission.SCHEMA_REPRESENTATION)
- [PermissionLaunchStage](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#PermissionLaunchStage)
- [CustomRolesSupportLevel](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#CustomRolesSupportLevel)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#try-it)

Lists every permission that you can test on a resource. A permission is testable if you can check whether a principal has that permission on the resource.

### HTTP request

`POST https://iam.googleapis.com/v1/permissions:queryTestablePermissions`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Request body

The request body contains data with the following structure:

**JSON representation**

```
{
  "fullResourceName": string,
  "pageSize": integer,
  "pageToken": string
}
```

| Fields             |                                                                                                                                                                                                                                                                                              |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `fullResourceName` | `string` Required. The full resource name to query from the list of testable permissions. The name follows the Google Cloud Platform resource format. For example, a Cloud Platform project with id `my-project` will be named `//cloudresourcemanager.googleapis.com/projects/my-project` . |
| `pageSize`         | `integer` Optional limit on the number of permissions to include in the response. The default is 100, and the maximum is 1,000.                                                                                                                                                              |
| `pageToken`        | `string` Optional pagination token returned in an earlier QueryTestablePermissionsRequest.                                                                                                                                                                                                   |

### Response body

The response containing permissions which can be tested on a resource.

If successful, the response body contains data with the following structure:

**JSON representation**

```
{
  "permissions": [
    {
      object (Permission)
    }
  ],
  "nextPageToken": string
}
```

| Fields          |                                                                                                                                                                                             |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `permissions[]` | `object ( `[`Permission`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#Permission)` )` The Permissions testable on the requested resource. |
| `nextPageToken` | `string` To retrieve the next page of results, set `QueryTestableRolesRequest.page_token` to this value.                                                                                    |

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/iam`
- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

## Permission

A permission which can be included by a role.

**JSON representation**

```
{
  "name": string,
  "title": string,
  "description": string,
  "onlyInPredefinedRoles": boolean,
  "stage": enum (PermissionLaunchStage),
  "customRolesSupportLevel": enum (CustomRolesSupportLevel),
  "apiDisabled": boolean,
  "primaryPermission": string
}
```

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>The name of this Permission.</p></td>
</tr>
<tr class="even">
<td><code>title</code></td>
<td><p><code>string</code></p>
<p>The title of this Permission.</p></td>
</tr>
<tr class="odd">
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>A brief description of what this Permission is used for.</p></td>
</tr>
<tr class="even">
<td><code>onlyInPredefinedRoles </code><strong><code>(deprecated)</code></strong></td>
<td><p><code>boolean</code></p>
<blockquote>
<p>This item is deprecated!</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><code>stage</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#PermissionLaunchStage"><code>PermissionLaunchStage</code></a><code> )</code></p>
<p>The current launch stage of the permission.</p></td>
</tr>
<tr class="even">
<td><code>customRolesSupportLevel</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#CustomRolesSupportLevel"><code>CustomRolesSupportLevel</code></a><code> )</code></p>
<p>The current custom role support level.</p></td>
</tr>
<tr class="odd">
<td><code>apiDisabled</code></td>
<td><p><code>boolean</code></p>
<p>The service API associated with the permission is not enabled.</p></td>
</tr>
<tr class="even">
<td><code>primaryPermission</code></td>
<td><p><code>string</code></p>
<p>The preferred name for this permission. If present, then this permission is an alias of, and equivalent to, the listed primaryPermission.</p></td>
</tr>
</tbody>
</table>

## PermissionLaunchStage

A stage representing a permission's lifecycle phase.

| Enums        |                                                |
|--------------|------------------------------------------------|
| `ALPHA`      | The permission is currently in an alpha phase. |
| `BETA`       | The permission is currently in a beta phase.   |
| `GA`         | The permission is generally available.         |
| `DEPRECATED` | The permission is being deprecated.            |

## CustomRolesSupportLevel

The state of the permission with regards to custom roles.

| Enums           |                                                                   |
|-----------------|-------------------------------------------------------------------|
| `SUPPORTED`     | Default state. Permission is fully supported for custom role use. |
| `TESTING`       | Permission is being tested to check custom role compatibility.    |
| `NOT_SUPPORTED` | Permission is not supported for custom role use.                  |
