---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/delete
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/delete
title: 'Method: projects.locations.authProviders.authorizations.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/delete#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/delete#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/delete#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/delete#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/delete#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/delete#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/delete#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/delete#try-it)

Deletes a single authorization.

### HTTP request

`DELETE https://agentidentity.googleapis.com/v1/{name=projects/*/locations/*/authProviders/*/authorizations/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The resource name of the authorization to delete. Format: projects/{project}/locations/{location}/authProviders/{authProvider}/authorizations/{authorization}

### Query parameters

Parameters

`requestId`

`string`

Optional. An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed. The server will guarantee that for at least 60 minutes after the first request.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, will ignore the second request. This prevents clients from accidentally creating duplicate commitments.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).

### Request body

The request body must be empty.

### Response body

If successful, the response body is an empty JSON object.

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `agentidentity.authorizations.delete`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
