---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/list
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/list
title: 'Method: organizations.locations.principalAccessBoundaryPolicies.list'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/list#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/list#body.ListPrincipalAccessBoundaryPoliciesResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/list#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/list#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/list#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/list#try-it)

Lists principal access boundary policies.

### HTTP request

`GET https://iam.googleapis.com/v3/{parent=organizations/*/locations/*}/principalAccessBoundaryPolicies`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The parent resource, which owns the collection of principal access boundary policies.

Format: `organizations/{organizationId}/locations/{location}`

### Query parameters

Parameters

`pageSize`

`integer`

Optional. The maximum number of principal access boundary policies to return. The service may return fewer than this value.

If unspecified, at most 50 principal access boundary policies will be returned. The maximum value is 1000; values above 1000 will be coerced to 1000.

`pageToken`

`string`

Optional. A page token, received from a previous `principalAccessBoundaryPolicies.list` call. Provide this to retrieve the subsequent page.

When paginating, all other parameters provided to `principalAccessBoundaryPolicies.list` must match the call that provided the page token.

### Request body

The request body must be empty.

### Response body

Response message for principalAccessBoundaryPolicies.list method.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;principalAccessBoundaryPolicies&quot;: [{object (PrincipalAccessBoundaryPolicy)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`principalAccessBoundaryPolicies[]`

` object ( PrincipalAccessBoundaryPolicy  ` )

The principal access boundary policies from the specified parent.

`nextPageToken`

`string`

Optional. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages.

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `iam.principalaccessboundarypolicies.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
