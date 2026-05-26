---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.operations/list
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.operations/list
title: 'Method: folders.locations.replays.operations.list'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.operations/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.operations/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.operations/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.operations/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.operations/list#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.operations/list#body.aspect)
  - [Try it\!](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays.operations/list#try-it)

Lists operations that match the specified filter in the request. If the server doesn't support this method, it returns `UNIMPLEMENTED` .

### HTTP request

`GET https://policysimulator.googleapis.com/v1/{name=folders/*/locations/*/replays/*/operations}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

The name of the operation's parent resource.

### Query parameters

Parameters

`filter`

`string`

The standard list filter.

`pageSize`

`integer`

The standard list page size.

`pageToken`

`string`

The standard list page token.

`returnPartialSuccess`

`boolean`

When set to `true` , operations that are reachable are returned as normal, and those that are unreachable are returned in the `  ListOperationsResponse.unreachable  ` field.

This can only be `true` when reading across collections. For example, when `parent` is set to `"projects/example/locations/-"` .

This field is not supported by default and will result in an `UNIMPLEMENTED` error if set unless explicitly documented otherwise in service or product specific documentation.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  ListOperationsResponse  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
