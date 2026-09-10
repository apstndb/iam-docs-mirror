---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/create
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/create
title: 'Method: folders.locations.accessPolicies.create'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/create#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/create#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/create#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/create#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/create#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/create#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/create#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/create#try-it)

Creates an access policy, and returns a long running operation.

### HTTP request

`POST https://iam.googleapis.com/v3beta/{parent=folders/*/locations/*}/accessPolicies`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource where this access policy will be created.

Format: `projects/{projectId}/locations/{location}` `projects/{projectNumber}/locations/{location}` `folders/{folderId}/locations/{location}` `organizations/{organizationId}/locations/{location}`

### Query parameters

Parameters

`accessPolicyId`

`string`

Required. The ID to use for the access policy, which will become the final component of the access policy's resource name.

This value must start with a lowercase letter followed by up to 62 lowercase letters, numbers, hyphens, or dots. Pattern, /\[a-z\]\[a-z0-9-.\]{2,62}/.

This value must be unique among all access policies with the same parent.

`validateOnly`

`boolean`

Optional. If set, validate the request and preview the creation, but do not actually post it.

### Request body

The request body contains an instance of `  AccessPolicy  ` .

### Response body

If successful, the response body contains a newly created instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
