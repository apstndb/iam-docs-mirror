---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/secretmanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager
title: Secret Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Secret Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Secret Manager roles

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
<td><h4 id="secretmanager.admin" class="role-title add-link" data-text="Secret Manager Admin" tabindex="-1">Secret Manager Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p>Full access to administer Secret Manager resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Secret</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.*</code></p>
<ul>
<li><code dir="ltr" translate="no">secretmanager.locations.get</code></li>
<li><code dir="ltr" translate="no">secretmanager.locations.list</code></li>
<li><code dir="ltr" translate="no">secretmanager.secrets.create</code></li>
<li><code dir="ltr" translate="no">secretmanager.  secrets.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">secretmanager.secrets.delete</code></li>
<li><code dir="ltr" translate="no">secretmanager.  secrets.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">secretmanager.secrets.get</code></li>
<li><code dir="ltr" translate="no">secretmanager.  secrets.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">secretmanager.secrets.list</code></li>
<li><code dir="ltr" translate="no">secretmanager.  secrets.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">secretmanager.  secrets.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">secretmanager.  secrets.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">secretmanager.secrets.update</code></li>
<li><code dir="ltr" translate="no">secretmanager.versions.access</code></li>
<li><code dir="ltr" translate="no">secretmanager.versions.add</code></li>
<li><code dir="ltr" translate="no">secretmanager.versions.destroy</code></li>
<li><code dir="ltr" translate="no">secretmanager.versions.disable</code></li>
<li><code dir="ltr" translate="no">secretmanager.versions.enable</code></li>
<li><code dir="ltr" translate="no">secretmanager.versions.get</code></li>
<li><code dir="ltr" translate="no">secretmanager.versions.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="secretmanager.secretAccessor" class="role-title add-link" data-text="Secret Manager Secret Accessor" tabindex="-1">Secret Manager Secret Accessor</h4>
<p>( <code dir="ltr" translate="no">roles/  secretmanager.secretAccessor</code> )</p>
<p>Allows accessing the payload of secrets.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Secret</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.versions.access</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="secretmanager.viewer" class="role-title add-link" data-text="Secret Manager Viewer" tabindex="-1">Secret Manager Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  secretmanager.viewer</code> )</p>
<p>Allows viewing metadata of all Secret Manager resources</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Secret</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">secretmanager.locations.get</code></li>
<li><code dir="ltr" translate="no">secretmanager.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">secretmanager.secrets.get</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">secretmanager.secrets.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">secretmanager.versions.get</code></p>
<p><code dir="ltr" translate="no">secretmanager.versions.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="secretmanager.secretVersionAdder" class="role-title add-link" data-text="Secret Manager Secret Version Adder" tabindex="-1">Secret Manager Secret Version Adder</h4>
<p>( <code dir="ltr" translate="no">roles/  secretmanager.secretVersionAdder</code> )</p>
<p>Allows adding versions to existing secrets.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Secret</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.versions.add</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="secretmanager.secretVersionManager" class="role-title add-link" data-text="Secret Manager Secret Version Manager" tabindex="-1">Secret Manager Secret Version Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  secretmanager.secretVersionManager</code> )</p>
<p>Allows creating and managing versions of existing secrets.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Secret</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.versions.add</code></p>
<p><code dir="ltr" translate="no">secretmanager.versions.destroy</code></p>
<p><code dir="ltr" translate="no">secretmanager.versions.disable</code></p>
<p><code dir="ltr" translate="no">secretmanager.versions.enable</code></p>
<p><code dir="ltr" translate="no">secretmanager.versions.get</code></p>
<p><code dir="ltr" translate="no">secretmanager.versions.list</code></p></td>
</tr>
</tbody>
</table>

## Secret Manager permissions

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
<td><h4 id="secretmanager.locations.get" class="permission-name add-link" data-text="secretmanager.locations.get" tabindex="-1"><code dir="ltr" translate="no">secretmanager.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.viewer">Secret Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="secretmanager.locations.list" class="permission-name add-link" data-text="secretmanager.locations.list" tabindex="-1"><code dir="ltr" translate="no">secretmanager.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.viewer">Secret Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="secretmanager.secrets.create" class="permission-name add-link" data-text="secretmanager.secrets.create" tabindex="-1"><code dir="ltr" translate="no">secretmanager.secrets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="secretmanager.secrets.createTagBinding" class="permission-name add-link" data-text="secretmanager.secrets.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">secretmanager.  secrets.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="secretmanager.secrets.delete" class="permission-name add-link" data-text="secretmanager.secrets.delete" tabindex="-1"><code dir="ltr" translate="no">secretmanager.secrets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="secretmanager.secrets.deleteTagBinding" class="permission-name add-link" data-text="secretmanager.secrets.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">secretmanager.  secrets.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="secretmanager.secrets.get" class="permission-name add-link" data-text="secretmanager.secrets.get" tabindex="-1"><code dir="ltr" translate="no">secretmanager.secrets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.viewer">Secret Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="secretmanager.secrets.getIamPolicy" class="permission-name add-link" data-text="secretmanager.secrets.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">secretmanager.  secrets.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.viewer">Secret Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="secretmanager.secrets.list" class="permission-name add-link" data-text="secretmanager.secrets.list" tabindex="-1"><code dir="ltr" translate="no">secretmanager.secrets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.viewer">Secret Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="secretmanager.secrets.listEffectiveTags" class="permission-name add-link" data-text="secretmanager.secrets.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">secretmanager.  secrets.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.viewer">Secret Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="secretmanager.secrets.listTagBindings" class="permission-name add-link" data-text="secretmanager.secrets.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">secretmanager.  secrets.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.viewer">Secret Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="secretmanager.secrets.setIamPolicy" class="permission-name add-link" data-text="secretmanager.secrets.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">secretmanager.  secrets.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="secretmanager.secrets.update" class="permission-name add-link" data-text="secretmanager.secrets.update" tabindex="-1"><code dir="ltr" translate="no">secretmanager.secrets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="secretmanager.versions.access" class="permission-name add-link" data-text="secretmanager.versions.access" tabindex="-1"><code dir="ltr" translate="no">secretmanager.versions.access</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretAccessor">Secret Manager Secret Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretAccessor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="secretmanager.versions.add" class="permission-name add-link" data-text="secretmanager.versions.add" tabindex="-1"><code dir="ltr" translate="no">secretmanager.versions.add</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionAdder">Secret Manager Secret Version Adder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionManager">Secret Manager Secret Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretVersionManager</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="secretmanager.versions.destroy" class="permission-name add-link" data-text="secretmanager.versions.destroy" tabindex="-1"><code dir="ltr" translate="no">secretmanager.versions.destroy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionManager">Secret Manager Secret Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretVersionManager</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="secretmanager.versions.disable" class="permission-name add-link" data-text="secretmanager.versions.disable" tabindex="-1"><code dir="ltr" translate="no">secretmanager.versions.disable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionManager">Secret Manager Secret Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretVersionManager</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="secretmanager.versions.enable" class="permission-name add-link" data-text="secretmanager.versions.enable" tabindex="-1"><code dir="ltr" translate="no">secretmanager.versions.enable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionManager">Secret Manager Secret Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretVersionManager</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="secretmanager.versions.get" class="permission-name add-link" data-text="secretmanager.versions.get" tabindex="-1"><code dir="ltr" translate="no">secretmanager.versions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.viewer">Secret Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionManager">Secret Manager Secret Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretVersionManager</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="secretmanager.versions.list" class="permission-name add-link" data-text="secretmanager.versions.list" tabindex="-1"><code dir="ltr" translate="no">secretmanager.versions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.viewer">Secret Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionManager">Secret Manager Secret Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  secretmanager.secretVersionManager</code> )</p></td>
</tr>
</tbody>
</table>
