---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/delete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/delete
title: 'Method: locations.workforcePools.subjects.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/delete#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/delete#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/delete#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/delete#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/delete#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/delete#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.subjects/delete#try-it)

Deletes a `WorkforcePoolSubject` .

Subject must not already be in a deleted state.

A `WorkforcePoolSubject` is automatically created the first time an external credential is exchanged for a Google Cloud credential using a mapped `google.subject` attribute. There is no endpoint to manually create a `WorkforcePoolSubject` .

For 30 days after a `WorkforcePoolSubject` is deleted, using the same `google.subject` attribute in token exchanges with Google Cloud STS fails.

Call `  subjects.undelete  ` to undelete a `WorkforcePoolSubject` that has been deleted, within within 30 days of deleting it.

After 30 days, the `WorkforcePoolSubject` is permanently deleted. At this point, a token exchange with Google Cloud STS that uses the same mapped `google.subject` attribute automatically creates a new `WorkforcePoolSubject` that is unrelated to the previously deleted `WorkforcePoolSubject` but has the same `google.subject` value.

### HTTP request

`DELETE https://iam.googleapis.com/v1/{name=locations/*/workforcePools/*/subjects/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The resource name of the `WorkforcePoolSubject` . Special characters, like `/` and `:` , must be escaped, because all URLs need to conform to the "When to Escape and Unescape" section of [RFC3986](https://www.ietf.org/rfc/rfc2396.txt) .

Format: `locations/{location}/workforcePools/{workforcePoolId}/subjects/{subject_id}`

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
