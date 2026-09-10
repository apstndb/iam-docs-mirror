---
name: documents/docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/finalize
uri: https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/finalize
title: 'Method: projects.locations.authProviders.credentials.finalize'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/finalize#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/finalize#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/finalize#body.request_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/finalize#body.request_body.SCHEMA_REPRESENTATION)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/finalize#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/finalize#body.aspect)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/finalize#try-it)

Finalizes the credentials after a successful consent flow.

### HTTP request

`POST https://agentidentitycredentials.googleapis.com/v1/{authProvider=projects/*/locations/*/authProviders/*}/credentials:finalize`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`authProvider`

`string`

Required. The resource name of the auth provider. Format: `projects/{project}/locations/{location}/authProviders/{authProvider}`

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
  &quot;userId&quot;: string,
  &quot;userIdValidationState&quot;: string,
  &quot;consentNonce&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`userId`

`string`

Required. The identity of the end user.

`userIdValidationState`

`string ( bytes format)`

Required. The encrypted state passed back from the consent flow.

A base64-encoded string.

`consentNonce`

`string`

Required. The same `consentNonce` value that was provided during retrieval in the [UriConsentRequired](https://docs.cloud.google.com/iam/docs/reference/agentidentitycredentials/rest/v1/projects.locations.authProviders.credentials/retrieve#UriConsentRequired) metadata.

### Response body

If successful, the response body is empty.

### Authorization scopes

Requires the following OAuth scope:

  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
