---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces/list
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces/list
title: 'Method: projects.locations.workloadIdentityPools.namespaces.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces/list#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces/list#body.ListWorkloadIdentityPoolNamespacesResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces/list#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces/list#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.locations.workloadIdentityPools.namespaces/list#try-it)

Lists all non-deleted `  WorkloadIdentityPoolNamespace  ` s in a workload identity pool. If `showDeleted` is set to `true` , then deleted namespaces are also listed.

### HTTP request

`GET https://iam.googleapis.com/v1/{parent=projects/*/locations/*/workloadIdentityPools/*}/namespaces`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource to list namespaces for.

### Query parameters

Parameters

`pageSize`

`integer`

The maximum number of namespaces to return. If unspecified, at most 50 namespaces are returned. The maximum value is 1000; values above are 1000 truncated to 1000.

`pageToken`

`string`

A page token, received from a previous `namespaces.list` call. Provide this to retrieve the subsequent page.

`showDeleted`

`boolean`

Whether to return soft-deleted namespaces.

### Request body

The request body must be empty.

### Response body

Response message for namespaces.list.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;workloadIdentityPoolNamespaces&quot;: [{object (WorkloadIdentityPoolNamespace)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`workloadIdentityPoolNamespaces[]`

` object ( WorkloadIdentityPoolNamespace  ` )

A list of namespaces.

`nextPageToken`

`string`

A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages.

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
