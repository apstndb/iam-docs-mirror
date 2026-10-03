---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/searchTargetPolicyBindings
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/searchTargetPolicyBindings
title: 'Method: projects.locations.policyBindings.searchTargetPolicyBindings'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/searchTargetPolicyBindings#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/searchTargetPolicyBindings#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/searchTargetPolicyBindings#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/searchTargetPolicyBindings#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/searchTargetPolicyBindings#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/searchTargetPolicyBindings#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/searchTargetPolicyBindings#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/searchTargetPolicyBindings#try-it)

Search policy bindings by target. Returns all policy binding objects bound directly to target.

### HTTP request

`GET https://iam.googleapis.com/v3/{parent=projects/*/locations/*}/policyBindings:searchTargetPolicyBindings`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Parameters</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>parent</code></td>
<td><p><code>string</code></p>
<p>Required. The parent resource where this search will be performed. This should be the nearest Resource Manager resource (project, folder, or organization) to the target.</p>
<p>Format:</p>
<ul>
<li><code>projects/{projectId}/locations/{location}</code></li>
<li><code>projects/{projectNumber}/locations/{location}</code></li>
<li><code>folders/{folderId}/locations/{location}</code></li>
<li><code>organizations/{organizationId}/locations/{location}</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Query parameters

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Parameters</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>target</code></td>
<td><p><code>string</code></p>
<p>Required. The target resource, which is bound to the policy in the binding.</p>
<p>Format:</p>
<ul>
<li><code>//iam.googleapis.com/locations/global/workforcePools/POOL_ID</code></li>
<li><code>//iam.googleapis.com/projects/PROJECT_NUMBER/locations/global/workloadIdentityPools/POOL_ID</code></li>
<li><code>//iam.googleapis.com/locations/global/workspace/WORKSPACE_ID</code></li>
<li><code>//cloudresourcemanager.googleapis.com/projects/{projectNumber}</code></li>
<li><code>//cloudresourcemanager.googleapis.com/folders/{folderId}</code></li>
<li><code>//cloudresourcemanager.googleapis.com/organizations/{organizationId}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>pageSize</code></td>
<td><p><code>integer</code></p>
<p>Optional. The maximum number of policy bindings to return. The service may return fewer than this value.</p>
<p>The default value is 50. The maximum value is 1000.</p></td>
</tr>
<tr class="odd">
<td><code>pageToken</code></td>
<td><p><code>string</code></p>
<p>Optional. A page token, received from a previous <code>SearchTargetPolicyBindingsRequest</code> call. Provide this to retrieve the subsequent page.</p>
<p>When paginating, all other parameters provided to <code>SearchTargetPolicyBindingsRequest</code> must match the call that provided the page token.</p></td>
</tr>
</tbody>
</table>

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of [`SearchTargetPolicyBindingsResponse`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/SearchTargetPolicyBindingsResponse) .

### Authorization scopes

Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
