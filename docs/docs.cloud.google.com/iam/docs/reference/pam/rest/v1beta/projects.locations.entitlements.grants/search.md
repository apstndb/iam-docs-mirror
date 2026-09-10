---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/search
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/search
title: 'Method: projects.locations.entitlements.grants.search'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/search#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/search#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/search#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/search#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/search#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/search#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/search#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/search#try-it)

`grants.search` returns grants that are related to the calling user in the specified way.

### HTTP request

`GET https://privilegedaccessmanager.googleapis.com/v1beta/{parent=projects/*/locations/*/entitlements/*}/grants:search`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent which owns the grant resources.

### Query parameters

Parameters

`callerRelationship`

` enum ( CallerRelationshipType  ` )

Required. Only grants which the caller is related to by this relationship are returned in the response.

`filter`

`string`

Optional. Only grants matching this filter are returned in the response.

`pageSize`

`integer`

Optional. Requested page size. The server may return fewer items than requested. If unspecified, server picks an appropriate default.

`pageToken`

`string`

Optional. A token identifying a page of results the server should return.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  SearchGrantsResponse  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
