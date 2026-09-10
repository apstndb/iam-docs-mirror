---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/essentialcontacts
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/essentialcontacts
title: Essential Contacts roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Essential Contacts. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Essential Contacts roles

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
<td><h4 id="essentialcontacts.admin" class="role-title add-link" data-text="Essential Contacts Admin" tabindex="-1">Essential Contacts Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  essentialcontacts.admin</code> )</p>
<p>Full access to all essential contacts</p></td>
<td><p><code dir="ltr" translate="no">essentialcontacts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  create</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  delete</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.contacts.get</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  list</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  send</code></li>
<li><code dir="ltr" translate="no">essentialcontacts.  contacts.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="essentialcontacts.viewer" class="role-title add-link" data-text="Essential Contacts Viewer" tabindex="-1">Essential Contacts Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  essentialcontacts.viewer</code> )</p>
<p>Viewer for all essential contacts</p></td>
<td><p><code dir="ltr" translate="no">essentialcontacts.contacts.get</code></p>
<p><code dir="ltr" translate="no">essentialcontacts.  contacts.  list</code></p></td>
</tr>
</tbody>
</table>

## Essential Contacts permissions

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
<td><h4 id="essentialcontacts.contacts.create" class="permission-name add-link" data-text="essentialcontacts.contacts.create" tabindex="-1"><code dir="ltr" translate="no">essentialcontacts.  contacts.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/essentialcontacts#essentialcontacts.admin">Essential Contacts Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  essentialcontacts.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="essentialcontacts.contacts.delete" class="permission-name add-link" data-text="essentialcontacts.contacts.delete" tabindex="-1"><code dir="ltr" translate="no">essentialcontacts.  contacts.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/essentialcontacts#essentialcontacts.admin">Essential Contacts Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  essentialcontacts.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="essentialcontacts.contacts.get" class="permission-name add-link" data-text="essentialcontacts.contacts.get" tabindex="-1"><code dir="ltr" translate="no">essentialcontacts.contacts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/essentialcontacts#essentialcontacts.admin">Essential Contacts Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  essentialcontacts.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/essentialcontacts#essentialcontacts.viewer">Essential Contacts Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  essentialcontacts.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="essentialcontacts.contacts.list" class="permission-name add-link" data-text="essentialcontacts.contacts.list" tabindex="-1"><code dir="ltr" translate="no">essentialcontacts.  contacts.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/essentialcontacts#essentialcontacts.admin">Essential Contacts Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  essentialcontacts.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/essentialcontacts#essentialcontacts.viewer">Essential Contacts Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  essentialcontacts.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="essentialcontacts.contacts.send" class="permission-name add-link" data-text="essentialcontacts.contacts.send" tabindex="-1"><code dir="ltr" translate="no">essentialcontacts.  contacts.  send</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/essentialcontacts#essentialcontacts.admin">Essential Contacts Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  essentialcontacts.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="essentialcontacts.contacts.update" class="permission-name add-link" data-text="essentialcontacts.contacts.update" tabindex="-1"><code dir="ltr" translate="no">essentialcontacts.  contacts.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/essentialcontacts#essentialcontacts.admin">Essential Contacts Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  essentialcontacts.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.organizationAdmin</code> )</p></td>
</tr>
</tbody>
</table>
