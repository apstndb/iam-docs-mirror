---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings/list
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings/list
title: 'Method: folders.locations.policyBindings.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings/list#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings/list#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings/list#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings/list#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings/list#try-it)

Lists policy bindings.

### HTTP request

`GET https://iam.googleapis.com/v3/{parent=folders/*/locations/*}/policyBindings`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource, which owns the collection of policy bindings.

Format:

  - `projects/{projectId}/locations/{location}`
  - `projects/{projectNumber}/locations/{location}`
  - `folders/{folderId}/locations/{location}`
  - `organizations/{organizationId}/locations/{location}`

### Query parameters

Parameters

`pageSize`

`integer`

Optional. The maximum number of policy bindings to return. The service may return fewer than this value.

The default value is 50. The maximum value is 1000.

`pageToken`

`string`

Optional. A page token, received from a previous `policyBindings.list` call. Provide this to retrieve the subsequent page.

When paginating, all other parameters provided to `policyBindings.list` must match the call that provided the page token.

`filter`

`string`

Optional. An expression for filtering the results of the request. Filter rules are case insensitive. Some eligible fields for filtering are the following:

  - `target`
  - `policy`

Some examples of filter queries:

  - `target:ex*` : The binding target's name starts with "ex".
  - `target:example` : The binding target's name is `example` .
  - `policy:example` : The binding policy's name is `example` .

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  ListPolicyBindingsResponse  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `iam.policybindings.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
