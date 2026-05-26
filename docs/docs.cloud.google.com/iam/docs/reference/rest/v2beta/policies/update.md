---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/update
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/update
title: 'Method: policies.update'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/update#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/update#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/update#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/update#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/update#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/update#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/update#try-it)

Updates the specified policy.

You can update only the rules and the display name for the policy.

To update a policy, you should use a read-modify-write loop:

1.  Use `  policies.get  ` to read the current version of the policy.
2.  Modify the policy as needed.
3.  Use `policies.update` to write the updated policy.

This pattern helps prevent conflicts between concurrent updates.

### HTTP request

`PUT https://iam.googleapis.com/v2beta/{policy.name=policies/*/*/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`policy.name`

`string`

Immutable. The resource name of the `Policy` , which must be unique. Format: `policies/{attachmentPoint}/denypolicies/{policyId}`

The attachment point is identified by its URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies/my-deny-policy` .

For organizations and folders, use the numeric ID in the full resource name. For projects, requests can use the alphanumeric or the numeric ID. Responses always contain the numeric ID.

### Request body

The request body contains an instance of `  Policy  ` .

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
