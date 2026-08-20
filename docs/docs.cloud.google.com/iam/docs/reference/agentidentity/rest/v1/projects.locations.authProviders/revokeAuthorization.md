---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/revokeAuthorization
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/revokeAuthorization
title: 'Method: projects.locations.authProviders.revokeAuthorization'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/revokeAuthorization#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/revokeAuthorization#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/revokeAuthorization#body.request_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/revokeAuthorization#body.request_body.SCHEMA_REPRESENTATION)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/revokeAuthorization#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/revokeAuthorization#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/revokeAuthorization#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/revokeAuthorization#try-it)

Revokes all authorizations for a specific user on an auth provider. This deletes all authorization records associated with the user and auth provider, effectively revoking access across all agents.

### HTTP request

`POST https://agentidentity.googleapis.com/v1/{name=projects/*/locations/*/authProviders/*}:revokeAuthorization`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`name`

`string`

Required. The resource name of the auth provider. Format: projects/{project}/locations/{location}/authProviders/{authProvider}

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
  &quot;userId&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`userId`

`string`

Required. The identity of the user to revoke authorization for.

### Response body

If successful, the response body is empty.

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `agentidentity.authProviders.revokeAuthorizations`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
