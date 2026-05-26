---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/get
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/get
title: 'Method: folders.locations.accessPolicies.get'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/get#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/get#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/get#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/get#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/get#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/get#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/get#try-it)

Gets an access policy.

### HTTP request

`GET https://iam.googleapis.com/v3beta/{name=folders/*/locations/*/accessPolicies/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The name of the access policy to retrieve.

Format: `projects/{projectId}/locations/{location}/accessPolicies/{accessPolicyId}` `projects/{projectNumber}/locations/{location}/accessPolicies/{accessPolicyId}` `folders/{folderId}/locations/{location}/accessPolicies/{accessPolicyId}` `organizations/{organizationId}/locations/{location}/accessPolicies/{accessPolicyId}`

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  AccessPolicy  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
