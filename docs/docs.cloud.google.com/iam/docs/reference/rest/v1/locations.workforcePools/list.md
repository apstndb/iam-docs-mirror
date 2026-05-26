---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools/list
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools/list
title: 'Method: locations.workforcePools.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools/list#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools/list#body.ListWorkforcePoolsResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools/list#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools/list#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/locations.workforcePools/list#try-it)

Lists all non-deleted `  WorkforcePool  ` s under the specified parent. If `showDeleted` is set to `true` , then deleted pools are also listed.

### HTTP request

`GET https://iam.googleapis.com/v1/{location=locations/*}/workforcePools`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`location`

`string`

The location of the pool.

Format: `locations/{location}` .

### Query parameters

Parameters

`parent`

`string`

Required. The parent resource to list pools for.

Format: `organizations/{org-id}` .

`pageSize`

`integer`

The maximum number of pools to return. The default value is 50. The maximum value is 100.

`pageToken`

`string`

A page token, received from a previous `workforcePools.list` call. Provide this to retrieve the subsequent page.

`showDeleted`

`boolean`

Whether to return soft-deleted pools.

### Request body

The request body must be empty.

### Response body

Response message for workforcePools.list.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;workforcePools&quot;: [{object (WorkforcePool)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`workforcePools[]`

` object ( WorkforcePool  ` )

A list of pools.

`nextPageToken`

`string`

A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages.

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
