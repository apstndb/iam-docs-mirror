---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/list
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/list
title: 'Method: organizations.locations.operations.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/list#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/list#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/list#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/list#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1/organizations.locations.operations/list#try-it)

Lists operations that match the specified filter in the request. If the server doesn't support this method, it returns `UNIMPLEMENTED` .

### HTTP request

`GET https://privilegedaccessmanager.googleapis.com/v1/{name=organizations/*/locations/*}/operations`

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

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `privilegedaccessmanager.operations.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
