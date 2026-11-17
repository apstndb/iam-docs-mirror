---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.accessPolicies/create
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.accessPolicies/create
title: 'Method: folders.locations.accessPolicies.create'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.accessPolicies/create#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.accessPolicies/create#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.accessPolicies/create#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.accessPolicies/create#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.accessPolicies/create#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.accessPolicies/create#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.accessPolicies/create#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.accessPolicies/create#try-it)

Creates a Unified Access Policy, and returns a long running operation.

### HTTP request

`POST https://iam.googleapis.com/v3/{parent=folders/*/locations/*}/accessPolicies`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters |                                                                                                                                                                                                                                                                                                     |
|------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `parent`   | `string` Required. The parent resource where this Unified Access Policy is created. Format: \* `projects/{projectId}/locations/{location}` \* `projects/{projectNumber}/locations/{location}` \* `folders/{folderId}/locations/{location}` \* `organizations/{organizationId}/locations/{location}` |

### Query parameters

| Parameters       |                                                                                                                                                                                                                                                                                                                                                                                      |
|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `accessPolicyId` | `string` Required. The ID to use for the Unified Access Policy, which will become the final component of the Unified Access Policy's resource name. This value must start with a lowercase letter followed by up to 62 lowercase letters, numbers, hyphens, or dots (/\[a-z\]\[a-z0-9-.\]{2,62}/). This value must be unique among all Unified Access Policies with the same parent. |
| `validateOnly`   | `boolean` Optional. If set, validate the request and preview the creation, but do not actually post it.                                                                                                                                                                                                                                                                              |

### Request body

The request body contains an instance of [`AccessPolicy`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.accessPolicies#AccessPolicy) .

### Response body

If successful, the response body contains a newly created instance of [`Operation`](https://docs.cloud.google.com/iam/docs/reference/rest/Shared.Types/Operation) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
