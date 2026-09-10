---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement
title: Android Management roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Android Management. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Android Management roles

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
<td><h4 id="androidmanagement.admin" class="role-title add-link" data-text="Androidmanagement Admin" tabindex="-1">Androidmanagement Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  androidmanagement.admin</code> )</p>
<p>Admin role for androidmanagement</p></td>
<td><p><code dir="ltr" translate="no">androidmanagement.  enterprises.  manage</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="androidmanagement.user" class="role-title add-link" data-text="Android Management User" tabindex="-1">Android Management User</h4>
<p>( <code dir="ltr" translate="no">roles/  androidmanagement.user</code> )</p>
<p>Full access to manage devices.</p></td>
<td><p><code dir="ltr" translate="no">androidmanagement.  enterprises.  manage</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Android Management permissions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Permission</th>
<th>Included in roles</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><h4 id="androidmanagement.enterprises.manage" class="permission-name add-link" data-text="androidmanagement.enterprises.manage" tabindex="-1"><code dir="ltr" translate="no">androidmanagement.  enterprises.  manage</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.admin">Androidmanagement Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  androidmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.user">Android Management User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  androidmanagement.user</code> )</p></td>
</tr>
</tbody>
</table>
