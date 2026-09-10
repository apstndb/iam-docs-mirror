---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/domains
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/domains
title: Cloud Domains roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Domains. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Domains roles

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
<td><h4 id="domains.admin" class="role-title add-link" data-text="Cloud Domains Admin" tabindex="-1">Cloud Domains Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p>Full access to Cloud Domains Registrations and related resources.</p></td>
<td><p><code dir="ltr" translate="no">domains.*</code></p>
<ul>
<li><code dir="ltr" translate="no">domains.locations.get</code></li>
<li><code dir="ltr" translate="no">domains.locations.list</code></li>
<li><code dir="ltr" translate="no">domains.operations.cancel</code></li>
<li><code dir="ltr" translate="no">domains.operations.get</code></li>
<li><code dir="ltr" translate="no">domains.operations.list</code></li>
<li><code dir="ltr" translate="no">domains.  registrations.  configureContact</code></li>
<li><code dir="ltr" translate="no">domains.  registrations.  configureDns</code></li>
<li><code dir="ltr" translate="no">domains.  registrations.  configureManagement</code></li>
<li><code dir="ltr" translate="no">domains.registrations.create</code></li>
<li><code dir="ltr" translate="no">domains.  registrations.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">domains.registrations.delete</code></li>
<li><code dir="ltr" translate="no">domains.  registrations.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">domains.registrations.get</code></li>
<li><code dir="ltr" translate="no">domains.  registrations.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">domains.registrations.list</code></li>
<li><code dir="ltr" translate="no">domains.  registrations.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">domains.  registrations.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">domains.  registrations.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">domains.registrations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="domains.editor" class="role-title add-link" data-text="Cloud Domains Editor" tabindex="-1">Cloud Domains Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  domains.editor</code> )</p>
<p>Editor role for Cloud Domains</p></td>
<td><p><code dir="ltr" translate="no">domains.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">domains.locations.get</code></li>
<li><code dir="ltr" translate="no">domains.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">domains.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">domains.operations.cancel</code></li>
<li><code dir="ltr" translate="no">domains.operations.get</code></li>
<li><code dir="ltr" translate="no">domains.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">domains.  registrations.  configureContact</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  configureDns</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  configureManagement</code></p>
<p><code dir="ltr" translate="no">domains.registrations.create</code></p>
<p><code dir="ltr" translate="no">domains.registrations.delete</code></p>
<p><code dir="ltr" translate="no">domains.registrations.get</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">domains.registrations.list</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">domains.registrations.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="domains.viewer" class="role-title add-link" data-text="Cloud Domains Viewer" tabindex="-1">Cloud Domains Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  domains.viewer</code> )</p>
<p>Read-only access to Cloud Domains Registrations and related resources.</p></td>
<td><p><code dir="ltr" translate="no">domains.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">domains.locations.get</code></li>
<li><code dir="ltr" translate="no">domains.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">domains.operations.get</code></p>
<p><code dir="ltr" translate="no">domains.operations.list</code></p>
<p><code dir="ltr" translate="no">domains.registrations.get</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">domains.registrations.list</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Cloud Domains permissions

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
<td><h4 id="domains.locations.get" class="permission-name add-link" data-text="domains.locations.get" tabindex="-1"><code dir="ltr" translate="no">domains.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.viewer">Cloud Domains Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="domains.locations.list" class="permission-name add-link" data-text="domains.locations.list" tabindex="-1"><code dir="ltr" translate="no">domains.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.viewer">Cloud Domains Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="domains.operations.cancel" class="permission-name add-link" data-text="domains.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">domains.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="domains.operations.get" class="permission-name add-link" data-text="domains.operations.get" tabindex="-1"><code dir="ltr" translate="no">domains.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.viewer">Cloud Domains Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="domains.operations.list" class="permission-name add-link" data-text="domains.operations.list" tabindex="-1"><code dir="ltr" translate="no">domains.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.viewer">Cloud Domains Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="domains.registrations.configureContact" class="permission-name add-link" data-text="domains.registrations.configureContact" tabindex="-1"><code dir="ltr" translate="no">domains.  registrations.  configureContact</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="domains.registrations.configureDns" class="permission-name add-link" data-text="domains.registrations.configureDns" tabindex="-1"><code dir="ltr" translate="no">domains.  registrations.  configureDns</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="domains.registrations.configureManagement" class="permission-name add-link" data-text="domains.registrations.configureManagement" tabindex="-1"><code dir="ltr" translate="no">domains.  registrations.  configureManagement</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="domains.registrations.create" class="permission-name add-link" data-text="domains.registrations.create" tabindex="-1"><code dir="ltr" translate="no">domains.registrations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="domains.registrations.createTagBinding" class="permission-name add-link" data-text="domains.registrations.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">domains.  registrations.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="domains.registrations.delete" class="permission-name add-link" data-text="domains.registrations.delete" tabindex="-1"><code dir="ltr" translate="no">domains.registrations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="domains.registrations.deleteTagBinding" class="permission-name add-link" data-text="domains.registrations.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">domains.  registrations.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="domains.registrations.get" class="permission-name add-link" data-text="domains.registrations.get" tabindex="-1"><code dir="ltr" translate="no">domains.registrations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.viewer">Cloud Domains Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="domains.registrations.getIamPolicy" class="permission-name add-link" data-text="domains.registrations.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">domains.  registrations.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.viewer">Cloud Domains Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="domains.registrations.list" class="permission-name add-link" data-text="domains.registrations.list" tabindex="-1"><code dir="ltr" translate="no">domains.registrations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.viewer">Cloud Domains Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="domains.registrations.listEffectiveTags" class="permission-name add-link" data-text="domains.registrations.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">domains.  registrations.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.viewer">Cloud Domains Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="domains.registrations.listTagBindings" class="permission-name add-link" data-text="domains.registrations.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">domains.  registrations.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.viewer">Cloud Domains Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="domains.registrations.setIamPolicy" class="permission-name add-link" data-text="domains.registrations.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">domains.  registrations.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="domains.registrations.update" class="permission-name add-link" data-text="domains.registrations.update" tabindex="-1"><code dir="ltr" translate="no">domains.registrations.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  domains.editor</code> )</p></td>
</tr>
</tbody>
</table>
