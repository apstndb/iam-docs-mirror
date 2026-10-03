---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/patch
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/patch
title: 'Method: organizations.locations.accessPolicies.patch'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/patch#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/patch#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/patch#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/patch#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/patch#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/patch#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/patch#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/patch#try-it)

Updates an access policy.

### HTTP request

`PATCH https://iam.googleapis.com/v3beta/{accessPolicy.name=organizations/*/locations/*/accessPolicies/*}`

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
<td><code>accessPolicy.name</code></td>
<td><p><code>string</code></p>
<p>Identifier. The resource name of the access policy.</p>
<p>The following formats are supported:</p>
<ul>
<li><code>projects/{projectId}/locations/{location}/accessPolicies/{policyId}</code></li>
<li><code>projects/{projectNumber}/locations/{location}/accessPolicies/{policyId}</code></li>
<li><code>folders/{folderId}/locations/{location}/accessPolicies/{policyId}</code></li>
<li><code>organizations/{organizationId}/locations/{location}/accessPolicies/{policyId}</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Query parameters

| Parameters     |                                                                                                       |
|----------------|-------------------------------------------------------------------------------------------------------|
| `validateOnly` | `boolean` Optional. If set, validate the request and preview the update, but do not actually post it. |

### Request body

The request body contains an instance of [`AccessPolicy`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy) .

### Response body

If successful, the response body contains an instance of [`Operation`](https://docs.cloud.google.com/iam/docs/reference/rest/Shared.Types/Operation) .

### Authorization scopes

Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
