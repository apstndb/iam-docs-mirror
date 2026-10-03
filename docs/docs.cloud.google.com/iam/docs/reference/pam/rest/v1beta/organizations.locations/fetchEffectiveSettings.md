---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/fetchEffectiveSettings
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/fetchEffectiveSettings
title: 'Method: organizations.locations.fetchEffectiveSettings'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/fetchEffectiveSettings#body.HTTP_TEMPLATE)
- [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/fetchEffectiveSettings#body.PATH_PARAMETERS)
- [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/fetchEffectiveSettings#body.request_body)
- [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/fetchEffectiveSettings#body.response_body)
- [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/fetchEffectiveSettings#body.aspect)
- [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/fetchEffectiveSettings#body.aspect_1)
- [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/fetchEffectiveSettings#examples)
- [Try it!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations/fetchEffectiveSettings#try-it)

`locations.fetchEffectiveSettings` returns the effective PAM Settings for the given project, folder, or organization.

### HTTP request

`GET https://privilegedaccessmanager.googleapis.com/v1beta/{parent=organizations/*/locations/*}:fetchEffectiveSettings`

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
<p>Required. The resource for which the effective settings is fetched, in one of the following formats:</p>
<ul>
<li><code>projects/{project-number|project-id}/locations/{region}</code></li>
<li><code>folders/{folder-number}/locations/{region}</code></li>
<li><code>organizations/{organization-number}/locations/{region}</code></li>
</ul></td>
</tr>
</tbody>
</table>

### Request body

The request body must be empty.

### Response body

If successful, the response body contains an instance of [`FetchEffectiveSettingsResponse`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/FetchEffectiveSettingsResponse) .

### Authorization scopes

Requires the following OAuth scope:

- `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

- `privilegedaccessmanager.settings.fetchEffective`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
