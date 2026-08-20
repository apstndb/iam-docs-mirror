---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/query
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/query
title: 'Method: projects.locations.authProviders.query'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/query#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/query#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/query#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/query#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/query#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/query#body.QueryAuthProvidersResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/query#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/query#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/query#try-it)

Queries which auth providers are used by a given workload ID.

### HTTP request

`GET https://agentidentity.googleapis.com/v1/{parent=projects/*/locations/*}/authProviders:query`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource where the search is performed. Format: projects/{project}/locations/{location}

### Query parameters

Parameters

`workloadId`

`string`

Required. The workload identifier to filter by.

`pageSize`

`integer`

Optional. Requested page size. Server may return fewer items than requested. If unspecified, server will pick an appropriate default. The maximum page size is 1000.

`pageToken`

`string`

Optional. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, the first page is returned.

A page token, received from a previous authProviders.query call. Provide this to retrieve the subsequent page. When paginating, all other parameters provided to authProviders.query must match the call that provided the page token.

### Request body

The request body must be empty.

### Response body

Response message for `authProviders.query` .

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
  &quot;authProviderNames&quot;: [
    string
  ],
  &quot;nextPageToken&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`authProviderNames[]`

`string`

The unique list of auth provider resource names used by the workload.

`nextPageToken`

`string`

A token identifying a page of results the server should return. If this field is omitted, there are no subsequent pages.

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `agentidentity.authProviders.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
