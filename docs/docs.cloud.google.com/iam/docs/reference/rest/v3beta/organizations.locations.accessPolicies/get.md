---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/get
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/get
title: 'Method: organizations.locations.accessPolicies.get'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/get#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/get#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/get#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/get#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/get#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/get#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/get#try-it)

Gets a Unified Access Policy.

### HTTP request

`GET https://iam.googleapis.com/v3beta/{name=organizations/*/locations/*/accessPolicies/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters |                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`     | `string` Required. The name of the Unified Access Policy to retrieve. Format: \* `projects/{projectId}/locations/{location}/accessPolicies/{unified_access_policy_id}` \* `projects/{projectNumber}/locations/{location}/accessPolicies/{unified_access_policy_id}` \* `folders/{folderId}/locations/{location}/accessPolicies/{unified_access_policy_id}` \* `organizations/{organizationId}/locations/{location}/accessPolicies/{unified_access_policy_id}` |

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of [`AccessPolicy`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
