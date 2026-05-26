---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/delete
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/delete
title: 'Method: organizations.locations.entitlements.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/delete#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/delete#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/delete#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/delete#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/delete#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/delete#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/delete#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/delete#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/delete#try-it)

Deletes a single entitlement. This method can only be called when there are no in-progress ( `ACTIVE` / `ACTIVATING` / `REVOKING` ) grants under the entitlement.

### HTTP request

`DELETE https://privilegedaccessmanager.googleapis.com/v1beta/{name=organizations/*/locations/*/entitlements/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. Name of the resource.

### Query parameters

Parameters

`requestId`

`string`

Optional. An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server knows to ignore the request if it has already been completed. The server guarantees this for at least 60 minutes after the first request.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, ignores the second request.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).

`force`

`boolean`

Optional. If set to true, any child grant under this entitlement is also deleted. (Otherwise, the request only works if the entitlement has no child grant.)

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `privilegedaccessmanager.entitlements.delete`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
