---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v2/policies/delete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/delete
title: 'Method: policies.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/delete#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/delete#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/delete#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/delete#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/delete#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/delete#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/delete#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/delete#try-it)

Deletes a policy. This action is permanent.

### HTTP request

`DELETE https://iam.googleapis.com/v2/{name=policies/*/*/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The resource name of the policy to delete. Format: `policies/{attachmentPoint}/denypolicies/{policyId}`

Use the URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-policy` .

For organizations and folders, use the numeric ID in the full resource name. For projects, you can use the alphanumeric or the numeric ID.

### Query parameters

Parameters

`etag`

`string`

Optional. The expected `etag` of the policy to delete. If the value does not match the value that is stored in IAM, the request fails with a `409` error code and `ABORTED` status.

If you omit this field, the policy is deleted regardless of its current `etag` .

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
