---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/delete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/delete
title: 'Method: projects.locations.oauthClients.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/delete#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/delete#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/delete#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/delete#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/delete#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/delete#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.oauthClients/delete#try-it)

Deletes an `  OauthClient  ` .

You cannot use a deleted `  OauthClient  ` . However, deletion does not revoke access tokens that have already been issued. They continue to grant access. Deletion does revoke refresh tokens that have already been issued. They cannot be used to renew an access token. If the `  OauthClient  ` is undeleted, and the refresh tokens are not expired, they are valid for token exchange again. You can undelete an `  OauthClient  ` for 30 days. After 30 days, deletion is permanent. You cannot update deleted `  OauthClient  ` s. However, you can view and list them.

### HTTP request

`DELETE https://iam.googleapis.com/v1/{name=projects/*/locations/*/oauthClients/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The name of the `  OauthClient  ` to delete.

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
