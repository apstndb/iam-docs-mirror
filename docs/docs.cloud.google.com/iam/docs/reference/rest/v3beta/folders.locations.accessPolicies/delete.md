---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/delete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/delete
title: 'Method: folders.locations.accessPolicies.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/delete#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/delete#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/delete#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/delete#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/delete#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/delete#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/delete#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies/delete#try-it)

Deletes a Unified Access Policy.

### HTTP request

`DELETE https://iam.googleapis.com/v3beta/{name=folders/*/locations/*/accessPolicies/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

| Parameters |                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`     | `string` Required. The name of the Unified Access Policy to delete. Format: \* `projects/{projectId}/locations/{location}/accessPolicies/{unified_access_policy_id}` \* `projects/{projectNumber}/locations/{location}/accessPolicies/{unified_access_policy_id}` \* `folders/{folderId}/locations/{location}/accessPolicies/{unified_access_policy_id}` \* `organizations/{organizationId}/locations/{location}/accessPolicies/{unified_access_policy_id}` |

### Query parameters

| Parameters     |                                                                                                                                                                                                                                                                            |
|----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `etag`         | `string` Optional. The etag of the Unified Access Policy. If this is provided, it must match the server's etag.                                                                                                                                                            |
| `validateOnly` | `boolean` Optional. If set, validate the request and preview the deletion, but do not actually post it.                                                                                                                                                                    |
| `force`        | `boolean` Optional. If set to true, the request will force the deletion of the Unified Access Policy even if it's referenced in existing bindings. If this value is set to false and the Unified Access Policy is referenced in existing bindings, then the request fails. |

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of [`Operation`](https://docs.cloud.google.com/iam/docs/reference/rest/Shared.Types/Operation) .

### Authorization scopes

Requires one of the following OAuth scopes:

- `https://www.googleapis.com/auth/cloud-platform`
- `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
