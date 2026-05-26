---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/createPolicy
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/createPolicy
title: 'Method: policies.createPolicy'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/createPolicy#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/createPolicy#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/createPolicy#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/createPolicy#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/createPolicy#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/createPolicy#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/createPolicy#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v2beta/policies/createPolicy#try-it)

Creates a policy.

### HTTP request

`POST https://iam.googleapis.com/v2beta/{parent=policies/*/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The resource that the policy is attached to, along with the kind of policy to create. Format: `policies/{attachmentPoint}/denypolicies`

The attachment point is identified by its URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies` .

For organizations and folders, use the numeric ID in the full resource name. For projects, you can use the alphanumeric or the numeric ID.

### Query parameters

Parameters

`policyId`

`string`

The ID to use for this policy, which will become the final component of the policy's resource name. The ID must contain 3 to 63 characters. It can contain lowercase letters and numbers, as well as dashes ( `-` ) and periods ( `.` ). The first character must be a lowercase letter.

### Request body

The request body contains an instance of `  Policy  ` .

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
