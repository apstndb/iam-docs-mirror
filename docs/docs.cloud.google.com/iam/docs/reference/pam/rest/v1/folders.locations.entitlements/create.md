---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/create
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/create
title: 'Method: folders.locations.entitlements.create'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/create#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/create#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/create#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/create#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/create#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/create#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/create#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/create#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/folders.locations.entitlements/create#try-it)

Creates a new entitlement in a given project, folder, organization, and in a given location.

### HTTP request

`POST https://privilegedaccessmanager.googleapis.com/v1/{parent=folders/*/locations/*}/entitlements`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. Name of the parent resource for the entitlement. Possible formats:

  - `organizations/{organization-number}/locations/{region}`
  - `folders/{folder-number}/locations/{region}`
  - `projects/{project-id|project-number}/locations/{region}`

### Query parameters

Parameters

`entitlementId`

`string`

Required. The ID to use for this entitlement. This becomes the last part of the resource name.

This value should be 4-63 characters in length, and valid characters are "\[a-z\]", "\[0-9\]", and "-". The first character should be from \[a-z\].

This value should be unique among all other entitlements under the specified `parent` .

`requestId`

`string`

Optional. An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server knows to ignore the request if it has already been completed. The server guarantees this for at least 60 minutes after the first request.

For example, consider a situation where you make an initial request and the request times out. If you make the request again with the same request ID, the server can check if original operation with the same request ID was received, and if so, ignores the second request and returns the previous operation's response. This prevents clients from accidentally creating duplicate entitlements.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).

### Request body

The request body contains an instance of `  Entitlement  ` .

### Response body

If successful, the response body contains a newly created instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `privilegedaccessmanager.entitlements.create`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
