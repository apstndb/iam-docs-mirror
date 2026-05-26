---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/undelete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/undelete
title: 'Method: projects.locations.oauthClients.undelete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/undelete#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/undelete#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/undelete#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/undelete#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/undelete#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/undelete#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/undelete#try-it)

Undeletes an `  OauthClient  ` , as long as it was deleted fewer than 30 days ago.

### HTTP request

`POST https://iam.googleapis.com/v1/{name=projects/*/locations/*/oauthClients/*}:undelete`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The name of the `  OauthClient  ` to undelete.

Format: `projects/{project}/locations/{location}/oauthClients/{oauthClient}` .

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  OauthClient  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
