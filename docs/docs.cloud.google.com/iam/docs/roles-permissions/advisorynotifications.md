---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications
title: Advisory Notifications roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Advisory Notifications. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Advisory Notifications roles

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
<td><h4 id="advisorynotifications.admin" class="role-title add-link" data-text="Advisory Notifications Admin" tabindex="-1">Advisory Notifications Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  advisorynotifications.admin</code> )</p>
<p>Grants write access to settings in Advisory Notifications</p></td>
<td><p><code dir="ltr" translate="no">advisorynotifications.*</code></p>
<ul>
<li><code dir="ltr" translate="no">advisorynotifications.  notifications.  get</code></li>
<li><code dir="ltr" translate="no">advisorynotifications.  notifications.  list</code></li>
<li><code dir="ltr" translate="no">advisorynotifications.  settings.  get</code></li>
<li><code dir="ltr" translate="no">advisorynotifications.  settings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="advisorynotifications.viewer" class="role-title add-link" data-text="Advisory Notifications Viewer" tabindex="-1">Advisory Notifications Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  advisorynotifications.viewer</code> )</p>
<p>Grants view access in Advisory Notifications</p></td>
<td><p><code dir="ltr" translate="no">advisorynotifications.  notifications.*</code></p>
<ul>
<li><code dir="ltr" translate="no">advisorynotifications.  notifications.  get</code></li>
<li><code dir="ltr" translate="no">advisorynotifications.  notifications.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">advisorynotifications.  settings.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
</tbody>
</table>

## Advisory Notifications permissions

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
<td><h4 id="advisorynotifications.notifications.get" class="permission-name add-link" data-text="advisorynotifications.notifications.get" tabindex="-1"><code dir="ltr" translate="no">advisorynotifications.  notifications.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.admin">Advisory Notifications Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  advisorynotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.viewer">Advisory Notifications Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  advisorynotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="advisorynotifications.notifications.list" class="permission-name add-link" data-text="advisorynotifications.notifications.list" tabindex="-1"><code dir="ltr" translate="no">advisorynotifications.  notifications.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.admin">Advisory Notifications Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  advisorynotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.viewer">Advisory Notifications Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  advisorynotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="advisorynotifications.settings.get" class="permission-name add-link" data-text="advisorynotifications.settings.get" tabindex="-1"><code dir="ltr" translate="no">advisorynotifications.  settings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.admin">Advisory Notifications Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  advisorynotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.viewer">Advisory Notifications Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  advisorynotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="advisorynotifications.settings.update" class="permission-name add-link" data-text="advisorynotifications.settings.update" tabindex="-1"><code dir="ltr" translate="no">advisorynotifications.  settings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.admin">Advisory Notifications Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  advisorynotifications.admin</code> )</p></td>
</tr>
</tbody>
</table>
