---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create
title: 'Method: organizations.roles.create'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create#body.request_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create#body.request_body.SCHEMA_REPRESENTATION)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create#try-it)

Creates a new custom `  Role  ` .

### HTTP request

`POST https://iam.googleapis.com/v1/{parent=organizations/*}/roles`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

The `parent` parameter's value depends on the target resource for the request, namely [projects](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles) or [organizations](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles) . Each resource type's `parent` value format is described below:

  - [projects.roles.create](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/create) : `projects/{PROJECT_ID}` . This method creates project-level [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) . Example request URL: `https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles`

  - [organizations.roles.create](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/create) : `organizations/{ORGANIZATION_ID}` . This method creates organization-level [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) . Example request URL: `https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles`

Note: Wildcard (\*) values are invalid; you must specify a complete project ID or organization ID.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `parent` :

  - `iam.roles.create`

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;roleId&quot;: string,&quot;role&quot;: {object (Role)}}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`roleId`

`string`

The role ID to use for this role.

A role ID may contain alphanumeric characters, underscores ( `_` ), and periods ( `.` ). It must contain a minimum of 3 characters and a maximum of 64 characters.

`role`

` object ( Role  ` )

The Role resource to create.

### Response body

If successful, the response body contains a newly created instance of `  Role  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/iam`
  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
