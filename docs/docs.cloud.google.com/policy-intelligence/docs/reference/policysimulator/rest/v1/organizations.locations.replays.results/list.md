---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results/list
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results/list
title: 'Method: organizations.locations.replays.results.list'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results/list#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results/list#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results/list#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays.results/list#try-it)

Lists the results of running a `  Replay  ` .

### HTTP request

`GET https://policysimulator.googleapis.com/v1/{parent=organizations/*/locations/*/replays/*}/results`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The `  Replay  ` whose results are listed, in the following format:

`{projects|folders|organizations}/{resource-id}/locations/global/replays/{replay-id}`

Example: `projects/my-project/locations/global/replays/506a5f7f-38ce-4d7d-8e03-479ce1833c36`

### Query parameters

Parameters

`pageSize`

`integer`

The maximum number of `  ReplayResult  ` objects to return. Defaults to 5000.

The maximum value is 5000; values above 5000 are rounded down to 5000.

`pageToken`

`string`

A page token, received from a previous `  Simulator.ListReplayResults  ` call. Provide this token to retrieve the next page of results.

When paginating, all other parameters provided to \[Simulator.ListReplayResults\[\] must match the call that provided the page token.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  ListReplayResultsResponse  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `policysimulator.replayResults.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
