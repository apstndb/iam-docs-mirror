---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/searchPolicyBindings
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/searchPolicyBindings
title: 'Method: organizations.locations.accessPolicies.searchPolicyBindings'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/searchPolicyBindings#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/searchPolicyBindings#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/searchPolicyBindings#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/searchPolicyBindings#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/searchPolicyBindings#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/searchPolicyBindings#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/searchPolicyBindings#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/searchPolicyBindings#try-it)

Returns all policy bindings that bind a specific policy if a user has searchPolicyBindings permission on that policy.

### HTTP request

`GET https://iam.googleapis.com/v3beta/{name=organizations/*/locations/*/accessPolicies/*}:searchPolicyBindings`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The name of the access policy. Format: `organizations/{organizationId}/locations/{location}/accessPolicies/{accessPolicyId}` `folders/{folderId}/locations/{location}/accessPolicies/{accessPolicyId}` `projects/{projectId}/locations/{location}/accessPolicies/{accessPolicyId}` `projects/{projectNumber}/locations/{location}/accessPolicies/{accessPolicyId}`

### Query parameters

Parameters

`pageSize`

`integer`

Optional. The maximum number of policy bindings to return. The service may return fewer than this value.

If unspecified, at most 50 policy bindings will be returned. The maximum value is 1000; values above 1000 will be coerced to 1000.

`pageToken`

`string`

Optional. A page token, received from a previous `SearchAccessPolicyBindingsRequest` call. Provide this to retrieve the subsequent page.

When paginating, all other parameters provided to `SearchAccessPolicyBindingsRequest` must match the call that provided the page token.

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  SearchAccessPolicyBindingsResponse  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
