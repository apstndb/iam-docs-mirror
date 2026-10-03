---
name: documents/docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies
uri: https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies
title: 'REST Resource: organizations.locations.accessPolicies'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: AccessPolicy](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies#AccessPolicy)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies#AccessPolicy.SCHEMA_REPRESENTATION)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies#METHODS_SUMMARY)

## Resource: AccessPolicy

An IAM access policy resource.

**JSON representation**

```
{
  "name": string,
  "uid": string,
  "etag": string,
  "displayName": string,
  "annotations": {
    string: string,
    ...
  },
  "createTime": string,
  "updateTime": string,
  "details": {
    object (AccessPolicyDetails)
  }
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
<p>Identifier. The resource name of the access policy.</p>
<p>The following formats are supported:</p>
<ul>
<li><code>projects/{projectId}/locations/{location}/accessPolicies/{policyId}</code></li>
<li><code>projects/{projectNumber}/locations/{location}/accessPolicies/{policyId}</code></li>
<li><code>folders/{folderId}/locations/{location}/accessPolicies/{policyId}</code></li>
<li><code>organizations/{organizationId}/locations/{location}/accessPolicies/{policyId}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>uid</code></td>
<td><p><code>string</code></p>
<p>Output only. The globally unique ID of the access policy.</p></td>
</tr>
<tr class="odd">
<td><code>etag</code></td>
<td><p><code>string</code></p>
<p>Optional. The etag for the access policy. If this is provided on update, it must match the server's etag.</p></td>
</tr>
<tr class="even">
<td><code>displayName</code></td>
<td><p><code>string</code></p>
<p>Optional. The description of the access policy. Must be less than or equal to 63 characters.</p></td>
</tr>
<tr class="odd">
<td><code>annotations</code></td>
<td><p><code>map (key: string, value: string)</code></p>
<p>Optional. User defined annotations. See <a href="https://google.aip.dev/148#annotations">https://google.aip.dev/148#annotations</a> for more details such as format and size limitations</p>
<p>An object containing a list of <code>"key": value</code> pairs. Example: <code>{ "name": "wrench", "mass": "1.3kg", "count": "3" }</code> .</p></td>
</tr>
<tr class="even">
<td><code>createTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The time when the access policy was created.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="odd">
<td><code>updateTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The time when the access policy was most recently updated.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="even">
<td><code>details</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/folders.locations.accessPolicies#AccessPolicy.AccessPolicyDetails"><code>AccessPolicyDetails</code></a><code> )</code></p>
<p>Optional. The details for the access policy.</p></td>
</tr>
</tbody>
</table>

| Methods                                                                                                                                            |                                                                                                                       |
|----------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/create)                             | Creates an access policy, and returns a long running operation.                                                       |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/delete)                             | Deletes an access policy.                                                                                             |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/get)                                   | Gets an access policy.                                                                                                |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/list)                                 | Lists access policies.                                                                                                |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/patch)                               | Updates an access policy.                                                                                             |
| [`searchPolicyBindings`](https://docs.cloud.google.com/iam/docs/reference/rest/v3beta/organizations.locations.accessPolicies/searchPolicyBindings) | Returns all policy bindings that bind a specific policy if a user has searchPolicyBindings permission on that policy. |
