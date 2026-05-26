---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/withdraw
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/withdraw
title: 'Method: folders.locations.entitlements.grants.withdraw'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/withdraw#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/withdraw#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/withdraw#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/withdraw#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/withdraw#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/withdraw#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements.grants/withdraw#try-it)

`grants.withdraw` is used to immediately withdraw the grant. This method can be called when the grant is in a non-terminal state.

### HTTP request

`POST https://privilegedaccessmanager.googleapis.com/v1beta/{name=folders/*/locations/*/entitlements/*/grants/*}:withdraw`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. Name of the grant resource which is being withdrawn.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
