---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/datastudio
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio
title: Data Studio roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Data Studio. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Data Studio roles

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
<td><h4 id="datastudio.admin" class="role-title add-link" data-text="Data Studio Admin Beta" tabindex="-1">Data Studio Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p>Data Studio Admin</p></td>
<td><p><code dir="ltr" translate="no">datastudio.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastudio.datasources.delete</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.get</code></li>
<li><code dir="ltr" translate="no">datastudio.  datasources.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.move</code></li>
<li><code dir="ltr" translate="no">datastudio.  datasources.  restoreTrash</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.search</code></li>
<li><code dir="ltr" translate="no">datastudio.  datasources.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.  datasources.  settingsShare</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.share</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.trash</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.update</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.delete</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.get</code></li>
<li><code dir="ltr" translate="no">datastudio.  reports.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.move</code></li>
<li><code dir="ltr" translate="no">datastudio.  reports.  restoreTrash</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.search</code></li>
<li><code dir="ltr" translate="no">datastudio.  reports.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.  reports.  settingsShare</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.share</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.trash</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.update</code></li>
<li><code dir="ltr" translate="no">datastudio.  workspaces.  createUnder</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.delete</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.get</code></li>
<li><code dir="ltr" translate="no">datastudio.  workspaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.moveIn</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.moveOut</code></li>
<li><code dir="ltr" translate="no">datastudio.  workspaces.  restoreTrash</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.search</code></li>
<li><code dir="ltr" translate="no">datastudio.  workspaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.trash</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.editor" class="role-title add-link" data-text="Data Studio Asset Editor Beta" tabindex="-1">Data Studio Asset Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datastudio.editor</code> )</p>
<p>Editor of a Data Studio resource</p></td>
<td><p><code dir="ltr" translate="no">datastudio.datasources.get</code></p>
<p><code dir="ltr" translate="no">datastudio.  datasources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.datasources.search</code></p>
<p><code dir="ltr" translate="no">datastudio.datasources.update</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.get</code></p>
<p><code dir="ltr" translate="no">datastudio.  reports.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.search</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.viewer" class="role-title add-link" data-text="Data Studio Asset Viewer Beta" tabindex="-1">Data Studio Asset Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datastudio.viewer</code> )</p>
<p>Viewer of a Data Studio resource</p></td>
<td><p><code dir="ltr" translate="no">datastudio.datasources.get</code></p>
<p><code dir="ltr" translate="no">datastudio.datasources.search</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.get</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.contentManager" class="role-title add-link" data-text="Data Studio Workspace Content Manager Beta" tabindex="-1">Data Studio Workspace Content Manager <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p>Content Manager of a Data Studio resource</p></td>
<td><p><code dir="ltr" translate="no">datastudio.datasources.get</code></p>
<p><code dir="ltr" translate="no">datastudio.  datasources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.datasources.move</code></p>
<p><code dir="ltr" translate="no">datastudio.  datasources.  restoreTrash</code></p>
<p><code dir="ltr" translate="no">datastudio.datasources.search</code></p>
<p><code dir="ltr" translate="no">datastudio.  datasources.  settingsShare</code></p>
<p><code dir="ltr" translate="no">datastudio.datasources.share</code></p>
<p><code dir="ltr" translate="no">datastudio.datasources.trash</code></p>
<p><code dir="ltr" translate="no">datastudio.datasources.update</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.get</code></p>
<p><code dir="ltr" translate="no">datastudio.  reports.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.move</code></p>
<p><code dir="ltr" translate="no">datastudio.  reports.  restoreTrash</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.search</code></p>
<p><code dir="ltr" translate="no">datastudio.  reports.  settingsShare</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.share</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.trash</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.update</code></p>
<p><code dir="ltr" translate="no">datastudio.  workspaces.  createUnder</code></p>
<p><code dir="ltr" translate="no">datastudio.workspaces.get</code></p>
<p><code dir="ltr" translate="no">datastudio.  workspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.workspaces.moveIn</code></p>
<p><code dir="ltr" translate="no">datastudio.workspaces.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.contributor" class="role-title add-link" data-text="Data Studio Workspace Contributor Beta" tabindex="-1">Data Studio Workspace Contributor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p>Contributor of a Data Studio resource</p></td>
<td><p><code dir="ltr" translate="no">datastudio.datasources.get</code></p>
<p><code dir="ltr" translate="no">datastudio.  datasources.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.  datasources.  restoreTrash</code></p>
<p><code dir="ltr" translate="no">datastudio.datasources.search</code></p>
<p><code dir="ltr" translate="no">datastudio.  datasources.  settingsShare</code></p>
<p><code dir="ltr" translate="no">datastudio.datasources.share</code></p>
<p><code dir="ltr" translate="no">datastudio.datasources.update</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.get</code></p>
<p><code dir="ltr" translate="no">datastudio.  reports.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.  reports.  restoreTrash</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.search</code></p>
<p><code dir="ltr" translate="no">datastudio.  reports.  settingsShare</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.share</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.update</code></p>
<p><code dir="ltr" translate="no">datastudio.  workspaces.  createUnder</code></p>
<p><code dir="ltr" translate="no">datastudio.workspaces.get</code></p>
<p><code dir="ltr" translate="no">datastudio.  workspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastudio.workspaces.moveIn</code></p>
<p><code dir="ltr" translate="no">datastudio.workspaces.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.manager" class="role-title add-link" data-text="Data Studio Workspace Manager Beta" tabindex="-1">Data Studio Workspace Manager <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p>Manager of a Data Studio resource</p></td>
<td><p><code dir="ltr" translate="no">datastudio.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastudio.datasources.delete</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.get</code></li>
<li><code dir="ltr" translate="no">datastudio.  datasources.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.move</code></li>
<li><code dir="ltr" translate="no">datastudio.  datasources.  restoreTrash</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.search</code></li>
<li><code dir="ltr" translate="no">datastudio.  datasources.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.  datasources.  settingsShare</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.share</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.trash</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.update</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.delete</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.get</code></li>
<li><code dir="ltr" translate="no">datastudio.  reports.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.move</code></li>
<li><code dir="ltr" translate="no">datastudio.  reports.  restoreTrash</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.search</code></li>
<li><code dir="ltr" translate="no">datastudio.  reports.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.  reports.  settingsShare</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.share</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.trash</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.update</code></li>
<li><code dir="ltr" translate="no">datastudio.  workspaces.  createUnder</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.delete</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.get</code></li>
<li><code dir="ltr" translate="no">datastudio.  workspaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.moveIn</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.moveOut</code></li>
<li><code dir="ltr" translate="no">datastudio.  workspaces.  restoreTrash</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.search</code></li>
<li><code dir="ltr" translate="no">datastudio.  workspaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.trash</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.workspaceViewer" class="role-title add-link" data-text="Data Studio Workspace Viewer Beta" tabindex="-1">Data Studio Workspace Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  datastudio.workspaceViewer</code> )</p>
<p>Viewer of a Data Studio Workspace</p></td>
<td><p><code dir="ltr" translate="no">datastudio.datasources.get</code></p>
<p><code dir="ltr" translate="no">datastudio.datasources.search</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.get</code></p>
<p><code dir="ltr" translate="no">datastudio.reports.search</code></p>
<p><code dir="ltr" translate="no">datastudio.workspaces.get</code></p>
<p><code dir="ltr" translate="no">datastudio.workspaces.search</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="lookerstudio.lookerAdmin" class="role-title add-link" data-text="Looker Admin Beta" tabindex="-1">Looker Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p>
<p>Admin of Looker instance mapping to a Studio subscription</p></td>
<td><p><code dir="ltr" translate="no">datastudio.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastudio.datasources.delete</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.get</code></li>
<li><code dir="ltr" translate="no">datastudio.  datasources.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.move</code></li>
<li><code dir="ltr" translate="no">datastudio.  datasources.  restoreTrash</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.search</code></li>
<li><code dir="ltr" translate="no">datastudio.  datasources.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.  datasources.  settingsShare</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.share</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.trash</code></li>
<li><code dir="ltr" translate="no">datastudio.datasources.update</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.delete</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.get</code></li>
<li><code dir="ltr" translate="no">datastudio.  reports.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.move</code></li>
<li><code dir="ltr" translate="no">datastudio.  reports.  restoreTrash</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.search</code></li>
<li><code dir="ltr" translate="no">datastudio.  reports.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.  reports.  settingsShare</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.share</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.trash</code></li>
<li><code dir="ltr" translate="no">datastudio.reports.update</code></li>
<li><code dir="ltr" translate="no">datastudio.  workspaces.  createUnder</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.delete</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.get</code></li>
<li><code dir="ltr" translate="no">datastudio.  workspaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.moveIn</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.moveOut</code></li>
<li><code dir="ltr" translate="no">datastudio.  workspaces.  restoreTrash</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.search</code></li>
<li><code dir="ltr" translate="no">datastudio.  workspaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.trash</code></li>
<li><code dir="ltr" translate="no">datastudio.workspaces.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="lookerstudio.proManager" class="role-title add-link" data-text="Looker Studio Pro Manager Beta" tabindex="-1">Looker Studio Pro Manager <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  lookerstudio.proManager</code> )</p>
<p>Looker Studio Pro Manager</p></td>
<td><p><code dir="ltr" translate="no">lookerstudio.pro.manage</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  updateLiens</code></p></td>
</tr>
</tbody>
</table>

### Service agent roles

Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="datastudio.serviceAgent" class="role-title add-link" data-text="Data Studio Service Agent" tabindex="-1">Data Studio Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  datastudio.serviceAgent</code> )</p>
<p>Grants Data Studio Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.jobs.create</code></p></td>
</tr>
</tbody>
</table>

## Data Studio permissions

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
<td><h4 id="datastudio.datasources.delete" class="permission-name add-link" data-text="datastudio.datasources.delete" tabindex="-1"><code dir="ltr" translate="no">datastudio.datasources.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.datasources.get" class="permission-name add-link" data-text="datastudio.datasources.get" tabindex="-1"><code dir="ltr" translate="no">datastudio.datasources.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.editor">Data Studio Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.viewer">Data Studio Asset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.workspaceViewer">Data Studio Workspace Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.workspaceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.datasources.getIamPolicy" class="permission-name add-link" data-text="datastudio.datasources.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastudio.  datasources.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.editor">Data Studio Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.datasources.move" class="permission-name add-link" data-text="datastudio.datasources.move" tabindex="-1"><code dir="ltr" translate="no">datastudio.datasources.move</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.datasources.restoreTrash" class="permission-name add-link" data-text="datastudio.datasources.restoreTrash" tabindex="-1"><code dir="ltr" translate="no">datastudio.  datasources.  restoreTrash</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.datasources.search" class="permission-name add-link" data-text="datastudio.datasources.search" tabindex="-1"><code dir="ltr" translate="no">datastudio.datasources.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.editor">Data Studio Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.viewer">Data Studio Asset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.workspaceViewer">Data Studio Workspace Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.workspaceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.datasources.setIamPolicy" class="permission-name add-link" data-text="datastudio.datasources.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastudio.  datasources.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.datasources.settingsShare" class="permission-name add-link" data-text="datastudio.datasources.settingsShare" tabindex="-1"><code dir="ltr" translate="no">datastudio.  datasources.  settingsShare</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.datasources.share" class="permission-name add-link" data-text="datastudio.datasources.share" tabindex="-1"><code dir="ltr" translate="no">datastudio.datasources.share</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.datasources.trash" class="permission-name add-link" data-text="datastudio.datasources.trash" tabindex="-1"><code dir="ltr" translate="no">datastudio.datasources.trash</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.datasources.update" class="permission-name add-link" data-text="datastudio.datasources.update" tabindex="-1"><code dir="ltr" translate="no">datastudio.datasources.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.editor">Data Studio Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.reports.delete" class="permission-name add-link" data-text="datastudio.reports.delete" tabindex="-1"><code dir="ltr" translate="no">datastudio.reports.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.reports.get" class="permission-name add-link" data-text="datastudio.reports.get" tabindex="-1"><code dir="ltr" translate="no">datastudio.reports.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.editor">Data Studio Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.viewer">Data Studio Asset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.workspaceViewer">Data Studio Workspace Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.workspaceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.reports.getIamPolicy" class="permission-name add-link" data-text="datastudio.reports.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastudio.  reports.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.editor">Data Studio Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.reports.move" class="permission-name add-link" data-text="datastudio.reports.move" tabindex="-1"><code dir="ltr" translate="no">datastudio.reports.move</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.reports.restoreTrash" class="permission-name add-link" data-text="datastudio.reports.restoreTrash" tabindex="-1"><code dir="ltr" translate="no">datastudio.  reports.  restoreTrash</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.reports.search" class="permission-name add-link" data-text="datastudio.reports.search" tabindex="-1"><code dir="ltr" translate="no">datastudio.reports.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.editor">Data Studio Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.viewer">Data Studio Asset Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.workspaceViewer">Data Studio Workspace Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.workspaceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.reports.setIamPolicy" class="permission-name add-link" data-text="datastudio.reports.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastudio.  reports.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.reports.settingsShare" class="permission-name add-link" data-text="datastudio.reports.settingsShare" tabindex="-1"><code dir="ltr" translate="no">datastudio.  reports.  settingsShare</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.reports.share" class="permission-name add-link" data-text="datastudio.reports.share" tabindex="-1"><code dir="ltr" translate="no">datastudio.reports.share</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.reports.trash" class="permission-name add-link" data-text="datastudio.reports.trash" tabindex="-1"><code dir="ltr" translate="no">datastudio.reports.trash</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.reports.update" class="permission-name add-link" data-text="datastudio.reports.update" tabindex="-1"><code dir="ltr" translate="no">datastudio.reports.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.editor">Data Studio Asset Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.workspaces.createUnder" class="permission-name add-link" data-text="datastudio.workspaces.createUnder" tabindex="-1"><code dir="ltr" translate="no">datastudio.  workspaces.  createUnder</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.workspaces.delete" class="permission-name add-link" data-text="datastudio.workspaces.delete" tabindex="-1"><code dir="ltr" translate="no">datastudio.workspaces.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.workspaces.get" class="permission-name add-link" data-text="datastudio.workspaces.get" tabindex="-1"><code dir="ltr" translate="no">datastudio.workspaces.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.workspaceViewer">Data Studio Workspace Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.workspaceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.workspaces.getIamPolicy" class="permission-name add-link" data-text="datastudio.workspaces.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastudio.  workspaces.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.workspaces.moveIn" class="permission-name add-link" data-text="datastudio.workspaces.moveIn" tabindex="-1"><code dir="ltr" translate="no">datastudio.workspaces.moveIn</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.workspaces.moveOut" class="permission-name add-link" data-text="datastudio.workspaces.moveOut" tabindex="-1"><code dir="ltr" translate="no">datastudio.workspaces.moveOut</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.workspaces.restoreTrash" class="permission-name add-link" data-text="datastudio.workspaces.restoreTrash" tabindex="-1"><code dir="ltr" translate="no">datastudio.  workspaces.  restoreTrash</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.workspaces.search" class="permission-name add-link" data-text="datastudio.workspaces.search" tabindex="-1"><code dir="ltr" translate="no">datastudio.workspaces.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.workspaceViewer">Data Studio Workspace Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.workspaceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.workspaces.setIamPolicy" class="permission-name add-link" data-text="datastudio.workspaces.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastudio.  workspaces.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastudio.workspaces.trash" class="permission-name add-link" data-text="datastudio.workspaces.trash" tabindex="-1"><code dir="ltr" translate="no">datastudio.workspaces.trash</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastudio.workspaces.update" class="permission-name add-link" data-text="datastudio.workspaces.update" tabindex="-1"><code dir="ltr" translate="no">datastudio.workspaces.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.lookerAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="lookerstudio.pro.manage" class="permission-name add-link" data-text="lookerstudio.pro.manage" tabindex="-1"><code dir="ltr" translate="no">lookerstudio.pro.manage</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.proManager">Looker Studio Pro Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lookerstudio.proManager</code> )</p></td>
</tr>
</tbody>
</table>
