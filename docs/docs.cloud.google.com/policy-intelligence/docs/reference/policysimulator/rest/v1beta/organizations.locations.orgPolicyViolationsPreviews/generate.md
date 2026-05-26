---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews/generate
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews/generate
title: 'Method: organizations.locations.orgPolicyViolationsPreviews.generate'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews/generate#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews/generate#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews/generate#body.request_body)
  - [Response body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews/generate#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews/generate#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews/generate#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews/generate#try-it)

orgPolicyViolationsPreviews.generate generates an `  OrgPolicyViolationsPreview  ` for the proposed changes in the provided \[OrgPolicyViolationsPreview.OrgPolicyOverlay\]\[\]. The changes to OrgPolicy are specified by this `OrgPolicyOverlay` . The resources to scan are inferred from these specified changes.

### HTTP request

`POST https://policysimulator.googleapis.com/v1beta/{parent=organizations/*/locations/*}/orgPolicyViolationsPreviews:generate`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The organization under which this `  OrgPolicyViolationsPreview  ` will be created.

Example: `organizations/my-example-org/locations/global`

### Request body

The request body contains an instance of `  OrgPolicyViolationsPreview  ` .

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `policysimulator.orgPolicyViolationsPreviews.create`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
