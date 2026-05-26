---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/delete
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/delete
title: 'Method: organizations.locations.operations.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/delete#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/delete#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/delete#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/delete#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/delete#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/delete#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/delete#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/delete#try-it)

Deletes a long-running operation. This method indicates that the client is no longer interested in the operation result. It does not cancel the operation. If the server doesn't support this method, it returns `google.rpc.Code.UNIMPLEMENTED` .

### HTTP request

`DELETE https://privilegedaccessmanager.googleapis.com/v1/{name=organizations/*/locations/*/operations/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

The name of the operation resource to be deleted.

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

  - `privilegedaccessmanager.operations.delete`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
