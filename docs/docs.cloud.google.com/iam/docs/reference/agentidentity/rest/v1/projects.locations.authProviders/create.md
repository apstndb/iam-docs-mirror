---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/create
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/create
title: 'Method: projects.locations.authProviders.create'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/create#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/create#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/create#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/create#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/create#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/create#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/create#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/create#try-it)

Creates a new auth provider in a given project and location.

### HTTP request

`POST https://agentidentity.googleapis.com/v1/{parent=projects/*/locations/*}/authProviders`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource where the auth provider is created. Format: projects/{project}/locations/{location}

### Query parameters

Parameters

`authProviderId`

`string`

Required. The ID to use for the auth provider, which will become the final segment of the auth provider's resource name. This value should be 1-63 characters, and valid characters are /\[a-z\]\[0-9\]-/. The first character must be a lowercase letter, and the last character must be a lowercase letter or a number.

`requestId`

`string`

Optional. An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed. The server will guarantee that for at least 60 minutes since the first request.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).

### Request body

The request body contains an instance of `  AuthProvider  ` .

### Response body

If successful, the response body contains a newly created instance of `  AuthProvider  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `agentidentity.authProviders.create`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
