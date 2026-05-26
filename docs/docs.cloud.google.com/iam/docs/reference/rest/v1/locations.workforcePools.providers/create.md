---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create
title: 'Method: locations.workforcePools.providers.create'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers/create#try-it)

Creates a new `  WorkforcePoolProvider  ` in a `  WorkforcePool  ` .

You cannot reuse the name of a deleted provider until 30 days after deletion.

### HTTP request

`POST https://iam.googleapis.com/v1/{parent=locations/*/workforcePools/*}/providers`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The pool to create this provider in.

Format: `locations/{location}/workforcePools/{workforcePoolId}`

### Query parameters

Parameters

`workforcePoolProviderId`

`string`

Required. The ID for the provider, which becomes the final component of the resource name. This value must be 4-32 characters, and may contain the characters `[a-z0-9-]` . The prefix `gcp-` is reserved for use by Google, and may not be specified.

### Request body

The request body contains an instance of `  WorkforcePoolProvider  ` .

### Response body

If successful, the response body contains a newly created instance of `  Operation  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
