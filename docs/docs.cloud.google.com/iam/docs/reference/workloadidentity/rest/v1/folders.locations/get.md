---
name: documents/docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations/get
uri: https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations/get
title: 'Method: folders.locations.get'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations/get#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations/get#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations/get#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations/get#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations/get#body.aspect)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations/get#try-it)

Gets information about a location.

### HTTP request

`GET https://workloadidentity.googleapis.com/v1/{name=folders/*/locations/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Resource name for the location.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Location  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
