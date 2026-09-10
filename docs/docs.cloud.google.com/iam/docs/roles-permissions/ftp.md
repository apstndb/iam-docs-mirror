---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/ftp
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/ftp
title: Cloud FTP roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud FTP. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud FTP roles

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
<td><h4 id="ftp.admin" class="role-title add-link" data-text="Cloud FTP Admin" tabindex="-1">Cloud FTP Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  ftp.admin</code> )</p>
<p>Full access to Cloud FTP resources.</p></td>
<td><p><code dir="ltr" translate="no">ftp.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ftp.locations.get</code></li>
<li><code dir="ltr" translate="no">ftp.locations.list</code></li>
<li><code dir="ltr" translate="no">ftp.operations.cancel</code></li>
<li><code dir="ltr" translate="no">ftp.operations.delete</code></li>
<li><code dir="ltr" translate="no">ftp.operations.get</code></li>
<li><code dir="ltr" translate="no">ftp.operations.list</code></li>
<li><code dir="ltr" translate="no">ftp.servers.create</code></li>
<li><code dir="ltr" translate="no">ftp.servers.delete</code></li>
<li><code dir="ltr" translate="no">ftp.servers.get</code></li>
<li><code dir="ltr" translate="no">ftp.servers.list</code></li>
<li><code dir="ltr" translate="no">ftp.servers.start</code></li>
<li><code dir="ltr" translate="no">ftp.servers.stop</code></li>
<li><code dir="ltr" translate="no">ftp.servers.update</code></li>
<li><code dir="ltr" translate="no">ftp.users.create</code></li>
<li><code dir="ltr" translate="no">ftp.users.delete</code></li>
<li><code dir="ltr" translate="no">ftp.users.get</code></li>
<li><code dir="ltr" translate="no">ftp.users.list</code></li>
<li><code dir="ltr" translate="no">ftp.users.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="ftp.viewer" class="role-title add-link" data-text="Cloud FTP Viewer" tabindex="-1">Cloud FTP Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  ftp.viewer</code> )</p>
<p>Readonly access to Cloud FTP resources.</p></td>
<td><p><code dir="ltr" translate="no">ftp.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ftp.locations.get</code></li>
<li><code dir="ltr" translate="no">ftp.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">ftp.operations.get</code></p>
<p><code dir="ltr" translate="no">ftp.operations.list</code></p>
<p><code dir="ltr" translate="no">ftp.servers.get</code></p>
<p><code dir="ltr" translate="no">ftp.servers.list</code></p>
<p><code dir="ltr" translate="no">ftp.users.get</code></p>
<p><code dir="ltr" translate="no">ftp.users.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Cloud FTP permissions

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
<td><h4 id="ftp.locations.get" class="permission-name add-link" data-text="ftp.locations.get" tabindex="-1"><code dir="ltr" translate="no">ftp.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.viewer">Cloud FTP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ftp.locations.list" class="permission-name add-link" data-text="ftp.locations.list" tabindex="-1"><code dir="ltr" translate="no">ftp.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.viewer">Cloud FTP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ftp.operations.cancel" class="permission-name add-link" data-text="ftp.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">ftp.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ftp.operations.delete" class="permission-name add-link" data-text="ftp.operations.delete" tabindex="-1"><code dir="ltr" translate="no">ftp.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ftp.operations.get" class="permission-name add-link" data-text="ftp.operations.get" tabindex="-1"><code dir="ltr" translate="no">ftp.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.viewer">Cloud FTP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ftp.operations.list" class="permission-name add-link" data-text="ftp.operations.list" tabindex="-1"><code dir="ltr" translate="no">ftp.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.viewer">Cloud FTP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ftp.servers.create" class="permission-name add-link" data-text="ftp.servers.create" tabindex="-1"><code dir="ltr" translate="no">ftp.servers.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ftp.servers.delete" class="permission-name add-link" data-text="ftp.servers.delete" tabindex="-1"><code dir="ltr" translate="no">ftp.servers.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ftp.servers.get" class="permission-name add-link" data-text="ftp.servers.get" tabindex="-1"><code dir="ltr" translate="no">ftp.servers.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.viewer">Cloud FTP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ftp.servers.list" class="permission-name add-link" data-text="ftp.servers.list" tabindex="-1"><code dir="ltr" translate="no">ftp.servers.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.viewer">Cloud FTP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ftp.servers.start" class="permission-name add-link" data-text="ftp.servers.start" tabindex="-1"><code dir="ltr" translate="no">ftp.servers.start</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ftp.servers.stop" class="permission-name add-link" data-text="ftp.servers.stop" tabindex="-1"><code dir="ltr" translate="no">ftp.servers.stop</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ftp.servers.update" class="permission-name add-link" data-text="ftp.servers.update" tabindex="-1"><code dir="ltr" translate="no">ftp.servers.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ftp.users.create" class="permission-name add-link" data-text="ftp.users.create" tabindex="-1"><code dir="ltr" translate="no">ftp.users.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ftp.users.delete" class="permission-name add-link" data-text="ftp.users.delete" tabindex="-1"><code dir="ltr" translate="no">ftp.users.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ftp.users.get" class="permission-name add-link" data-text="ftp.users.get" tabindex="-1"><code dir="ltr" translate="no">ftp.users.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.viewer">Cloud FTP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ftp.users.list" class="permission-name add-link" data-text="ftp.users.list" tabindex="-1"><code dir="ltr" translate="no">ftp.users.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.viewer">Cloud FTP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ftp.users.update" class="permission-name add-link" data-text="ftp.users.update" tabindex="-1"><code dir="ltr" translate="no">ftp.users.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ftp.admin</code> )</p></td>
</tr>
</tbody>
</table>
