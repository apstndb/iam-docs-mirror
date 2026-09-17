---
name: documents/docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/groups
uri: https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/groups
title: 'Method: common.groups'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/groups#body.HTTP_TEMPLATE)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/groups#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/groups#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/groups#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/groups#body.FetchGroupsResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/groups#body.aspect)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/cloudoauth/rest/v1/common/groups#try-it)

Retrieves a list of groups for the authenticated user from the distributed claims endpoint.

Note: This endpoint is only supported for Looker.

### HTTP request

`GET https://cloudoauth.googleapis.com/v1/common/groups`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Query parameters

Parameters

`pageSize`

`integer`

Optional. The maximum number of groups to return. If unspecified, at most 2500 groups will be returned.

`pageToken`

`string`

Optional. A page token received from a previous `common.groups` call. Provide this to retrieve the subsequent page.

### Request body

The request body must be empty.

### Response body

Response message for `  common.groups  ` .

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{
  &quot;groups&quot;: [
    string
  ],
  &quot;nextPageToken&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`groups[]`

`string`

A paginated list of enterprise group memberships for the user.

`nextPageToken`

`string`

A token which can be sent as `pageToken` to retrieve the next page of results. If this field is empty or omitted, there are no subsequent pages. Note: Pagination is not supported in preview.

### Authorization scopes

Requires the following OAuth scope:

  - `openid`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
