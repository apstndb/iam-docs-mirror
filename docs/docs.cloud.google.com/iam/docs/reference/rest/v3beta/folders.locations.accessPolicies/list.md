---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/list
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/list
title: 'Method: folders.locations.accessPolicies.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/list#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/list#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/list#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/list#try-it)

Lists access policies.

### HTTP request

`GET https://iam.googleapis.com/v3beta/{parent=folders/*/locations/*}/accessPolicies`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource, which owns the collection of access policy resources.

Format: `projects/{projectId}/locations/{location}` `projects/{projectNumber}/locations/{location}` `folders/{folderId}/locations/{location}` `organizations/{organizationId}/locations/{location}`

### Query parameters

Parameters

`pageSize`

`integer`

Optional. The maximum number of access policies to return. The service may return fewer than this value.

If unspecified, at most 50 access policies will be returned. Valid value ranges from 1 to 1000; values above 1000 will be coerced to 1000.

`pageToken`

`string`

Optional. A page token, received from a previous `accessPolicies.list` call. Provide this to retrieve the subsequent page.

When paginating, all other parameters provided to `accessPolicies.list` must match the call that provided the page token.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  ListAccessPoliciesResponse  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
