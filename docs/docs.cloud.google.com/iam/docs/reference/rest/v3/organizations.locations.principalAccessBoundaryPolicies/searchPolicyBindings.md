---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/searchPolicyBindings
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/searchPolicyBindings
title: 'Method: organizations.locations.principalAccessBoundaryPolicies.searchPolicyBindings'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/searchPolicyBindings#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/searchPolicyBindings#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/searchPolicyBindings#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/searchPolicyBindings#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/searchPolicyBindings#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/searchPolicyBindings#body.SearchPrincipalAccessBoundaryPolicyBindingsResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/searchPolicyBindings#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/searchPolicyBindings#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/searchPolicyBindings#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v3/organizations.locations.principalAccessBoundaryPolicies/searchPolicyBindings#try-it)

Returns all policy bindings that bind a specific policy if a user has searchPolicyBindings permission on that policy.

### HTTP request

`GET https://iam.googleapis.com/v3/{name=organizations/*/locations/*/principalAccessBoundaryPolicies/*}:searchPolicyBindings`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The name of the principal access boundary policy. Format: `organizations/{organizationId}/locations/{location}/principalAccessBoundaryPolicies/{principalAccessBoundaryPolicyId}`

### Query parameters

Parameters

`pageSize`

`integer`

Optional. The maximum number of policy bindings to return. The service may return fewer than this value.

If unspecified, at most 50 policy bindings will be returned. The maximum value is 1000; values above 1000 will be coerced to 1000.

`pageToken`

`string`

Optional. A page token, received from a previous `SearchPrincipalAccessBoundaryPolicyBindingsRequest` call. Provide this to retrieve the subsequent page.

When paginating, all other parameters provided to `SearchPrincipalAccessBoundaryPolicyBindingsRequest` must match the call that provided the page token.

### Request body

The request body must be empty.

### Response body

Response message for principalAccessBoundaryPolicies.searchPolicyBindings rpc.

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;policyBindings&quot;: [{object (PolicyBinding)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`policyBindings[]`

` object ( PolicyBinding  ` )

The policy bindings that reference the specified policy.

`nextPageToken`

`string`

Optional. A token, which can be sent as `pageToken` to retrieve the next page. If this field is omitted, there are no subsequent pages.

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `iam.principalaccessboundarypolicies.searchPolicyBindings`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
