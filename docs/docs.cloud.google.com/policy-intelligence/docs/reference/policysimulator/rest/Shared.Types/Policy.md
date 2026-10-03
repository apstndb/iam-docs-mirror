---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Policy
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Policy
title: Policy
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/Policy#SCHEMA_REPRESENTATION)

Defines an organization policy which is used to specify constraints for configurations of Google Cloud resources.

**JSON representation**

```
{
  "name": string,
  "spec": {
    object (PolicySpec)
  },
  "alternate": {
    object (AlternatePolicySpec)
  },
  "dryRunSpec": {
    object (PolicySpec)
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
<p>Immutable. The resource name of the policy. Must be one of the following forms, where <code>constraint_name</code> is the name of the constraint which this policy configures:</p>
<ul>
<li><code>projects/{projectNumber}/policies/{constraint_name}</code></li>
<li><code>folders/{folderId}/policies/{constraint_name}</code></li>
<li><code>organizations/{organizationId}/policies/{constraint_name}</code></li>
</ul>
<p>For example, <code>projects/123/policies/compute.disableSerialPortAccess</code> .</p>
<p>Note: <code>projects/{projectId}/policies/{constraint_name}</code> is also an acceptable name for API requests, but responses will return the name using the equivalent project number.</p></td>
</tr>
<tr class="even">
<td><code>spec</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/PolicySpec"><code>PolicySpec</code></a><code> )</code></p>
<p>Basic information about the organization policy.</p></td>
</tr>
<tr class="odd">
<td><code>alternate </code><strong><code>(deprecated)</code></strong></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/AlternatePolicySpec"><code>AlternatePolicySpec</code></a><code> )</code></p>
<blockquote>
<p>This item is deprecated!</p>
</blockquote>
<p>Deprecated.</p></td>
</tr>
<tr class="even">
<td><code>dryRunSpec</code></td>
<td><p><code>object ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/PolicySpec"><code>PolicySpec</code></a><code> )</code></p>
<p>Dry-run policy. Audit-only policy, can be used to monitor how the policy would have impacted the existing and future resources if it's enforced.</p></td>
</tr>
<tr class="odd">
<td><code>etag</code></td>
<td><p><code>string</code></p>
<p>Optional. An opaque tag indicating the current state of the policy, used for concurrency control. This 'etag' is computed by the server based on the value of other fields, and may be sent on update and delete requests to ensure the client has an up-to-date value before proceeding.</p></td>
</tr>
</tbody>
</table>
