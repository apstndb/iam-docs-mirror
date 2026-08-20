---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders/get
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders/get
title: 'Method: projects.locations.authProviders.get'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders/get#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders/get#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders/get#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders/get#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders/get#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders/get#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.authProviders/get#try-it)

Gets details of a single auth provider.

### HTTP request

`GET https://agentidentity.googleapis.com/v1beta/{name=projects/*/locations/*/authProviders/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The resource name of the auth provider.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  AuthProvider  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `agentidentity.authProviders.get`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
