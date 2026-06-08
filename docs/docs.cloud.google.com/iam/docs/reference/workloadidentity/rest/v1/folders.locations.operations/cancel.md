---
name: documents/docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations.operations/cancel
uri: https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations.operations/cancel
title: 'Method: folders.locations.operations.cancel'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations.operations/cancel#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations.operations/cancel#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations.operations/cancel#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations.operations/cancel#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations.operations/cancel#body.aspect)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/workloadidentity/rest/v1/folders.locations.operations/cancel#try-it)

Starts asynchronous cancellation on a long-running operation. The server makes a best effort to cancel the operation, but success is not guaranteed. If the server doesn't support this method, it returns `google.rpc.Code.UNIMPLEMENTED` . Clients can use `  Operations.GetOperation  ` or other methods to check whether the cancellation succeeded or whether the operation completed despite cancellation. On successful cancellation, the operation is not deleted; instead, it becomes an operation with an `  Operation.error  ` value with a `  google.rpc.Status.code  ` of `1` , corresponding to `Code.CANCELLED` .

### HTTP request

`POST https://workloadidentity.googleapis.com/v1/{name=folders/*/locations/*/operations/*}:cancel`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

The name of the operation resource to be cancelled.

### Request body

The request body must be empty.

### Response body

If successful, the response body is an empty JSON object.

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
