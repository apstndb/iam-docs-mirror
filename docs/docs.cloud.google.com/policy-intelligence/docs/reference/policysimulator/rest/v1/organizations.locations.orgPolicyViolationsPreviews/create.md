---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/create
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/create
title: 'Method: organizations.locations.orgPolicyViolationsPreviews.create'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/create#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/create#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/create#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/create#body.request_body)
  - [Response body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/create#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/create#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/create#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1/organizations.locations.orgPolicyViolationsPreviews/create#try-it)

orgPolicyViolationsPreviews.create creates an `  OrgPolicyViolationsPreview  ` for the proposed changes in the provided \[OrgPolicyViolationsPreview.OrgPolicyOverlay\]\[\]. The changes to OrgPolicy are specified by this `OrgPolicyOverlay` . The resources to scan are inferred from these specified changes.

### HTTP request

`POST https://policysimulator.googleapis.com/v1/{parent=organizations/*/locations/*}/orgPolicyViolationsPreviews`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The organization under which this `  OrgPolicyViolationsPreview  ` will be created.

Example: `organizations/my-example-org/locations/global`

### Query parameters

Parameters

`orgPolicyViolationsPreviewId`

`string`

Optional. An optional user-specified ID for the `  OrgPolicyViolationsPreview  ` . If not provided, a random ID will be generated.

### Request body

The request body contains an instance of `  OrgPolicyViolationsPreview  ` .

### Response body

If successful, the response body contains a newly created instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `policysimulator.orgPolicyViolationsPreviews.create`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
