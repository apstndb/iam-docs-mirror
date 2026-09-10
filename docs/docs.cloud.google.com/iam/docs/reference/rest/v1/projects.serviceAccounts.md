---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts
title: 'REST Resource: projects.serviceAccounts'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

  - [Resource: ServiceAccount](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount)
      - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount.SCHEMA_REPRESENTATION)
  - [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#METHODS_SUMMARY)

## Resource: ServiceAccount

An IAM service account.

A service account is an account for an application or a virtual machine (VM) instance, not a person. You can use a service account to call Google APIs. To learn more, read the [overview of service accounts](https://cloud.google.com/iam/help/service-accounts/overview) .

When you create a service account, you specify the project ID that owns the service account, as well as a name that must be unique within the project. IAM uses these values to create an email address that identifies the service account. //

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
  &quot;name&quot;: string,
  &quot;projectId&quot;: string,
  &quot;uniqueId&quot;: string,
  &quot;email&quot;: string,
  &quot;displayName&quot;: string,
  &quot;etag&quot;: string,
  &quot;description&quot;: string,
  &quot;oauth2ClientId&quot;: string,
  &quot;disabled&quot;: boolean
}</code></pre></td>
</tr>
</tbody>
</table>

Fields

`name`

`string`

The resource name of the service account.

Use one of the following formats:

  - `projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}`

As an alternative, you can use the `-` wildcard character instead of the project ID:

  - `projects/-/serviceAccounts/{EMAIL_ADDRESS}`
  - `projects/-/serviceAccounts/{UNIQUE_ID}`

When possible, avoid using the `-` wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account `projects/-/serviceAccounts/fake@example.com` , which does not exist, the response contains an HTTP `403 Forbidden` error instead of a `404 Not Found` error.

`projectId`

`string`

Output only. The ID of the project that owns the service account.

`uniqueId`

`string`

Output only. The unique, stable numeric ID for the service account.

Each service account retains its unique ID even if you delete the service account. For example, if you delete a service account, then create a new service account with the same name, the new service account has a different unique ID than the deleted service account.

`email`

`string`

Output only. The email address of the service account.

`displayName`

`string`

Optional. A user-specified, human-readable name for the service account. The maximum length is 100 UTF-8 bytes.

` etag (deprecated)  `

`string ( bytes format)`

> This item is deprecated\!

Deprecated. Do not use.

A base64-encoded string.

`description`

`string`

Optional. A user-specified, human-readable description of the service account. The maximum length is 256 UTF-8 bytes.

`oauth2ClientId`

`string`

Output only. The OAuth 2.0 client ID for the service account.

`disabled`

`boolean`

Output only. Whether the service account is disabled.

## Methods

### `            create           `

Creates a `  ServiceAccount  ` .

### `            delete           `

Deletes a `  ServiceAccount  ` .

### `            disable           `

Disables a `  ServiceAccount  ` immediately.

### `            enable           `

Enables a `  ServiceAccount  ` that was disabled by `  DisableServiceAccount  ` .

### `            get           `

Gets a `  ServiceAccount  ` .

### `            getIamPolicy           `

Gets the IAM policy that is attached to a `  ServiceAccount  ` .

### `            list           `

Lists every `  ServiceAccount  ` that belongs to a specific project.

### `            patch           `

Patches a `  ServiceAccount  ` .

### `            setIamPolicy           `

Sets the IAM policy that is attached to a `  ServiceAccount  ` .

### `            signBlob             (deprecated)  `

Signs a blob using the system-managed private key for a `  ServiceAccount  ` .

### `            signJwt             (deprecated)  `

Signs a JSON Web Token (JWT) using the system-managed private key for a `  ServiceAccount  ` .

### `            testIamPermissions           `

Tests whether the caller has the specified permissions on a `  ServiceAccount  ` .

### `            undelete           `

Restores a deleted `  ServiceAccount  ` .

### `            update           `

**Note:** We are in the process of deprecating this method.
