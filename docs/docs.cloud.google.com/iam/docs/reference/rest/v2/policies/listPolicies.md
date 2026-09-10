---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v2/policies/listPolicies
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/listPolicies
title: 'Method: policies.listPolicies'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/listPolicies#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/listPolicies#body.PATH_PARAMETERS)
  - [Query parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/listPolicies#body.QUERY_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/listPolicies#body.request_body)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/listPolicies#body.response_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/listPolicies#body.ListPoliciesResponse.SCHEMA_REPRESENTATION)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/listPolicies#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/listPolicies#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v2/policies/listPolicies#try-it)

Retrieves the policies of the specified kind that are attached to a resource.

The response lists only policy metadata. In particular, policy rules are omitted.

### HTTP request

`GET https://iam.googleapis.com/v2/{parent=policies/*/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`parent`

`string`

Required. The resource that the policy is attached to, along with the kind of policy to list. Format: `policies/{attachmentPoint}/denypolicies`

The attachment point is identified by its URL-encoded full resource name, which means that the forward-slash character, `/` , must be written as `%2F` . For example, `policies/cloudresourcemanager.googleapis.com%2Fprojects%2Fmy-project/denypolicies` .

For organizations and folders, use the numeric ID in the full resource name. For projects, you can use the alphanumeric or the numeric ID.

### Query parameters

Parameters

`pageSize`

`integer`

The maximum number of policies to return. IAM ignores this value and uses the value 1000.

`pageToken`

`string`

A page token received in a `  ListPoliciesResponse  ` . Provide this token to retrieve the next page.

### Request body

The request body must be empty.

### Response body

Response message for `policies.listPolicies` .

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
<td><pre dir="ltr" data-is-upgraded="" style="border: 0;margin: 0;" translate="no"><code>{&quot;policies&quot;: [{object (Policy)}],&quot;nextPageToken&quot;: string}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`policies[]`

` object ( Policy  ` )

Metadata for the policies that are attached to the resource.

`nextPageToken`

`string`

A page token that you can use in a `ListPoliciesRequest` to retrieve the next page. If this field is omitted, there are no additional pages.

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/cloud-platform`
  - `https://www.googleapis.com/auth/iam`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
