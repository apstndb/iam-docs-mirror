---
name: documents/docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/CustomConstraint
uri: https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/CustomConstraint
title: CustomConstraint
description: A suite of tools to help you understand and manage your policies to proactively improve your security configuration.
data_source: docs.cloud.google.com
---

- [JSON representation](https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/CustomConstraint#SCHEMA_REPRESENTATION)

A custom constraint defined by customers which can *only* be applied to the given resource types and organization.

By creating a custom constraint, customers can apply policies of this custom constraint. *Creating a custom constraint itself does NOT apply any policy enforcement* .

**JSON representation**

```
{
  "name": string,
  "resourceTypes": [
    string
  ],
  "methodTypes": [
    enum (MethodType)
  ],
  "condition": string,
  "actionType": enum (ActionType),
  "displayName": string,
  "description": string,
  "updateTime": string
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
<p>Immutable. Name of the constraint. This is unique within the organization. Format of the name should be</p>
<ul>
<li><code>organizations/{organizationId}/customConstraints/{custom_constraint_id}</code></li>
</ul>
<p>Example: <code>organizations/123/customConstraints/custom.createOnlyE2TypeVms</code></p>
<p>The max length is 70 characters and the minimum length is 1. Note that the prefix <code>organizations/{organizationId}/customConstraints/</code> is not counted.</p></td>
</tr>
<tr class="even">
<td><code>resourceTypes[]</code></td>
<td><p><code>string</code></p>
<p>Immutable. The resource instance type on which this policy applies. Format will be of the form : <code>&lt;service name&gt;/&lt;type&gt;</code> Example:</p>
<ul>
<li><code>compute.googleapis.com/Instance</code> .</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>methodTypes[]</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/MethodType"><code>MethodType</code></a><code> )</code></p>
<p>All the operations being applied for this constraint.</p></td>
</tr>
<tr class="even">
<td><code>condition</code></td>
<td><p><code>string</code></p>
<p>A Common Expression Language (CEL) condition which is used in the evaluation of the constraint. For example: <code>resource.instanceName.matches("(production|test)_(.+_)?[\d]+")</code> or, <code>resource.management.auto_upgrade == true</code></p>
<p>The max length of the condition is 1000 characters.</p></td>
</tr>
<tr class="odd">
<td><code>actionType</code></td>
<td><p><code>enum ( </code><a href="https://docs.cloud.google.com/policy-intelligence/docs/reference/policysimulator/rest/Shared.Types/ActionType"><code>ActionType</code></a><code> )</code></p>
<p>Allow or deny type.</p></td>
</tr>
<tr class="even">
<td><code>displayName</code></td>
<td><p><code>string</code></p>
<p>One line display name for the UI. The max length of the displayName is 200 characters.</p></td>
</tr>
<tr class="odd">
<td><code>description</code></td>
<td><p><code>string</code></p>
<p>Detailed information about this custom policy constraint. The max length of the description is 2000 characters.</p></td>
</tr>
<tr class="even">
<td><code>updateTime</code></td>
<td><p><code>string ( </code><a href="https://protobuf.dev/reference/protobuf/google.protobuf/#timestamp"><code>Timestamp</code></a><code> format)</code></p>
<p>Output only. The last time this custom constraint was updated. This represents the last time that the <code>customConstraints.create</code> or <code>customConstraints.patch</code> methods were called.</p>
<p>Uses RFC 3339, where generated output will always be Z-normalized and use 0, 3, 6 or 9 fractional digits. Offsets other than "Z" are also accepted. Examples: <code>"2014-10-02T15:01:23Z"</code> , <code>"2014-10-02T15:01:23.045123456Z"</code> or <code>"2014-10-02T15:01:23+05:30"</code> .</p></td>
</tr>
</tbody>
</table>
