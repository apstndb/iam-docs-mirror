---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/roles/get
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/get
title: 'Method: roles.get'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/get#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/get#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/get#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/get#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/get#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/get#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/roles/get#try-it)

Gets the definition of a `  Role  ` .

### HTTP request

`GET https://iam.googleapis.com/v1/{name=roles/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

The `name` parameter's value depends on the target resource for the request, namely [roles](https://cloud.google.com/iam/docs/reference/rest/v1/roles) , [projects](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles) , or [organizations](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles) . Each resource type's `name` value format is described below:

  - [roles.get](https://cloud.google.com/iam/docs/reference/rest/v1/roles/get) : `roles/{ROLE_NAME}` . This method returns results from all [predefined roles](https://cloud.google.com/iam/docs/understanding-roles#predefined_roles) in IAM. Example request URL: `https://iam.googleapis.com/v1/roles/{ROLE_NAME}`

  - [projects.roles.get](https://cloud.google.com/iam/docs/reference/rest/v1/projects.roles/get) : `projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}` . This method returns only [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) that have been created at the project level. Example request URL: `https://iam.googleapis.com/v1/projects/{PROJECT_ID}/roles/{CUSTOM_ROLE_ID}`

  - [organizations.roles.get](https://cloud.google.com/iam/docs/reference/rest/v1/organizations.roles/get) : `organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}` . This method returns only [custom roles](https://cloud.google.com/iam/docs/understanding-custom-roles) that have been created at the organization level. Example request URL: `https://iam.googleapis.com/v1/organizations/{ORGANIZATION_ID}/roles/{CUSTOM_ROLE_ID}`

Note: Wildcard (\*) values are invalid; you must specify a complete project ID or organization ID.

Authorization requires the following [IAM](https://cloud.google.com/iam/docs/) permission on the specified resource `name` :

  - `iam.roles.get`

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Role  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/iam`
  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
