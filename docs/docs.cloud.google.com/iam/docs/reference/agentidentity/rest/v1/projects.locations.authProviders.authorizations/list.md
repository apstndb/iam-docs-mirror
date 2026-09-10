---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/list
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/list
title: 'Method: projects.locations.authProviders.authorizations.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/list#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/list#body.ListAuthorizationsResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/list#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/list#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders.authorizations/list#try-it)

Lists authorizations in a given project and location.

### HTTP request

`GET https://agentidentity.googleapis.com/v1/{parent=projects/*/locations/*/authProviders/*}/authorizations`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource where the search is performed. Format: projects/{project}/locations/{location}/authProviders/{authProvider}

### Query parameters

Parameters

`pageSize`

`integer`

Optional. Requested page size. Server may return fewer items than requested. If unspecified, server will pick an appropriate default. The maximum page size is 1000.

`pageToken`

`string`

Optional. A page token, received from a previous `authorizations.list` call. Provide this to retrieve the subsequent page. When paginating, all other parameters provided to `authorizations.list` must match the call that provided the page token.

`filter`

`string`

Optional. Filter string to restrict the results. Currently supports filtering by `clientUserId` only. Format: `clientUserId="<value>"`

`orderBy`

`string`

Optional. This field is currently ignored. Defaults to ordering by authorization\_id in ascending order.

### Request body

The request body must be empty.

### Response body

Response message for `authorizations.list` .

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;authorizations&quot;: [{object (Authorization)}],&quot;nextPageToken&quot;: string,&quot;unreachable&quot;: [string]}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`authorizations[]`

` object ( Authorization  ` )

The list of authorizations.

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

  - `agentidentity.authorizations.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
