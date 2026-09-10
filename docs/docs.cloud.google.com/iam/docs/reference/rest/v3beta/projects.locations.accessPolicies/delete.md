---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.accessPolicies/delete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.accessPolicies/delete
title: 'Method: projects.locations.accessPolicies.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.accessPolicies/delete#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.accessPolicies/delete#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.accessPolicies/delete#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.accessPolicies/delete#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.accessPolicies/delete#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.accessPolicies/delete#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.accessPolicies/delete#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/projects.locations.accessPolicies/delete#try-it)

Deletes an access policy.

### HTTP request

`DELETE https://iam.googleapis.com/v3beta/{name=projects/*/locations/*/accessPolicies/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The name of the access policy to delete.

Format: `projects/{projectId}/locations/{location}/accessPolicies/{accessPolicyId}` `projects/{projectNumber}/locations/{location}/accessPolicies/{accessPolicyId}` `folders/{folderId}/locations/{location}/accessPolicies/{accessPolicyId}` `organizations/{organizationId}/locations/{location}/accessPolicies/{accessPolicyId}`

### Query parameters

Parameters

`etag`

`string`

Optional. The etag of the access policy. If this is provided, it must match the server's etag.

`validateOnly`

`boolean`

Optional. If set, validate the request and preview the deletion, but do not actually post it.

`force`

`boolean`

Optional. If set to true, the request will force the deletion of the Policy even if the Policy references PolicyBindings.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
