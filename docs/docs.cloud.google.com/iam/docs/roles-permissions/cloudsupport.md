---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport
title: Google Cloud Support roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Cloud Support. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Cloud Support roles

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
<td><h4 id="cloudsupport.admin" class="role-title add-link" data-text="Support Account Administrator" tabindex="-1">Support Account Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p>
<p>Allows management of a support account without giving access to support cases. See the <a href="https://docs.cloud.google.com/support/docs/access-control#support_account_admin">Cloud Support documentation</a> for more information.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudsupport.accounts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudsupport.accounts.create</code></li>
<li><code dir="ltr" translate="no">cloudsupport.accounts.delete</code></li>
<li><code dir="ltr" translate="no">cloudsupport.accounts.get</code></li>
<li><code dir="ltr" translate="no">cloudsupport.  accounts.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudsupport.  accounts.  getUserRoles</code></li>
<li><code dir="ltr" translate="no">cloudsupport.accounts.list</code></li>
<li><code dir="ltr" translate="no">cloudsupport.accounts.purchase</code></li>
<li><code dir="ltr" translate="no">cloudsupport.  accounts.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudsupport.accounts.update</code></li>
<li><code dir="ltr" translate="no">cloudsupport.  accounts.  updateUserRoles</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudsupport.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudsupport.properties.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudsupport.viewer" class="role-title add-link" data-text="Support Account Viewer" tabindex="-1">Support Account Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsupport.viewer</code> )</p>
<p>Read-only access to details of a support account. This does not allow viewing cases. See the <a href="https://docs.cloud.google.com/support/docs/access-control#support_account_viewer">Cloud Support documentation</a> for more information.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudsupport.accounts.get</code></p>
<p><code dir="ltr" translate="no">cloudsupport.  accounts.  getUserRoles</code></p>
<p><code dir="ltr" translate="no">cloudsupport.accounts.list</code></p>
<p><code dir="ltr" translate="no">cloudsupport.properties.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsupport.advisorySupportEditor" class="role-title add-link" data-text="Advisory Support Editor" tabindex="-1">Advisory Support Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsupport.advisorySupportEditor</code> )</p>
<p>Full read-write access to advisory support cases applicable for GCP Customer Care.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudsupport.properties.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudsupport.advisorySupportViewer" class="role-title add-link" data-text="Advisory Support Viewer" tabindex="-1">Advisory Support Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsupport.advisorySupportViewer</code> )</p>
<p>Read-only access to advisory support cases applicable for GCP Customer Care.</p></td>
<td><p><code dir="ltr" translate="no">cloudsupport.properties.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsupport.techSupportEditor" class="role-title add-link" data-text="Tech Support Editor" tabindex="-1">Tech Support Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsupport.techSupportEditor</code> )</p>
<p>Full read-write access to technical support cases (applicable for GCP Customer Care and Maps support). See the <a href="https://docs.cloud.google.com/support/docs/access-control#tech_support_editor">Cloud Support documentation</a> for more information.</p></td>
<td><p><code dir="ltr" translate="no">billing.  resourceAssociations.  list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudsupport.properties.get</code></p>
<p><code dir="ltr" translate="no">cloudsupport.techCases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudsupport.techCases.create</code></li>
<li><code dir="ltr" translate="no">cloudsupport.  techCases.  escalate</code></li>
<li><code dir="ltr" translate="no">cloudsupport.techCases.get</code></li>
<li><code dir="ltr" translate="no">cloudsupport.techCases.list</code></li>
<li><code dir="ltr" translate="no">cloudsupport.techCases.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudsupport.techSupportViewer" class="role-title add-link" data-text="Tech Support Viewer" tabindex="-1">Tech Support Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsupport.techSupportViewer</code> )</p>
<p>Read-only access to technical support cases (applicable for GCP Customer Care and Maps support). See the <a href="https://docs.cloud.google.com/support/docs/access-control#tech_support_viewer">Cloud Support documentation</a> for more information.</p></td>
<td><p><code dir="ltr" translate="no">cloudsupport.properties.get</code></p>
<p><code dir="ltr" translate="no">cloudsupport.techCases.get</code></p>
<p><code dir="ltr" translate="no">cloudsupport.techCases.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Google Cloud Support permissions

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
<td><h4 id="cloudsupport.accounts.create" class="permission-name add-link" data-text="cloudsupport.accounts.create" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.accounts.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudsupport.accounts.delete" class="permission-name add-link" data-text="cloudsupport.accounts.delete" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.accounts.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsupport.accounts.get" class="permission-name add-link" data-text="cloudsupport.accounts.get" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.accounts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.viewer">Support Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudsupport.accounts.getIamPolicy" class="permission-name add-link" data-text="cloudsupport.accounts.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.  accounts.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsupport.accounts.getUserRoles" class="permission-name add-link" data-text="cloudsupport.accounts.getUserRoles" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.  accounts.  getUserRoles</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.viewer">Support Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudsupport.accounts.list" class="permission-name add-link" data-text="cloudsupport.accounts.list" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.accounts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.viewer">Support Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsupport.accounts.purchase" class="permission-name add-link" data-text="cloudsupport.accounts.purchase" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.accounts.purchase</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudsupport.accounts.setIamPolicy" class="permission-name add-link" data-text="cloudsupport.accounts.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.  accounts.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsupport.accounts.update" class="permission-name add-link" data-text="cloudsupport.accounts.update" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.accounts.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudsupport.accounts.updateUserRoles" class="permission-name add-link" data-text="cloudsupport.accounts.updateUserRoles" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.  accounts.  updateUserRoles</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsupport.operations.get" class="permission-name add-link" data-text="cloudsupport.operations.get" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudsupport.properties.get" class="permission-name add-link" data-text="cloudsupport.properties.get" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.properties.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.viewer">Support Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.advisorySupportEditor">Advisory Support Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.advisorySupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.advisorySupportViewer">Advisory Support Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.advisorySupportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportEditor">Tech Support Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportViewer">Tech Support Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsupport.techCases.create" class="permission-name add-link" data-text="cloudsupport.techCases.create" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.techCases.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportEditor">Tech Support Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudsupport.techCases.escalate" class="permission-name add-link" data-text="cloudsupport.techCases.escalate" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.  techCases.  escalate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportEditor">Tech Support Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsupport.techCases.get" class="permission-name add-link" data-text="cloudsupport.techCases.get" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.techCases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportEditor">Tech Support Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportViewer">Tech Support Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.supportCaseServiceAgent">Cloud Controls Partner Support Case Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.supportCaseServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsupport.techCases.list" class="permission-name add-link" data-text="cloudsupport.techCases.list" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.techCases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportEditor">Tech Support Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportViewer">Tech Support Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsupport.techCases.update" class="permission-name add-link" data-text="cloudsupport.techCases.update" tabindex="-1"><code dir="ltr" translate="no">cloudsupport.techCases.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportEditor">Tech Support Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsupport.techSupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
