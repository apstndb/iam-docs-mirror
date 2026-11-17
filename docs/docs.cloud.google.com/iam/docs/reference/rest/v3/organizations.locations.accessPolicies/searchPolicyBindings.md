---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/searchPolicyBindings
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/searchPolicyBindings
title: 'Method: organizations.locations.accessPolicies.searchPolicyBindings'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/searchPolicyBindings#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/searchPolicyBindings#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/searchPolicyBindings#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/searchPolicyBindings#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/searchPolicyBindings#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/searchPolicyBindings#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/searchPolicyBindings#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.accessPolicies/searchPolicyBindings#try-it)

Returns all policy bindings that bind a specific policy if a user has searchPolicyBindings permission on that policy.

### HTTP request

`GET https://iam.googleapis.com/v3/{name=organizations/*/locations/*/accessPolicies/*}:searchPolicyBindings`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters |                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`     | `string` Required. The name of the Unified Access Policy. Format: \* `organizations/{organizationId}/locations/{location}/accessPolicies/{unified_access_policy_id}` \* `folders/{folderId}/locations/{location}/accessPolicies/{unified_access_policy_id}` \* `projects/{projectId}/locations/{location}/accessPolicies/{unified_access_policy_id}` \* `projects/{projectNumber}/locations/{location}/accessPolicies/{unified_access_policy_id}` |

### Query parameters

| Parameters  |                                                                                                                                                                                                                                                                                           |
|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `pageSize`  | `integer` Optional. The maximum number of Unified Access Policy bindings to return. The service might return a smaller number of bindings. If unspecified, at most 50 bindings are returned. The maximum value is 1000; values above 1000 are reduced to 1000.                            |
| `pageToken` | `string` Optional. A page token, received from a previous `SearchAccessPolicyBindingsRequest` call. Provide this to retrieve the subsequent page. When paginating, all other parameters provided to `SearchAccessPolicyBindingsRequest` must match the call that provided the page token. |

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of [`SearchAccessPolicyBindingsResponse`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/SearchAccessPolicyBindingsResponse) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
