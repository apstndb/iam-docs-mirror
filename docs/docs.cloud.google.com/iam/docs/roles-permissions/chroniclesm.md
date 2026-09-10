---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm
title: Google Security Operations Service Management roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Security Operations Service Management. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Security Operations Service Management roles

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
<td><h4 id="chroniclesm.admin" class="role-title add-link" data-text="Chronicle Service Admin" tabindex="-1">Chronicle Service Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  chroniclesm.admin</code> )</p>
<p>Admins can view and modify Chronicle service details.</p></td>
<td><p><code dir="ltr" translate="no">chroniclesm.*</code></p>
<ul>
<li><code dir="ltr" translate="no">chroniclesm.contracts.get</code></li>
<li><code dir="ltr" translate="no">chroniclesm.contracts.update</code></li>
<li><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  create</code></li>
<li><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  delete</code></li>
<li><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  get</code></li>
<li><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  list</code></li>
<li><code dir="ltr" translate="no">chroniclesm.  gcpLogFlowFilters.  get</code></li>
<li><code dir="ltr" translate="no">chroniclesm.  gcpLogFlowFilters.  update</code></li>
<li><code dir="ltr" translate="no">chroniclesm.gcpSettings.get</code></li>
<li><code dir="ltr" translate="no">chroniclesm.gcpSettings.update</code></li>
<li><code dir="ltr" translate="no">chroniclesm.  soarRoleScripts.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="chroniclesm.editor" class="role-title add-link" data-text="Chroniclesm Editor" tabindex="-1">Chroniclesm Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  chroniclesm.editor</code> )</p>
<p>Editor role for chroniclesm</p></td>
<td><p><code dir="ltr" translate="no">chroniclesm.contracts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">chroniclesm.contracts.get</code></li>
<li><code dir="ltr" translate="no">chroniclesm.contracts.update</code></li>
</ul>
<p><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  get</code></p>
<p><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  list</code></p>
<p><code dir="ltr" translate="no">chroniclesm.  gcpLogFlowFilters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">chroniclesm.  gcpLogFlowFilters.  get</code></li>
<li><code dir="ltr" translate="no">chroniclesm.  gcpLogFlowFilters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">chroniclesm.gcpSettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">chroniclesm.gcpSettings.get</code></li>
<li><code dir="ltr" translate="no">chroniclesm.gcpSettings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">chroniclesm.  soarRoleScripts.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="chroniclesm.viewer" class="role-title add-link" data-text="Chronicle Service Viewer" tabindex="-1">Chronicle Service Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  chroniclesm.viewer</code> )</p>
<p>Viewers can see Chronicle service details but not change them.</p></td>
<td><p><code dir="ltr" translate="no">chroniclesm.contracts.get</code></p>
<p><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  get</code></p>
<p><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  list</code></p>
<p><code dir="ltr" translate="no">chroniclesm.  gcpLogFlowFilters.  get</code></p>
<p><code dir="ltr" translate="no">chroniclesm.gcpSettings.get</code></p>
<p><code dir="ltr" translate="no">chroniclesm.  soarRoleScripts.  list</code></p></td>
</tr>
</tbody>
</table>

## Google Security Operations Service Management permissions

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
<td><h4 id="chroniclesm.contracts.get" class="permission-name add-link" data-text="chroniclesm.contracts.get" tabindex="-1"><code dir="ltr" translate="no">chroniclesm.contracts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.admin">Chronicle Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.editor">Chroniclesm Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.viewer">Chronicle Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="chroniclesm.contracts.update" class="permission-name add-link" data-text="chroniclesm.contracts.update" tabindex="-1"><code dir="ltr" translate="no">chroniclesm.contracts.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.admin">Chronicle Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.editor">Chroniclesm Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="chroniclesm.gcpAssociations.create" class="permission-name add-link" data-text="chroniclesm.gcpAssociations.create" tabindex="-1"><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.admin">Chronicle Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="chroniclesm.gcpAssociations.delete" class="permission-name add-link" data-text="chroniclesm.gcpAssociations.delete" tabindex="-1"><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.admin">Chronicle Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="chroniclesm.gcpAssociations.get" class="permission-name add-link" data-text="chroniclesm.gcpAssociations.get" tabindex="-1"><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.admin">Chronicle Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.editor">Chroniclesm Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.viewer">Chronicle Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="chroniclesm.gcpAssociations.list" class="permission-name add-link" data-text="chroniclesm.gcpAssociations.list" tabindex="-1"><code dir="ltr" translate="no">chroniclesm.  gcpAssociations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.admin">Chronicle Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.editor">Chroniclesm Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.viewer">Chronicle Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="chroniclesm.gcpLogFlowFilters.get" class="permission-name add-link" data-text="chroniclesm.gcpLogFlowFilters.get" tabindex="-1"><code dir="ltr" translate="no">chroniclesm.  gcpLogFlowFilters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.admin">Chronicle Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.editor">Chroniclesm Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.viewer">Chronicle Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="chroniclesm.gcpLogFlowFilters.update" class="permission-name add-link" data-text="chroniclesm.gcpLogFlowFilters.update" tabindex="-1"><code dir="ltr" translate="no">chroniclesm.  gcpLogFlowFilters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.admin">Chronicle Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.editor">Chroniclesm Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="chroniclesm.gcpSettings.get" class="permission-name add-link" data-text="chroniclesm.gcpSettings.get" tabindex="-1"><code dir="ltr" translate="no">chroniclesm.gcpSettings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.admin">Chronicle Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.editor">Chroniclesm Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.viewer">Chronicle Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="chroniclesm.gcpSettings.update" class="permission-name add-link" data-text="chroniclesm.gcpSettings.update" tabindex="-1"><code dir="ltr" translate="no">chroniclesm.gcpSettings.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.admin">Chronicle Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.editor">Chroniclesm Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="chroniclesm.soarRoleScripts.list" class="permission-name add-link" data-text="chroniclesm.soarRoleScripts.list" tabindex="-1"><code dir="ltr" translate="no">chroniclesm.  soarRoleScripts.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.admin">Chronicle Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.editor">Chroniclesm Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.viewer">Chronicle Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chroniclesm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
