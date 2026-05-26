---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/delete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/delete
title: 'Method: organizations.roles.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/delete#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/delete#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/delete#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/delete#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/delete#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/delete#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/delete#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/delete#try-it)

Deletes a custom `  Role  ` .

When you delete a custom role, the following changes occur immediately:

  - You cannot bind a principal to the custom role in an IAM `  Policy  ` .
  - Existing bindings to the custom role are not changed, but they have no effect.
  - By default, the response from `  roles.list  ` does not include the custom role.

A deleted custom role still counts toward the [custom role limit](https://cloud.google.com/iam/help/limits) until it is permanently deleted. You have 7 days to undelete the custom role. After 7 days, the following changes occur:

  - The custom role is permanently deleted and cannot be recovered.
  - If an IAM policy contains a binding to the custom role, the binding is permanently removed.
  - The custom role no longer counts toward your custom role limit.

### HTTP request

`DELETE https://iam.googleapis.com/v1/{name=organizations/*/roles/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

The `name` parameter's value depends on the target resource for the request, namely [projects](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles) or [organizations](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles) . Each resource type's `name` value format is described below:

  - [projects.roles.delete](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/delete) : `projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}` . This method deletes only [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) that have been created at the project level. Example request URL: `https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}`

  - [organizations.roles.delete](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/delete) : `organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}` . This method deletes only [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) that have been created at the organization level. Example request URL: `https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}`

Note: Wildcard (\*) values are invalid; you must specify a complete project ID or organization ID.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.roles.delete`

### Query parameters

Parameters

`etag`

`string ( bytes format)`

Used to perform a consistent read-modify-write.

A base64-encoded string.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Role  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/iam`
  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
