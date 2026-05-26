---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/list
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/list
title: 'Method: locations.workforcePools.providers.scimTenants.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/list#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/list#body.ListWorkforcePoolProviderScimTenantsResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/list#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/list#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools.providers.scimTenants/list#try-it)

Gemini Enterprise only. Lists all non-deleted `  WorkforcePoolProviderScimTenant  ` s in a `  WorkforcePoolProvider  ` . If `showDeleted` is set to `true` , then deleted SCIM tenants are also listed.

### HTTP request

`GET https://iam.googleapis.com/v1/{parent=locations/*/workforcePools/*/providers/*}/scimTenants`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. Gemini Enterprise only. The parent to list SCIM tenants. Format: 'locations/{location}/workforcePools/{workforcePool}/providers/{provider}'

### Query parameters

Parameters

`pageSize`

`integer`

Optional. Gemini Enterprise only. The maximum number of SCIM tenants to return. If unspecified, at most 50 SCIM tenants will be returned. The maximum value is 100; values above 100 are truncated to 100.

`pageToken`

`string`

Optional. Gemini Enterprise only. A page token, received from a previous `ListScimTenants` call. Provide this to retrieve the subsequent page.

`showDeleted`

`boolean`

Optional. Gemini Enterprise only. Whether to return soft-deleted SCIM tenants.

### Request body

The request body must be empty.

### Response body

Gemini Enterprise only. Response message for scimTenants.list.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;workforcePoolProviderScimTenants&quot;: [{object (WorkforcePoolProviderScimTenant)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`workforcePoolProviderScimTenants[]`

` object ( WorkforcePoolProviderScimTenant  ` )

Output only. Gemini Enterprise only. A list of SCIM tenants.

`nextPageToken`

`string`

Optional. Gemini Enterprise only. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages.

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
