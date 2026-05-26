---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays/create
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays/create
title: 'Method: organizations.locations.replays.create'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays/create#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays/create#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays/create#body.request_body)
  - [Response body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays/create#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays/create#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays/create#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.replays/create#try-it)

Creates and starts a `  Replay  ` using the given `  ReplayConfig  ` .

### HTTP request

`POST https://policysimulator.googleapis.com/v1/{parent=organizations/*/locations/*}/replays`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource where this `  Replay  ` will be created. This resource must be a project, folder, or organization with a location.

Example: `projects/my-example-project/locations/global`

### Request body

The request body contains an instance of `  Replay  ` .

### Response body

If successful, the response body contains a newly created instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `policysimulator.replays.create`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
