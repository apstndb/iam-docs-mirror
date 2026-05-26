---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/get
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/get
title: 'Method: organizations.locations.orgPolicyViolationsPreviews.get'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/get#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/get#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/get#body.request_body)
  - [Response body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/get#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/get#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/get#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/get#try-it)

orgPolicyViolationsPreviews.get gets the specified `  OrgPolicyViolationsPreview  ` . Each `  OrgPolicyViolationsPreview  ` is available for at least 7 days.

### HTTP request

`GET https://policysimulator.googleapis.com/v1/{name=organizations/*/locations/*/orgPolicyViolationsPreviews/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The name of the OrgPolicyViolationsPreview to get.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  OrgPolicyViolationsPreview  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `policysimulator.orgPolicyViolationsPreviews.get`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
