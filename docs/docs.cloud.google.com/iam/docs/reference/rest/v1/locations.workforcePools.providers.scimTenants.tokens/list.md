---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/list
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/list
title: 'Method: locations.workforcePools.providers.scimTenants.tokens.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/list#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/list#body.ListWorkforcePoolProviderScimTokensResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/list#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/list#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants.tokens/list#try-it)

Gemini Enterprise only. Lists all non-deleted \[WorkforcePoolProviderScimTokens\]\[\]s in a `  WorkforcePoolProviderScimTenant  ` . If `showDeleted` is set to `true` , then deleted SCIM tokens are also listed.

### HTTP request

`GET https://iam.googleapis.com/v1/{parent=locations/*/workforcePools/*/providers/*/scimTenants/*}/tokens`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. Gemini Enterprise only. The parent to list SCIM tokens. Format: 'locations/{location}/workforcePools/{workforcePool}/providers/{provider}/scimTenants/{scim\_tenant}'

### Query parameters

Parameters

`pageSize`

`integer`

Optional. Gemini Enterprise only. The maximum number of SCIM tokens to return. If unspecified, at most 2 SCIM tokens will be returned.

`pageToken`

`string`

Optional. Gemini Enterprise only. A page token, received from a previous `tokens.list` call. Provide this to retrieve the subsequent page.

`showDeleted`

`boolean`

Optional. Gemini Enterprise only. Whether to return soft-deleted SCIM tokens.

### Request body

The request body must be empty.

### Response body

Gemini Enterprise only. Response message for tokens.list.

If successful, the response body contains data with the following structure:

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>JSON representation</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;workforcePoolProviderScimTokens&quot;: [{object (WorkforcePoolProviderScimToken)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`workforcePoolProviderScimTokens[]`

` object ( WorkforcePoolProviderScimToken  ` )

Output only. Gemini Enterprise only. A list of SCIM tokens.

`nextPageToken`

`string`

Optional. Gemini Enterprise only. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages.

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
