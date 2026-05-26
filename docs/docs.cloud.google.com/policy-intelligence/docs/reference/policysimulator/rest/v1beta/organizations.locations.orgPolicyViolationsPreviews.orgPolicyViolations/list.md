---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations/list
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations/list
title: 'Method: organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations.list'
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations/list#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations/list#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations/list#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations/list#body.request_body)
  - [Response body](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations/list#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations/list#body.ListOrgPolicyViolationsResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations/list#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations/list#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/v1beta/organizations.locations.orgPolicyViolationsPreviews.orgPolicyViolations/list#try-it)

orgPolicyViolations.list lists the \[OrgPolicyViolations\]\[\] that are present in an `  OrgPolicyViolationsPreview  ` .

### HTTP request

`GET https://policysimulator.googleapis.com/v1beta/{parent=organizations/*/locations/*/orgPolicyViolationsPreviews/*}/orgPolicyViolations`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The OrgPolicyViolationsPreview to get OrgPolicyViolations from. Format: organizations/{organization}/locations/{location}/orgPolicyViolationsPreviews/{orgPolicyViolationsPreview}

### Query parameters

Parameters

`pageSize`

`integer`

Optional. The maximum number of items to return. The service may return fewer than this value. If unspecified, at most 1000 items will be returned. The maximum value is 1000; values above 1000 will be coerced to 1000.

`pageToken`

`string`

Optional. A page token, received from a previous call. Provide this to retrieve the subsequent page.

When paginating, all other parameters must match the call that provided the page token.

### Request body

The request body must be empty.

### Response body

ListOrgPolicyViolationsResponse is the response message for `  OrgPolicyViolationsPreviewService.ListOrgPolicyViolations  `

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;orgPolicyViolations&quot;: [{object (OrgPolicyViolation)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`orgPolicyViolations[]`

` object ( OrgPolicyViolation  ` )

The list of OrgPolicyViolations

`nextPageToken`

`string`

A token that you can use to retrieve the next page of results. If this field is omitted, there are no subsequent pages.

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `parent` resource:

  - `policysimulator.orgPolicyViolations.list`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
