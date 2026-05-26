---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon
title: Proxmity Beacon roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Proxmity Beacon. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Proxmity Beacon roles

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
<td><h4 id="proximitybeacon.admin" class="role-title add-link" data-text="Proximitybeacon Admin" tabindex="-1">Proximitybeacon Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p>Admin role for proximitybeacon</p></td>
<td><p><code dir="ltr" translate="no">proximitybeacon.*</code></p>
<ul>
<li><code dir="ltr" translate="no">proximitybeacon.  attachments.  create</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  attachments.  delete</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  attachments.  get</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  attachments.  list</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.beacons.attach</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.beacons.create</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.beacons.get</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  beacons.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.beacons.list</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  beacons.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.beacons.update</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  namespaces.  create</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  namespaces.  delete</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.namespaces.get</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  namespaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  namespaces.  list</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  namespaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  namespaces.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="proximitybeacon.editor" class="role-title add-link" data-text="Proximitybeacon Editor" tabindex="-1">Proximitybeacon Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p>Editor role for proximitybeacon</p></td>
<td><p><code dir="ltr" translate="no">proximitybeacon.attachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">proximitybeacon.  attachments.  create</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  attachments.  delete</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  attachments.  get</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  attachments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.attach</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.create</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.get</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.list</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.update</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  namespaces.  create</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  namespaces.  delete</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.namespaces.get</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  namespaces.  list</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  namespaces.  update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="proximitybeacon.viewer" class="role-title add-link" data-text="Proximitybeacon Viewer" tabindex="-1">Proximitybeacon Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  proximitybeacon.viewer</code> )</p>
<p>Viewer role for proximitybeacon</p></td>
<td><p><code dir="ltr" translate="no">proximitybeacon.  attachments.  get</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.get</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.list</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.namespaces.get</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  namespaces.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="proximitybeacon.attachmentEditor" class="role-title add-link" data-text="Beacon Attachment Editor" tabindex="-1">Beacon Attachment Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  proximitybeacon.attachmentEditor</code> )</p>
<p>Can create and delete attachments; can list and get a project's beacons; can list a project's namespaces.</p></td>
<td><p><code dir="ltr" translate="no">proximitybeacon.attachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">proximitybeacon.  attachments.  create</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  attachments.  delete</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  attachments.  get</code></li>
<li><code dir="ltr" translate="no">proximitybeacon.  attachments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.get</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.list</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  namespaces.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="proximitybeacon.attachmentPublisher" class="role-title add-link" data-text="Beacon Attachment Publisher" tabindex="-1">Beacon Attachment Publisher</h4>
<p>( <code dir="ltr" translate="no">roles/  proximitybeacon.attachmentPublisher</code> )</p>
<p>Grants necessary permissions to use beacons to create attachments in namespaces not owned by this project.</p></td>
<td><p><code dir="ltr" translate="no">proximitybeacon.beacons.attach</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.get</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="proximitybeacon.attachmentViewer" class="role-title add-link" data-text="Beacon Attachment Viewer" tabindex="-1">Beacon Attachment Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  proximitybeacon.attachmentViewer</code> )</p>
<p>Can view all attachments under a namespace; no beacon or namespace permissions.</p></td>
<td><p><code dir="ltr" translate="no">proximitybeacon.  attachments.  get</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="proximitybeacon.beaconEditor" class="role-title add-link" data-text="Beacon Editor" tabindex="-1">Beacon Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  proximitybeacon.beaconEditor</code> )</p>
<p>Necessary access to register, modify, and view beacons; no attachment or namespace permissions.</p></td>
<td><p><code dir="ltr" translate="no">proximitybeacon.beacons.create</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.get</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.list</code></p>
<p><code dir="ltr" translate="no">proximitybeacon.beacons.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Proxmity Beacon permissions

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
<td><h4 id="proximitybeacon.attachments.create" class="permission-name add-link" data-text="proximitybeacon.attachments.create" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.  attachments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentEditor">Beacon Attachment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="proximitybeacon.attachments.delete" class="permission-name add-link" data-text="proximitybeacon.attachments.delete" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.  attachments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentEditor">Beacon Attachment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="proximitybeacon.attachments.get" class="permission-name add-link" data-text="proximitybeacon.attachments.get" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.  attachments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.viewer">Proximitybeacon Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentEditor">Beacon Attachment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentViewer">Beacon Attachment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="proximitybeacon.attachments.list" class="permission-name add-link" data-text="proximitybeacon.attachments.list" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.  attachments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.viewer">Proximitybeacon Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentEditor">Beacon Attachment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentViewer">Beacon Attachment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="proximitybeacon.beacons.attach" class="permission-name add-link" data-text="proximitybeacon.beacons.attach" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.beacons.attach</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentPublisher">Beacon Attachment Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentPublisher</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="proximitybeacon.beacons.create" class="permission-name add-link" data-text="proximitybeacon.beacons.create" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.beacons.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.beaconEditor">Beacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.beaconEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="proximitybeacon.beacons.get" class="permission-name add-link" data-text="proximitybeacon.beacons.get" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.beacons.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.viewer">Proximitybeacon Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentEditor">Beacon Attachment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentPublisher">Beacon Attachment Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.beaconEditor">Beacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.beaconEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="proximitybeacon.beacons.getIamPolicy" class="permission-name add-link" data-text="proximitybeacon.beacons.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.  beacons.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="proximitybeacon.beacons.list" class="permission-name add-link" data-text="proximitybeacon.beacons.list" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.beacons.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.viewer">Proximitybeacon Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentEditor">Beacon Attachment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentPublisher">Beacon Attachment Publisher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.beaconEditor">Beacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.beaconEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="proximitybeacon.beacons.setIamPolicy" class="permission-name add-link" data-text="proximitybeacon.beacons.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.  beacons.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="proximitybeacon.beacons.update" class="permission-name add-link" data-text="proximitybeacon.beacons.update" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.beacons.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.beaconEditor">Beacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.beaconEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="proximitybeacon.namespaces.create" class="permission-name add-link" data-text="proximitybeacon.namespaces.create" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.  namespaces.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="proximitybeacon.namespaces.delete" class="permission-name add-link" data-text="proximitybeacon.namespaces.delete" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.  namespaces.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="proximitybeacon.namespaces.get" class="permission-name add-link" data-text="proximitybeacon.namespaces.get" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.namespaces.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.viewer">Proximitybeacon Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="proximitybeacon.namespaces.getIamPolicy" class="permission-name add-link" data-text="proximitybeacon.namespaces.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.  namespaces.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="proximitybeacon.namespaces.list" class="permission-name add-link" data-text="proximitybeacon.namespaces.list" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.  namespaces.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.viewer">Proximitybeacon Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentEditor">Beacon Attachment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.attachmentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="proximitybeacon.namespaces.setIamPolicy" class="permission-name add-link" data-text="proximitybeacon.namespaces.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.  namespaces.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="proximitybeacon.namespaces.update" class="permission-name add-link" data-text="proximitybeacon.namespaces.update" tabindex="-1"><code dir="ltr" translate="no">proximitybeacon.  namespaces.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  proximitybeacon.editor</code> )</p></td>
</tr>
</tbody>
</table>
