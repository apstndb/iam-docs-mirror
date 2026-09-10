---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect
title: Navigation Connect roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Navigation Connect. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Navigation Connect roles

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
<td><h4 id="navigationconnect.admin" class="role-title add-link" data-text="Navigation Connect Admin Beta" tabindex="-1">Navigation Connect Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  navigationconnect.admin</code> )</p>
<p>Full access to Navigation Connect resources.</p></td>
<td><p><code dir="ltr" translate="no">navigationconnect.*</code></p>
<ul>
<li><code dir="ltr" translate="no">navigationconnect.trips.cancel</code></li>
<li><code dir="ltr" translate="no">navigationconnect.trips.create</code></li>
<li><code dir="ltr" translate="no">navigationconnect.trips.get</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="navigationconnect.viewer" class="role-title add-link" data-text="Navigation Connect Viewer Beta" tabindex="-1">Navigation Connect Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  navigationconnect.viewer</code> )</p>
<p>Read-only access to Navigation Connect resources.</p></td>
<td><p><code dir="ltr" translate="no">navigationconnect.trips.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Navigation Connect permissions

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
<td><h4 id="navigationconnect.trips.cancel" class="permission-name add-link" data-text="navigationconnect.trips.cancel" tabindex="-1"><code dir="ltr" translate="no">navigationconnect.trips.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect#navigationconnect.admin">Navigation Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  navigationconnect.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="navigationconnect.trips.create" class="permission-name add-link" data-text="navigationconnect.trips.create" tabindex="-1"><code dir="ltr" translate="no">navigationconnect.trips.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect#navigationconnect.admin">Navigation Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  navigationconnect.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="navigationconnect.trips.get" class="permission-name add-link" data-text="navigationconnect.trips.get" tabindex="-1"><code dir="ltr" translate="no">navigationconnect.trips.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect#navigationconnect.admin">Navigation Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  navigationconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect#navigationconnect.viewer">Navigation Connect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  navigationconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
