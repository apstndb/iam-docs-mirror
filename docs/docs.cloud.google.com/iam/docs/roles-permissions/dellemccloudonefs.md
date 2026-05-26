---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs
title: Dell EMC Cloud OneFS roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Dell EMC Cloud OneFS. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Dell EMC Cloud OneFS roles

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
<td><h4 id="dellemccloudonefs.admin" class="role-title add-link" data-text="Dell EMC Cloud OneFS Admin Beta" tabindex="-1">Dell EMC Cloud OneFS Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p>
<p>This role is managed by Dell EMC, not Google.</p></td>
<td><p><code dir="ltr" translate="no">cloudonefs.isiloncloud.com/*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  create</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  delete</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  get</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  list</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  update</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  updateAdvancedSettings</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  create</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  delete</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  get</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  list</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dellemccloudonefs.viewer" class="role-title add-link" data-text="Dell EMC Cloud OneFS Viewer Beta" tabindex="-1">Dell EMC Cloud OneFS Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  dellemccloudonefs.viewer</code> )</p>
<p>This role is managed by Dell EMC, not Google.</p></td>
<td><p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  get</code></p>
<p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  list</code></p>
<p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  get</code></p>
<p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dellemccloudonefs.user" class="role-title add-link" data-text="Dell EMC Cloud OneFS User Beta" tabindex="-1">Dell EMC Cloud OneFS User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  dellemccloudonefs.user</code> )</p>
<p>This role is managed by Dell EMC, not Google.</p></td>
<td><p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  create</code></p>
<p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  delete</code></p>
<p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  get</code></p>
<p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  list</code></p>
<p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  update</code></p>
<p><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  create</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  delete</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  get</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  list</code></li>
<li><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Dell EMC Cloud OneFS permissions

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
<td><h4 id="cloudonefs.isiloncloud.com_clusters.create" class="permission-name add-link" data-text="cloudonefs.isiloncloud.com/clusters.create" tabindex="-1"><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudonefs.isiloncloud.com_clusters.delete" class="permission-name add-link" data-text="cloudonefs.isiloncloud.com/clusters.delete" tabindex="-1"><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudonefs.isiloncloud.com_clusters.get" class="permission-name add-link" data-text="cloudonefs.isiloncloud.com/clusters.get" tabindex="-1"><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.viewer">Dell EMC Cloud OneFS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudonefs.isiloncloud.com_clusters.list" class="permission-name add-link" data-text="cloudonefs.isiloncloud.com/clusters.list" tabindex="-1"><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.viewer">Dell EMC Cloud OneFS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudonefs.isiloncloud.com_clusters.update" class="permission-name add-link" data-text="cloudonefs.isiloncloud.com/clusters.update" tabindex="-1"><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudonefs.isiloncloud.com_clusters.updateAdvancedSettings" class="permission-name add-link" data-text="cloudonefs.isiloncloud.com/clusters.updateAdvancedSettings" tabindex="-1"><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/clusters.  updateAdvancedSettings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudonefs.isiloncloud.com_fileshares.create" class="permission-name add-link" data-text="cloudonefs.isiloncloud.com/fileshares.create" tabindex="-1"><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudonefs.isiloncloud.com_fileshares.delete" class="permission-name add-link" data-text="cloudonefs.isiloncloud.com/fileshares.delete" tabindex="-1"><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudonefs.isiloncloud.com_fileshares.get" class="permission-name add-link" data-text="cloudonefs.isiloncloud.com/fileshares.get" tabindex="-1"><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.viewer">Dell EMC Cloud OneFS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudonefs.isiloncloud.com_fileshares.list" class="permission-name add-link" data-text="cloudonefs.isiloncloud.com/fileshares.list" tabindex="-1"><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.viewer">Dell EMC Cloud OneFS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudonefs.isiloncloud.com_fileshares.update" class="permission-name add-link" data-text="cloudonefs.isiloncloud.com/fileshares.update" tabindex="-1"><code dir="ltr" translate="no">cloudonefs.isiloncloud.  com/fileshares.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dellemccloudonefs.user</code> )</p></td>
</tr>
</tbody>
</table>
