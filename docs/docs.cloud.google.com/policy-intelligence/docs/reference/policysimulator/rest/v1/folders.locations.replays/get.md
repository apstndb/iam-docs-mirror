---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays/get
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays/get
title: 'Method: folders.locations.replays.get'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays/get#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays/get#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays/get#body.request_body)
  - [Response body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays/get#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays/get#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays/get#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/folders.locations.replays/get#try-it)

Gets the specified `  Replay  ` . Each `Replay` is available for at least 7 days.

### HTTP request

`GET https://policysimulator.googleapis.com/v1/{name=folders/*/locations/*/replays/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The name of the `  Replay  ` to retrieve, in the following format:

`{projects|folders|organizations}/{resource-id}/locations/global/replays/{replay-id}` , where `{resource-id}` is the ID of the project, folder, or organization that owns the `Replay` .

Example: `projects/my-example-project/locations/global/replays/506a5f7f-38ce-4d7d-8e03-479ce1833c36`

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Replay  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `policysimulator.replays.get`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
