---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/aiedgeportal
title: AI Edge Portal roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for AI Edge Portal. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## AI Edge Portal roles

AI Edge Portal offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Role</th>
<th>Permissions</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><h4 id="aiedgeportal.serviceAgent" class="role-title add-link" data-text="AI Edge Portal Service Agent" tabindex="-1">AI Edge Portal Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  aiedgeportal.serviceAgent</code> )</p>
<p>Grants AI Edge Portal Service Agent permissions required to read/write data to GCS buckets</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p></td>
</tr>
</tbody>
</table>

## AI Edge Portal permissions

There are no IAM permissions for this service.
