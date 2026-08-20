---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries/list
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries/list
title: 'Method: projects.locations.accessSummaries.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries/list#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries/list#body.ListAccessSummariesResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries/list#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries/list#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1beta/projects.locations.accessSummaries/list#try-it)

Lists access summaries in a given project and location. Supported filters: - `workloadId` : Filter by the SPIFFE ID of the agent. Example: `workloadId="spiffe://example.com/ns/default/sa/my-agent"`

### HTTP request

`GET https://agentidentity.googleapis.com/v1beta/{parent=projects/*/locations/*}/accessSummaries`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource where the search is performed. Format: projects/{project}/locations/{location}

### Query parameters

Parameters

`pageSize`

`integer`

Optional. Requested page size. Server may return fewer items than requested. If unspecified, server will pick an appropriate default. The maximum page size is 1000.

`pageToken`

`string`

Optional. A token identifying a page of results the server should return.

`filter`

`string`

Optional. Filter string to restrict the results.

Currently supports filtering by `workloadId` or `authProviderName` . If no filter is provided, returns all access summaries for the requested project and location. Format: `workloadId="<value>"` or `authProviderName="<value>"`

`orderBy`

`string`

Optional. This field is currently ignored. Defaults to ordering by (authProviderId, userId) in ascending order.

### Request body

The request body must be empty.

### Response body

Response message for `accessSummaries.list` .

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;accessSummaries&quot;: [{object (AccessSummary)}],&quot;nextPageToken&quot;: string,&quot;unreachable&quot;: [string]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`accessSummaries[]`

` object ( AccessSummary  ` )

The list of access summaries.

`nextPageToken`

`string`

A token identifying a page of results the server should return.

`unreachable[]`

`string`

Unordered list. Locations that could not be reached.

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `agentidentity.accessSummaries.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
