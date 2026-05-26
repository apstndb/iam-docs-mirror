---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/revoke
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/revoke
title: 'Method: projects.locations.entitlements.grants.revoke'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/revoke#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/revoke#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/revoke#body.request_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/revoke#body.request_body.SCHEMA_REPRESENTATION)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/revoke#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/revoke#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/revoke#body.aspect_1)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/revoke#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/projects.locations.entitlements.grants/revoke#try-it)

`grants.revoke` is used to immediately revoke access for a grant. This method can be called when the grant is in a non-terminal state.

### HTTP request

`POST https://privilegedaccessmanager.googleapis.com/v1beta/{name=projects/*/locations/*/entitlements/*/grants/*}:revoke`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. Name of the grant resource which is being revoked.

### Request body

The request body contains data with the following structure:

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
  &quot;reason&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`reason`

`string`

Optional. The reason for revoking this grant.

### Response body

If successful, the response body contains an instance of `  Operation  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `privilegedaccessmanager.grants.revoke`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
