---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v2/policies/get
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/get
title: 'Method: policies.get'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/get#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/get#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/get#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/get#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/get#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/get#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/get#try-it)

Gets a policy.

### HTTP request

`GET https://iam.googleapis.com/v2/{name=policies/*/*/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The resource name of the policy to retrieve. Format: `policies/{attachmentPoint}/denypolicies/{policyId}`

Use the URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-policy` .

For organizations and folders, use the numeric ID in the full resource name. For projects, you can use the alphanumeric or the numeric ID.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Policy  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
