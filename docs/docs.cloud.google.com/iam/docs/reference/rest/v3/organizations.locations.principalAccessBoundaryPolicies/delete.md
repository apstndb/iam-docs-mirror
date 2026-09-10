---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/delete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/delete
title: 'Method: organizations.locations.principalAccessBoundaryPolicies.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/delete#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/delete#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/delete#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/delete#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/delete#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/delete#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/delete#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/delete#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/delete#try-it)

Deletes a principal access boundary policy.

### HTTP request

`DELETE https://iam.googleapis.com/v3/{name=organizations/*/locations/*/principalAccessBoundaryPolicies/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The name of the principal access boundary policy to delete.

Format: `organizations/{organizationId}/locations/{location}/principalAccessBoundaryPolicies/{principalAccessBoundaryPolicyId}`

### Query parameters

Parameters

`etag`

`string`

Optional. The etag of the principal access boundary policy. If this is provided, it must match the server's etag.

`validateOnly`

`boolean`

Optional. If set, validate the request and preview the deletion, but do not actually post it.

`force`

`boolean`

Optional. If set to true, the request will force the deletion of the policy even if the policy is referenced in policy bindings.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `iam.principalaccessboundarypolicies.delete`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
