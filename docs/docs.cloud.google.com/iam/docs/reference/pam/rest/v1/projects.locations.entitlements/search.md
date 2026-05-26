---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/search
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/search
title: 'Method: projects.locations.entitlements.search'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/search#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/search#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/search#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/search#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/search#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/search#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/search#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/projects.locations.entitlements/search#try-it)

`entitlements.search` returns entitlements on which the caller has the specified access.

### HTTP request

`GET https://privilegedaccessmanager.googleapis.com/v1/{parent=projects/*/locations/*}/entitlements:search`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent which owns the entitlement resources.

### Query parameters

Parameters

`callerAccessType`

` enum ( CallerAccessType  ` )

Required. Only entitlements where the calling user has this access are returned.

`filter`

`string`

Optional. Only entitlements matching this filter are returned in the response.

`pageSize`

`integer`

Optional. Requested page size. The server may return fewer items than requested. If unspecified, the server picks an appropriate default.

`pageToken`

`string`

Optional. A token identifying a page of results the server should return.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  SearchEntitlementsResponse  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
