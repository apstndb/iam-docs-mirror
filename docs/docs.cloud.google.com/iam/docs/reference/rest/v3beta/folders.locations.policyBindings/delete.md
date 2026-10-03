---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/delete
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/delete
title: 'Method: folders.locations.policyBindings.delete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/delete#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/delete#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/delete#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/delete#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/delete#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/delete#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/delete#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings/delete#try-it)

Deletes a policy binding and returns a long-running operation. Callers will need the IAM permissions on both the policy and target. After the binding is deleted, the policy no longer applies to the target.

### HTTP request

`DELETE https://iam.googleapis.com/v3beta/{name=folders/*/locations/*/policyBindings/*}`

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
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>Required. The name of the policy binding to delete.</p>
<p>Format:</p>
<ul>
<li><code>projects/{projectId}/locations/{location}/policyBindings/{policyBindingId}</code></li>
<li><code>projects/{projectNumber}/locations/{location}/policyBindings/{policyBindingId}</code></li>
<li><code>folders/{folderId}/locations/{location}/policyBindings/{policyBindingId}</code></li>
<li><code>organizations/{organizationId}/locations/{location}/policyBindings/{policyBindingId}</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Query parameters

| Parameters     |                                                                                                          |
|----------------|----------------------------------------------------------------------------------------------------------|
| `etag`         | `string` Optional. The etag of the policy binding. If this is provided, it must match the server's etag. |
| `validateOnly` | `boolean` Optional. If set, validate the request and preview the deletion, but do not actually post it.  |

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of [`Operation`](https://docs.cloud.google.com/iam/docs/reference/rest/Shared.Types/Operation) .

### Authorization scopes

Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
