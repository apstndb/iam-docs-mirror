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

**JSON representation**

```
{
  "name": string,
  "projectId": string,
  "uniqueId": string,
  "email": string,
  "displayName": string,
  "etag": string,
  "description": string,
  "oauth2ClientId": string,
  "disabled": boolean
}
```

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Fields</th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><code>name</code></td>
<td><p><code>string</code></p>
<p>The resource name of the service account.</p>
<p>Use one of the following formats:</p>
<ul>
<li><code>projects/{PROJECT_ID}/serviceAccounts/{EMAIL_ADDRESS}</code></li>
<li><code>projects/{PROJECT_ID}/serviceAccounts/{UNIQUE_ID}</code></li>
</ul>
<p>As an alternative, you can use the <code>-</code> wildcard character instead of the project ID:</p>
<ul>
<li><code>projects/-/serviceAccounts/{EMAIL_ADDRESS}</code></li>
<li><code>projects/-/serviceAccounts/{UNIQUE_ID}</code></li>
</ul>
<p>When possible, avoid using the <code>-</code> wildcard character, because it can cause response messages to contain misleading error codes. For example, if you try to access the service account <code>projects/-/serviceAccounts/fake@example.com</code> , which does not exist, the response contains an HTTP <code>403 Forbidden</code> error instead of a <code>404 Not Found</code> error.</p></td>
</tr>
<tr class="even">
<td><code>projectId</code></td>
<td><p><code>string</code></p>
<p>Output only. The ID of the project that owns the service account.</p></td>
</tr>
<tr class="odd">
<td><code>uniqueId</code></td>
<td><p><code>string</code></p>
<p>Output only. The unique, stable numeric ID for the service account.</p>
<p>Each service account retains its unique ID even if you delete the service account. For example, if you delete a service account, then create a new service account with the same name, the new service account has a different unique ID than the deleted service account.</p></td>
</tr>
<tr class="even">
<td><code>email</code></td>
<td><p><code>string</code></p>
<p>Output only. The email address of the service account.</p></td>
</tr>
<tr class="odd">
<td><code>displayName</code></td>
<td><p><code>string</code></p>
<p>Optional. A user-specified, human-readable name for the service account. The maximum length is 100 UTF-8 bytes.</p></td>
</tr>
<tr class="even">
<td><code>etag </code><strong><code>(deprecated)</code></strong></td>
<td><p><code>string ( </code><a href="https://developers.google.com/discovery/v1/type-format"><code>bytes</code></a><code> format)</code></p>
<blockquote>
<p>This item is deprecated!</p>
</blockquote>
<p>Deprecated. Do not use.</p>
<p>A base64-encoded string.</p></td>
</tr>
<tr class="odd">
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>Optional. A user-specified, human-readable description of the service account. The maximum length is 256 UTF-8 bytes.</p></td>
</tr>
<tr class="even">
<td><code>oauth2ClientId</code></td>
<td><p><code>string</code></p>
<p>Output only. The OAuth 2.0 client ID for the service account.</p></td>
</tr>
<tr class="odd">
<td><code>disabled</code></td>
<td><p><code>boolean</code></p>
<p>Output only. Whether the service account is disabled.</p></td>
</tr>
</tbody>
</table>

| Methods                                                                                                                      |                                                                                                                                                                                                                                                                                                                          |
|------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/create)                         | Creates a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .                                                                                                                                                                                         |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/delete)                         | Deletes a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .                                                                                                                                                                                         |
| [`disable`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/disable)                       | Disables a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) immediately.                                                                                                                                                                             |
| [`enable`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/enable)                         | Enables a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) that was disabled by [`DisableServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/disable#google.iam.admin.v1.IAM.DisableServiceAccount) . |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/get)                               | Gets a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .                                                                                                                                                                                            |
| [`getIamPolicy`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/getIamPolicy)             | Gets the IAM policy that is attached to a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .                                                                                                                                                         |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/list)                             | Lists every [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) that belongs to a specific project.                                                                                                                                                     |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/patch)                           | Patches a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .                                                                                                                                                                                         |
| [`setIamPolicy`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/setIamPolicy)             | Sets the IAM policy that is attached to a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .                                                                                                                                                         |
| [`signBlob`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signBlob)` (deprecated)`      | Signs a blob using the system-managed private key for a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .                                                                                                                                           |
| [`signJwt`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/signJwt)` (deprecated)`        | Signs a JSON Web Token (JWT) using the system-managed private key for a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .                                                                                                                           |
| [`testIamPermissions`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/testIamPermissions) | Tests whether the caller has the specified permissions on a [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .                                                                                                                                       |
| [`undelete`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/undelete)                     | Restores a deleted [`ServiceAccount`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts#ServiceAccount) .                                                                                                                                                                                |
| [`update`](https://docs.cloud.google.com/iam/docs/reference/rest/v1/projects.serviceAccounts/update)                         | **Note:** We are in the process of deprecating this method.                                                                                                                                                                                                                                                              |
