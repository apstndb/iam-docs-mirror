---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/patch
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/patch
title: 'Method: organizations.locations.policyBindings.patch'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/patch#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/patch#body.PATH_PARAMETERS)
- [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/patch#body.QUERY_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/patch#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/patch#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/patch#body.aspect)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/patch#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/patch#try-it)

Updates a policy binding and returns a long-running operation. Callers will need the IAM permissions on the policy and target in the binding to update. Target and policy are immutable and cannot be updated.

### HTTP request

`PATCH https://iam.googleapis.com/v3beta/{policyBinding.name=organizations/*/locations/*/policyBindings/*}`

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
<td><code>policyBinding.name</code></td>
<td><p><code>string</code></p>
<p>Identifier. The name of the policy binding, in the format <code>{binding_parent/locations/{location}/policyBindings/{policyBindingId}</code> . The binding parent is the closest Resource Manager resource (project, folder, or organization) to the binding target.</p>
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

| Parameters     |                                                                                                                                                                                                                                                         |
|----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `validateOnly` | `boolean` Optional. If set, validate the request and preview the update, but do not actually post it.                                                                                                                                                   |
| `updateMask`   | `string ( `[`FieldMask`](https://protobuf.dev/reference/protobuf/google.protobuf/#field-mask)` format)` Optional. The list of fields to update This is a comma-separated list of fully qualified names of fields. Example: `"user.displayName,photo"` . |

### Request body

The request body contains an instance of [`PolicyBinding`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings#PolicyBinding) .

### Response body

If successful, the response body contains an instance of [`Operation`](https://docs.cloud.google.com/iam/docs/reference/rest/Shared.Types/Operation) .

### Authorization scopes

Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
