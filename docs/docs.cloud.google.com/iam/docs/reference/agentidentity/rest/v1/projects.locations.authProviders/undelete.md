---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/undelete
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/undelete
title: 'Method: projects.locations.authProviders.undelete'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/undelete#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/undelete#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/undelete#body.request_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/undelete#body.request_body.SCHEMA_REPRESENTATION)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/undelete#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/undelete#body.aspect)
  - [IAM Permissions](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/undelete#body.aspect_1)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/agentidentity/rest/v1/projects.locations.authProviders/undelete#try-it)

Undeletes a single auth provider.

### HTTP request

`POST https://agentidentity.googleapis.com/v1/{name=projects/*/locations/*/authProviders/*}:undelete`

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
  &quot;requestId&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`requestId`

`string`

Optional. An optional request ID to identify requests. Specify a unique request ID so that if you must retry your request, the server will know to ignore the request if it has already been completed. The server will guarantee that for at least 60 minutes after the first request.

The request ID must be a valid UUID with the exception that zero UUID is not supported (00000000-0000-0000-0000-000000000000).

### Response body

If successful, the response body contains an instance of `  AuthProvider  ` .

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .

### IAM Permissions

Requires the following [IAM](https://cloud.google.com/iam/docs) permission on the `name` resource:

  - `agentidentity.authProviders.undelete`

For more information, see the [IAM documentation](https://cloud.google.com/iam/docs) .
