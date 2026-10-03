---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/get
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/get
title: 'Method: organizations.locations.policyBindings.get'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/get#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/get#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/get#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/get#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/get#body.aspect)
- [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/get#body.aspect_1)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/get#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.policyBindings/get#try-it)

Gets a policy binding.

### HTTP request

`GET https://iam.googleapis.com/v3beta/{name=organizations/*/locations/*/policyBindings/*}`

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
<p>Required. The name of the policy binding to retrieve.</p>
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

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of [`PolicyBinding`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.policyBindings#PolicyBinding) .

### Authorization scopes

Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

- `iam.policybindings.get`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
