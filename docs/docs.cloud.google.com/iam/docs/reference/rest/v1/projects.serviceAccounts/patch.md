---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/patch
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/patch
title: 'Method: projects.serviceAccounts.patch'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [HTTP request](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/patch#body.HTTP_TEMPLATE)
  - [Path parameters](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/patch#body.PATH_PARAMETERS)
  - [Request body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/patch#body.request_body)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/patch#body.request_body.SCHEMA_REPRESENTATION)
  - [Response body](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/patch#body.response_body)
  - [Authorization scopes](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/patch#body.aspect)
  - [Examples](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/patch#examples)
  - [Try it\!](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/patch#try-it)

Patches a `  ServiceAccount  ` .

### HTTP request

`PATCH https://iam.googleapis.com/v1/{serviceAccount.name=projects/*/serviceAccounts/*}`

The URL uses [gRPC Transcoding](https://google.aip.dev/127) syntax.

### Path parameters

Parameters

`serviceAccount.name`

`string`

The resource name of the service account.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account `projects/-/serviceAccounts/fake@example.com` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

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
  &quot;serviceAccount&quot;: {
    &quot;name&quot;: string,
    &quot;projectId&quot;: string,
    &quot;uniqueId&quot;: string,
    &quot;email&quot;: string,
    &quot;displayName&quot;: string,
    &quot;etag&quot;: string,
    &quot;description&quot;: string,
    &quot;oauth2ClientId&quot;: string,
    &quot;disabled&quot;: boolean
  },
  &quot;updateMask&quot;: string
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`serviceAccount.projectId`

`string`

Output only. The ID of the project that owns the service account.

`serviceAccount.uniqueId`

`string`

Output only. The unique, stable numeric ID for the service account.

Each service account retains its unique ID even if you delete the service account. For example, if you delete a service account, then create a new service account with the same name, the new service account has a different unique ID than the deleted service account.

`serviceAccount.email`

`string`

Output only. The email address of the service account.

`serviceAccount.displayName`

`string`

Optional. A user-specified, human-readable name for the service account. The maximum length is 100 UTF-8 bytes.

` serviceAccount.etag (deprecated)  `

`string ( bytes format)`

Deprecated. Do not use.

A base64-encoded string.

`serviceAccount.description`

`string`

Optional. A user-specified, human-readable description of the service account. The maximum length is 256 UTF-8 bytes.

`serviceAccount.oauth2ClientId`

`string`

Output only. The OAuth 2.0 client ID for the service account.

`serviceAccount.disabled`

`boolean`

Output only. Whether the service account is disabled.

`updateMask`

` string ( FieldMask  ` format)

This is a comma-separated list of fully qualified names of fields. Example: `"user.displayName,photo"` .

### Response body

If successful, the response body contains an instance of `  ServiceAccount  ` .

### Authorization scopes

Requires one of the following OAuth scopes:

  - `https://www.googleapis.com/auth/iam`
  - `https://www.googleapis.com/auth/cloud-platform`

For more information, see the [Authentication Overview](https://docs.cloud.google.com/docs/authentication#authorization-gcp) .
