---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/searchTargetPolicyBindings
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/searchTargetPolicyBindings
title: 'Method: folders.locations.policyBindings.searchTargetPolicyBindings'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/searchTargetPolicyBindings#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/searchTargetPolicyBindings#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/searchTargetPolicyBindings#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/searchTargetPolicyBindings#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/searchTargetPolicyBindings#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/searchTargetPolicyBindings#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/searchTargetPolicyBindings#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/searchTargetPolicyBindings#try-it)

Search policy bindings by target. Returns all policy binding objects bound directly to target.

### HTTP request

`GET https://iam.googleapis.com/v3beta/{parent=folders/*/locations/*}/policyBindings:searchTargetPolicyBindings`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource where this search will be performed. This should be the nearest Resource Manager resource (project, folder, or organization) to the target.

Format:

  - `projects/{projectId}/locations/{location}`
  - `projects/{projectNumber}/locations/{location}`
  - `folders/{folderId}/locations/{location}`
  - `organizations/{organizationId}/locations/{location}`

### Query parameters

Parameters

`target`

`string`

Required. The target resource, which is bound to the policy in the binding.

Format:

  - `//iam.googleapis.com/locations/global/workforcePools/POOL_ID`
  - `//iam.googleapis.com/projects/PROJECT_NUMBER/locations/global/workloadIdentityPools/POOL_ID`
  - `//iam.googleapis.com/locations/global/workspace/WORKSPACE_ID`
  - `//cloudresourcemanager.googleapis.com/projects/{projectNumber}`
  - `//cloudresourcemanager.googleapis.com/folders/{folderId}`
  - `//cloudresourcemanager.googleapis.com/organizations/{organizationId}`

`pageSize`

`integer`

Optional. The maximum number of policy bindings to return. The service may return fewer than this value.

The default value is 50. The maximum value is 1000.

`pageToken`

`string`

Optional. A page token, received from a previous `SearchTargetPolicyBindingsRequest` call. Provide this to retrieve the subsequent page.

When paginating, all other parameters provided to `SearchTargetPolicyBindingsRequest` must match the call that provided the page token.

`filter`

`string`

Optional. Filtering currently only supports the kind of policies to return, and must be in the format "policyKind={policyKind}".

If String is empty, bindings bound to all kinds of policies would be returned.

The only supported values are the following:

  - "policyKind=PRINCIPAL\_ACCESS\_BOUNDARY",
  - "policyKind=ACCESS"

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of `  SearchTargetPolicyBindingsResponse  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
