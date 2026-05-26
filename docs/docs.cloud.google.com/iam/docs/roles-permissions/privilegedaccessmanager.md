---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager
title: Privileged Access Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Privileged Access Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Privileged Access Manager roles

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
<td><h4 id="privilegedaccessmanager.admin" class="role-title add-link" data-text="Privileged Access Manager Admin" tabindex="-1">Privileged Access Manager Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p>
<p>Full access to Privileged Access Manager resources.</p></td>
<td><p><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.*</code></p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  create</code></li>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  delete</code></li>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  get</code></li>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  list</code></li>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  grants.*</code></p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  grants.  get</code></li>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  grants.  list</code></li>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  grants.  revoke</code></li>
</ul>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  locations.  checkOnboardingStatus</code></li>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  locations.  get</code></li>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  fetchEffective</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="privilegedaccessmanager.editor" class="role-title add-link" data-text="Privilegedaccessmanager Editor" tabindex="-1">Privilegedaccessmanager Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  privilegedaccessmanager.editor</code> )</p>
<p>Editor role for privilegedaccessmanager</p></td>
<td><p><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  get</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  grants.  get</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  grants.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  locations.  get</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  operations.  get</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  fetchEffective</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="privilegedaccessmanager.viewer" class="role-title add-link" data-text="Privileged Access Manager Viewer" tabindex="-1">Privileged Access Manager Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  privilegedaccessmanager.viewer</code> )</p>
<p>Readonly access to Privileged Access Manager resources.</p></td>
<td><p><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  get</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  grants.  get</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  grants.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  locations.  get</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  locations.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  operations.  get</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  fetchEffective</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="privilegedaccessmanager.settingsAdmin" class="role-title add-link" data-text="Privileged Access Manager Settings Admin Beta" tabindex="-1">Privileged Access Manager Settings Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  privilegedaccessmanager.settingsAdmin</code> )</p>
<p>Administrator of Privileged Access Manager Settings.</p></td>
<td><p><code dir="ltr" translate="no">privilegedaccessmanager.  operations.  get</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  settings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  fetchEffective</code></li>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  get</code></li>
<li><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="privilegedaccessmanager.settingsViewer" class="role-title add-link" data-text="Privileged Access Manager Settings Viewer Beta" tabindex="-1">Privileged Access Manager Settings Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  privilegedaccessmanager.settingsViewer</code> )</p>
<p>Readonly access to Privileged Access Manager Settings &amp; Effective Settings.</p></td>
<td><p><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  fetchEffective</code></p>
<p><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  get</code></p></td>
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
<td><h4 id="privilegedaccessmanager.folderServiceAgent" class="role-title add-link" data-text="Privileged Access Manager Folder Service Agent" tabindex="-1">Privileged Access Manager Folder Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  privilegedaccessmanager.folderServiceAgent</code> )</p>
<p>Gives privileged access manager service account access to modify IAM policies on GCP folders</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  setIamPolicy</code></p></td>
</tr>
<tr class="even">
<td><h4 id="privilegedaccessmanager.organizationServiceAgent" class="role-title add-link" data-text="Privileged Access Manager Organization Service Agent" tabindex="-1">Privileged Access Manager Organization Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  privilegedaccessmanager.organizationServiceAgent</code> )</p>
<p>Gives privileged access manager service account access to modify IAM policies on GCP organizations</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">iam.roles.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  setIamPolicy</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="privilegedaccessmanager.projectServiceAgent" class="role-title add-link" data-text="Privileged Access Manager Project Service Agent" tabindex="-1">Privileged Access Manager Project Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  privilegedaccessmanager.projectServiceAgent</code> )</p>
<p>Gives privileged access manager service account access to modify IAM policies on GCP projects</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">iam.roles.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  setIamPolicy</code></p></td>
</tr>
<tr class="even">
<td><h4 id="privilegedaccessmanager.serviceAgent" class="role-title add-link" data-text="Privileged Access Manager Service Agent" tabindex="-1">Privileged Access Manager Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  privilegedaccessmanager.serviceAgent</code> )</p>
<p>Gives privileged access manager service account access to modify IAM policies on GCP resources</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">iam.roles.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  setIamPolicy</code></p></td>
</tr>
</tbody>
</table>

## Privileged Access Manager permissions

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
<td><h4 id="privilegedaccessmanager.entitlements.create" class="permission-name add-link" data-text="privilegedaccessmanager.entitlements.create" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="privilegedaccessmanager.entitlements.delete" class="permission-name add-link" data-text="privilegedaccessmanager.entitlements.delete" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="privilegedaccessmanager.entitlements.get" class="permission-name add-link" data-text="privilegedaccessmanager.entitlements.get" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.viewer">Privileged Access Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="privilegedaccessmanager.entitlements.list" class="permission-name add-link" data-text="privilegedaccessmanager.entitlements.list" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.viewer">Privileged Access Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="privilegedaccessmanager.entitlements.setIamPolicy" class="permission-name add-link" data-text="privilegedaccessmanager.entitlements.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="privilegedaccessmanager.entitlements.update" class="permission-name add-link" data-text="privilegedaccessmanager.entitlements.update" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  entitlements.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="privilegedaccessmanager.grants.get" class="permission-name add-link" data-text="privilegedaccessmanager.grants.get" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  grants.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.viewer">Privileged Access Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="privilegedaccessmanager.grants.list" class="permission-name add-link" data-text="privilegedaccessmanager.grants.list" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  grants.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.viewer">Privileged Access Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="privilegedaccessmanager.grants.revoke" class="permission-name add-link" data-text="privilegedaccessmanager.grants.revoke" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  grants.  revoke</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="privilegedaccessmanager.locations.checkOnboardingStatus" class="permission-name add-link" data-text="privilegedaccessmanager.locations.checkOnboardingStatus" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  locations.  checkOnboardingStatus</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="privilegedaccessmanager.locations.get" class="permission-name add-link" data-text="privilegedaccessmanager.locations.get" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.viewer">Privileged Access Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="privilegedaccessmanager.locations.list" class="permission-name add-link" data-text="privilegedaccessmanager.locations.list" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.viewer">Privileged Access Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="privilegedaccessmanager.operations.delete" class="permission-name add-link" data-text="privilegedaccessmanager.operations.delete" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="privilegedaccessmanager.operations.get" class="permission-name add-link" data-text="privilegedaccessmanager.operations.get" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.viewer">Privileged Access Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.settingsAdmin">Privileged Access Manager Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.settingsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="privilegedaccessmanager.operations.list" class="permission-name add-link" data-text="privilegedaccessmanager.operations.list" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.viewer">Privileged Access Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="privilegedaccessmanager.settings.fetchEffective" class="permission-name add-link" data-text="privilegedaccessmanager.settings.fetchEffective" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  fetchEffective</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.viewer">Privileged Access Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.settingsAdmin">Privileged Access Manager Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.settingsViewer">Privileged Access Manager Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.settingsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="privilegedaccessmanager.settings.get" class="permission-name add-link" data-text="privilegedaccessmanager.settings.get" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.viewer">Privileged Access Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.settingsAdmin">Privileged Access Manager Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.settingsViewer">Privileged Access Manager Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.settingsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="privilegedaccessmanager.settings.update" class="permission-name add-link" data-text="privilegedaccessmanager.settings.update" tabindex="-1"><code dir="ltr" translate="no">privilegedaccessmanager.  settings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.settingsAdmin">Privileged Access Manager Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  privilegedaccessmanager.settingsAdmin</code> )</p></td>
</tr>
</tbody>
</table>
