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
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list#try-it)

Lists every predefined `  Role  ` that IAM supports, or every custom role that is defined for an organization or project.

### HTTP request

`GET https://iam.googleapis.com/v1/{parent=organizations/*}/roles`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

The `parent` parameter's value depends on the target resource for the request, namely [roles](https://cloud.google.com/iam/docs/reference/rest/v1/roles) , [projects](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles) , or [organizations](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles) . Each resource type's `parent` value format is described below:

  - [roles.list](https://cloud.google.com/iam/docs/reference/rest/v1/roles/list) : An empty string. This method doesn't require a resource; it simply returns all [predefined roles](https://cloud.google.com/iam/docs/understanding-roles#predefined_roles) in IAM. Example request URL: `https://iam.googleapis.com/v1/roles`

  - [projects.roles.list](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/list) : `projects/{PROJECT_ID}` . This method lists all project-level [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) . Example request URL: `https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles`

  - [organizations.roles.list](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/list) : `organizations/{ORGANIZATION_ID}` . This method lists all organization-level [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) . Example request URL: `https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles`

Note: Wildcard (\*) values are invalid; you must specify a complete project ID or organization ID.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `parent` :

  - `iam.roles.list`

### Query parameters

Parameters

`pageSize`

`integer`

Optional limit on the number of roles to include in the response.

The default is 300, and the maximum is 1,000.

`pageToken`

`string`

Optional pagination token returned in an earlier ListRolesResponse.

`view`

` enum ( RoleView  ` )

Optional view for the returned Role objects. When `FULL` is specified, the `includedPermissions` field is returned, which includes a list of all permissions in the role. The default value is `BASIC` , which does not return the `includedPermissions` field.

`showDeleted`

`boolean`

Include Roles that have been deleted.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  ListRolesResponse  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/iam`
  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
