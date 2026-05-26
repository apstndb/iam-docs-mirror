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
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/permissions/queryTestablePermissions#try-it)

Lists every permission that you can test on a resource. A permission is testable if you can check whether a principal has that permission on the resource.

### HTTP request

`POST https://iam.googleapis.com/v1/permissions:queryTestablePermissions`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Request body

The request body contains data with the following structure:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{
  &quot;fullResourceName&quot;: string,
  &quot;pageSize&quot;: integer,
  &quot;pageToken&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`fullResourceName`

`string`

Required. The full resource name to query from the list of testable permissions.

The name follows the Google Cloud Platform resource format. For example, a Cloud Platform project with id `my-project` will be named `//cloudresourcemanager.googleapis.com/projects/my-project` .

`pageSize`

`integer`

Optional limit on the number of permissions to include in the response.

The default is 100, and the maximum is 1,000.

`pageToken`

`string`

Optional pagination token returned in an earlier QueryTestablePermissionsRequest.

### Response body

The response containing permissions which can be tested on a resource.

If successful, the response body contains data with the following structure:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;permissions&quot;: [{object (Permission)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`permissions[]`

` object ( Permission  ` )

The Permissions testable on the requested resource.

`nextPageToken`

`string`

To retrieve the next page of results, set `QueryTestableRolesRequest.page_token` to this value.

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/iam`
  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

## Permission

A permission which can be included by a role.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;name&quot;: string,&quot;title&quot;: string,&quot;description&quot;: string,&quot;onlyInPredefinedRoles&quot;: boolean,&quot;stage&quot;: enum (PermissionLaunchStage),&quot;customRolesSupportLevel&quot;: enum (CustomRolesSupportLevel),&quot;apiDisabled&quot;: boolean,&quot;primaryPermission&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

The name of this Permission.

`title`

`string`

The title of this Permission.

`description`

`string`

A brief description of what this Permission is used for.

` onlyInPredefinedRoles (deprecated)  `

`boolean`

> This item is deprecated\!

`stage`

` enum ( PermissionLaunchStage  ` )

The current launch stage of the permission.

`customRolesSupportLevel`

` enum ( CustomRolesSupportLevel  ` )

The current custom role support level.

`apiDisabled`

`boolean`

The service API associated with the permission is not enabled.

`primaryPermission`

`string`

The preferred name for this permission. If present, then this permission is an alias of, and equivalent to, the listed primaryPermission.

## PermissionLaunchStage

A stage representing a permission's lifecycle phase.

Enums

`ALPHA`

The permission is currently in an alpha phase.

`BETA`

The permission is currently in a beta phase.

`GA`

The permission is generally available.

`DEPRECATED`

The permission is being deprecated.

## CustomRolesSupportLevel

The state of the permission with regards to custom roles.

Enums

`SUPPORTED`

Default state. Permission is fully supported for custom role use.

`TESTING`

Permission is being tested to check custom role compatibility.

`NOT_SUPPORTED`

Permission is not supported for custom role use.
