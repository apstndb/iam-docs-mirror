---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays/list
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays/list
title: 'Method: organizations.locations.replays.list'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays/list#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays/list#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays/list#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.replays/list#try-it)

Lists each `  Replay  ` in a project, folder, or organization. Each `Replay` is available for at least 7 days.

### HTTP request

`GET https://policysimulator.googleapis.com/v1beta/{parent=organizations/*/locations/*}/replays`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource, in the following format:

`{projects|folders|organizations}/{resource-id}/locations/global` , where `{resource-id}` is the ID of the project, folder, or organization that owns the `  Replay  ` .

Example: `projects/my-example-project/locations/global`

Only `Replay` objects that are direct children of the provided parent are listed. In other words, `Replay` objects that are children of a project will not be included when the parent is a folder of that project.

### Query parameters

Parameters

`pageSize`

`integer`

The maximum number of `  Replay  ` objects to return. Defaults to 50.

The maximum value is 1000; values above 1000 are rounded down to 1000.

`pageToken`

`string`

A page token, received from a previous `  Simulator.ListReplays  ` call. Provide this to retrieve the subsequent page.

When paginating, all other parameters provided to `  Simulator.ListReplays  ` must match the call that provided the page token.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  ListReplaysResponse  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `policysimulator.replays.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
