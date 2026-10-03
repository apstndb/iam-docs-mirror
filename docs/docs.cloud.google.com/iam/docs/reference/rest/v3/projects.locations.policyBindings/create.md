---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/create
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/create
title: 'Method: projects.locations.policyBindings.create'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/create#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/create#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/create#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/create#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/create#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/create#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/create#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v3/projects.locations.policyBindings/create#try-it)

Creates a policy binding and returns a long-running operation. Callers will need the IAM permissions on both the policy and target. After the binding is created, the policy is applied to the target.

### HTTP request

`POST https://iam.googleapis.com/v3/{parent=projects/*/locations/*}/policyBindings`

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
<p>Required. The parent resource where this policy binding will be created. The binding parent is the closest Resource Manager resource (project, folder or organization) to the binding target.</p>
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

| Parameters        |                                                                                                                                                                                                                                                                                              |
|-------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policyBindingId` | `string` Required. The ID to use for the policy binding, which will become the final component of the policy binding's resource name. This value must start with a lowercase letter followed by up to 62 lowercase letters, numbers, hyphens, or dots. Pattern, /\[a-z\]\[a-z0-9-.\]{2,62}/. |
| `validateOnly`    | `boolean` Optional. If set, validate the request and preview the creation, but do not actually post it.                                                                                                                                                                                      |

### Request body

The request body contains an instance of [`PolicyBinding`](https://docs.cloud.google.com/iam/docs/reference/rest/v3/folders.locations.policyBindings#PolicyBinding) .

### Response body

If successful, the response body contains a newly created instance of [`Operation`](https://docs.cloud.google.com/iam/docs/reference/rest/Shared.Types/Operation) .

### Authorization scopes

Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
