---
name: documents/docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/userinfo
uri: https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/userinfo
title: 'Method: organizations.userinfo'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/userinfo#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/userinfo#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/userinfo#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/userinfo#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/userinfo#body.aspect)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/organizations/userinfo#try-it)

Retrieves claims about the authenticated user from the OIDC /userinfo endpoint.

Note: This endpoint is only supported for Looker.

### HTTP request

`GET https://cloudoauth.googleapis.com/v1/{parent=organizations/*}/userinfo`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Optional. The parent organization resource for which user info is being fetched. Format: `organizations/{organization_id}` .

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Struct  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `openid`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
