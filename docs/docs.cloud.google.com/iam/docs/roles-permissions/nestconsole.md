---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/nestconsole
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole
title: Nest Console roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Nest Console. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Nest Console roles

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
<td><h4 id="nestconsole.admin" class="role-title add-link" data-text="Nestconsole Admin" tabindex="-1">Nestconsole Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  nestconsole.admin</code> )</p>
<p>Admin role for nestconsole</p></td>
<td><p><code dir="ltr" translate="no">nestconsole.*</code></p>
<ul>
<li><code dir="ltr" translate="no">nestconsole.  smarthomePreviews.  update</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  create</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  delete</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  get</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  update</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  create</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  get</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  submit</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="nestconsole.editor" class="role-title add-link" data-text="Nestconsole Editor" tabindex="-1">Nestconsole Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  nestconsole.editor</code> )</p>
<p>Editor role for nestconsole</p></td>
<td><p><code dir="ltr" translate="no">nestconsole.  smarthomePreviews.  update</code></p>
<p><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  get</code></p>
<p><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  update</code></p>
<p><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  create</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  get</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  submit</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="nestconsole.viewer" class="role-title add-link" data-text="Nestconsole Viewer" tabindex="-1">Nestconsole Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  nestconsole.viewer</code> )</p>
<p>Viewer role for nestconsole</p></td>
<td><p><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  get</code></p>
<p><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="nestconsole.homeDeveloperAdmin" class="role-title add-link" data-text="Google Home Developer Console Admin" tabindex="-1">Google Home Developer Console Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  nestconsole.homeDeveloperAdmin</code> )</p>
<p>Admin access to Google Home Developer Console resources</p></td>
<td><p><code dir="ltr" translate="no">nestconsole.*</code></p>
<ul>
<li><code dir="ltr" translate="no">nestconsole.  smarthomePreviews.  update</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  create</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  delete</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  get</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  update</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  create</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  get</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  submit</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="nestconsole.homeDeveloperEditor" class="role-title add-link" data-text="Google Home Developer Console Editor" tabindex="-1">Google Home Developer Console Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  nestconsole.homeDeveloperEditor</code> )</p>
<p>Read-Write access to Google Home Developer Console resources</p></td>
<td><p><code dir="ltr" translate="no">nestconsole.  smarthomePreviews.  update</code></p>
<p><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  get</code></p>
<p><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  update</code></p>
<p><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  create</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  get</code></li>
<li><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  submit</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="nestconsole.homeDeveloperViewer" class="role-title add-link" data-text="Google Home Developer Console Reader" tabindex="-1">Google Home Developer Console Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  nestconsole.homeDeveloperViewer</code> )</p>
<p>Read-only access to Google Home Developer Console resources</p></td>
<td><p><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  get</code></p>
<p><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Nest Console permissions

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
<td><h4 id="nestconsole.smarthomePreviews.update" class="permission-name add-link" data-text="nestconsole.smarthomePreviews.update" tabindex="-1"><code dir="ltr" translate="no">nestconsole.  smarthomePreviews.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin">Nestconsole Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor">Nestconsole Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin">Google Home Developer Console Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor">Google Home Developer Console Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="nestconsole.smarthomeProjects.create" class="permission-name add-link" data-text="nestconsole.smarthomeProjects.create" tabindex="-1"><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin">Nestconsole Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin">Google Home Developer Console Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="nestconsole.smarthomeProjects.delete" class="permission-name add-link" data-text="nestconsole.smarthomeProjects.delete" tabindex="-1"><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin">Nestconsole Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin">Google Home Developer Console Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="nestconsole.smarthomeProjects.get" class="permission-name add-link" data-text="nestconsole.smarthomeProjects.get" tabindex="-1"><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin">Nestconsole Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor">Nestconsole Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.viewer">Nestconsole Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin">Google Home Developer Console Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor">Google Home Developer Console Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperViewer">Google Home Developer Console Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="nestconsole.smarthomeProjects.update" class="permission-name add-link" data-text="nestconsole.smarthomeProjects.update" tabindex="-1"><code dir="ltr" translate="no">nestconsole.  smarthomeProjects.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin">Nestconsole Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor">Nestconsole Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin">Google Home Developer Console Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor">Google Home Developer Console Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="nestconsole.smarthomeVersions.create" class="permission-name add-link" data-text="nestconsole.smarthomeVersions.create" tabindex="-1"><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin">Nestconsole Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor">Nestconsole Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin">Google Home Developer Console Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor">Google Home Developer Console Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="nestconsole.smarthomeVersions.get" class="permission-name add-link" data-text="nestconsole.smarthomeVersions.get" tabindex="-1"><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin">Nestconsole Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor">Nestconsole Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.viewer">Nestconsole Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin">Google Home Developer Console Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor">Google Home Developer Console Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperViewer">Google Home Developer Console Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="nestconsole.smarthomeVersions.submit" class="permission-name add-link" data-text="nestconsole.smarthomeVersions.submit" tabindex="-1"><code dir="ltr" translate="no">nestconsole.  smarthomeVersions.  submit</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin">Nestconsole Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor">Nestconsole Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin">Google Home Developer Console Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor">Google Home Developer Console Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  nestconsole.homeDeveloperEditor</code> )</p></td>
</tr>
</tbody>
</table>
