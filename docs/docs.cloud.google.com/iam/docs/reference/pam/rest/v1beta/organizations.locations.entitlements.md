---
name: documents/docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements
uri: https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements
title: 'REST Resource: organizations.locations.entitlements'
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

- [Resource: Entitlement](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements#Entitlement)
  - [JSON representation](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements#Entitlement.SCHEMA_REPRESENTATION)
- [Methods](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements#METHODS_SUMMARY)

## Resource: Entitlement

An entitlement defines the eligibility of a set of users to obtain predefined access for some time possibly after going through an approval workflow.

**JSON representation**

```
{
  "name": string,
  "createTime": string,
  "updateTime": string,
  "eligibleUsers": [
    {
      object (AccessControlEntry)
    }
  ],
  "approvalWorkflow": {
    object (ApprovalWorkflow)
  },
  "privilegedAccess": {
    object (PrivilegedAccess)
  },
  "maxRequestDuration": string,
  "state": enum (State),
  "requesterJustificationConfig": {
    object (RequesterJustificationConfig)
  },
  "additionalNotificationTargets": {
    object (AdditionalNotificationTargets)
  },
  "etag": string
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
<p>Identifier. Name of the entitlement. Possible formats:</p>
<ul>
<li><code>organizations/{organization-number}/locations/{region}/entitlements/{entitlement-id}</code></li>
<li><code>folders/{folder-number}/locations/{region}/entitlements/{entitlement-id}</code></li>
<li><code>projects/{project-id|project-number}/locations/{region}/entitlements/{entitlement-id}</code></li>
</ul></td>
</tr>
<tr class="even">
<td><code>createTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. Create time stamp.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="odd">
<td><code>updateTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. Update time stamp.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
<tr class="even">
<td><code>eligibleUsers[]</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.AccessControlEntry"><code>AccessControlEntry</code></a><code> )</code></p>
<p>Optional. Who can create grants using this entitlement. This list should contain at most one entry.</p></td>
</tr>
<tr class="odd">
<td><code>approvalWorkflow</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.ApprovalWorkflow"><code>ApprovalWorkflow</code></a><code> )</code></p>
<p>Optional. The approvals needed before access are granted to a requester. No approvals are needed if this field is null.</p></td>
</tr>
<tr class="even">
<td><code>privilegedAccess</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/PrivilegedAccess"><code>PrivilegedAccess</code></a><code> )</code></p>
<p>Required. The access granted to a requester on successful approval.</p></td>
</tr>
<tr class="odd">
<td><code>maxRequestDuration</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#duration"><code>Duration</code></a><code> format)</code></p>
<p>Required. The maximum amount of time that access is granted for a request. A requester can ask for a shorter duration but never a longer one. The supported range is between 30 minutes and 168 hours (7 days).</p>
<p>A duration in seconds with up to nine fractional digits, ending with ' <code>s</code> '. Example: <code>"3.5s"</code> .</p></td>
</tr>
<tr class="even">
<td><code>state</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.State"><code>State</code></a><code> )</code></p>
<p>Output only. Current state of this entitlement.</p></td>
</tr>
<tr class="odd">
<td><code>requesterJustificationConfig</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.RequesterJustificationConfig"><code>RequesterJustificationConfig</code></a><code> )</code></p>
<p>Required. The manner in which the requester should provide a justification for requesting access.</p></td>
</tr>
<tr class="even">
<td><code>additionalNotificationTargets</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/folders.locations.entitlements#Entitlement.AdditionalNotificationTargets"><code>AdditionalNotificationTargets</code></a><code> )</code></p>
<p>Optional. Additional email addresses to be notified based on actions taken.</p></td>
</tr>
<tr class="odd">
<td><code>etag</code></td>
<td><p><code>string</code></p>
<p>An <code>etag</code> is used for optimistic concurrency control as a way to prevent simultaneous updates to the same entitlement. An <code>etag</code> is returned in the response to <code>entitlements.get</code> and the caller should put the <code>etag</code> in the request to <code>entitlements.patch</code> so that their change is applied on the same version. If this field is omitted or if there is a mismatch while updating an entitlement, then the server rejects the request.</p></td>
</tr>
</tbody>
</table>

| Methods                                                                                                                  |                                                                                              |
|--------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------|
| [`create`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/create) | Creates a new entitlement in a given project, folder, organization, and in a given location. |
| [`delete`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/delete) | Deletes a single entitlement.                                                                |
| [`get`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/get)       | Gets details of a single entitlement.                                                        |
| [`list`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/list)     | Lists the entitlements in a given project, folder, organization, and in a given location.    |
| [`patch`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/patch)   | Updates the entitlement specified in the request.                                            |
| [`search`](https://docs.cloud.google.com/iam/docs/reference/pam/rest/v1beta/organizations.locations.entitlements/search) | `SearchEntitlements` returns entitlements on which the caller has the specified access.      |
