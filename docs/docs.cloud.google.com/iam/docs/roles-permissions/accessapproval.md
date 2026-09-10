---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/accessapproval
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval
title: Access Approval roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Access Approval. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Access Approval roles

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
<td><h4 id="accessapproval.admin" class="role-title add-link" data-text="Access Approval Admin" tabindex="-1">Access Approval Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  accessapproval.admin</code> )</p>
<p>Admin role for Access Approval</p></td>
<td><p><code dir="ltr" translate="no">accessapproval.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accessapproval.  requests.  approve</code></li>
<li><code dir="ltr" translate="no">accessapproval.  requests.  dismiss</code></li>
<li><code dir="ltr" translate="no">accessapproval.requests.get</code></li>
<li><code dir="ltr" translate="no">accessapproval.  requests.  invalidate</code></li>
<li><code dir="ltr" translate="no">accessapproval.requests.list</code></li>
<li><code dir="ltr" translate="no">accessapproval.  serviceAccounts.  get</code></li>
<li><code dir="ltr" translate="no">accessapproval.settings.delete</code></li>
<li><code dir="ltr" translate="no">accessapproval.settings.get</code></li>
<li><code dir="ltr" translate="no">accessapproval.settings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="accessapproval.editor" class="role-title add-link" data-text="Access Approval Editor" tabindex="-1">Access Approval Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  accessapproval.editor</code> )</p>
<p>Editor role for Access Approval</p></td>
<td><p><code dir="ltr" translate="no">accessapproval.requests.get</code></p>
<p><code dir="ltr" translate="no">accessapproval.requests.list</code></p>
<p><code dir="ltr" translate="no">accessapproval.  serviceAccounts.  get</code></p>
<p><code dir="ltr" translate="no">accessapproval.settings.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="accessapproval.viewer" class="role-title add-link" data-text="Access Approval Viewer" tabindex="-1">Access Approval Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  accessapproval.viewer</code> )</p>
<p>Ability to view access approval requests and configuration</p></td>
<td><p><code dir="ltr" translate="no">accessapproval.requests.get</code></p>
<p><code dir="ltr" translate="no">accessapproval.requests.list</code></p>
<p><code dir="ltr" translate="no">accessapproval.  serviceAccounts.  get</code></p>
<p><code dir="ltr" translate="no">accessapproval.settings.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="accessapproval.approver" class="role-title add-link" data-text="Access Approval Approver" tabindex="-1">Access Approval Approver</h4>
<p>( <code dir="ltr" translate="no">roles/  accessapproval.approver</code> )</p>
<p>Ability to view or act on access approval requests and view configuration.</p></td>
<td><p><code dir="ltr" translate="no">accessapproval.requests.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accessapproval.  requests.  approve</code></li>
<li><code dir="ltr" translate="no">accessapproval.  requests.  dismiss</code></li>
<li><code dir="ltr" translate="no">accessapproval.requests.get</code></li>
<li><code dir="ltr" translate="no">accessapproval.  requests.  invalidate</code></li>
<li><code dir="ltr" translate="no">accessapproval.requests.list</code></li>
</ul>
<p><code dir="ltr" translate="no">accessapproval.  serviceAccounts.  get</code></p>
<p><code dir="ltr" translate="no">accessapproval.settings.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="accessapproval.configEditor" class="role-title add-link" data-text="Access Approval Config Editor" tabindex="-1">Access Approval Config Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  accessapproval.configEditor</code> )</p>
<p>Ability to update the Access Approval configuration</p></td>
<td><p><code dir="ltr" translate="no">accessapproval.  serviceAccounts.  get</code></p>
<p><code dir="ltr" translate="no">accessapproval.settings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accessapproval.settings.delete</code></li>
<li><code dir="ltr" translate="no">accessapproval.settings.get</code></li>
<li><code dir="ltr" translate="no">accessapproval.settings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="accessapproval.invalidator" class="role-title add-link" data-text="Access Approval Invalidator" tabindex="-1">Access Approval Invalidator</h4>
<p>( <code dir="ltr" translate="no">roles/  accessapproval.invalidator</code> )</p>
<p>Ability to invalidate existing approved approval requests</p></td>
<td><p><code dir="ltr" translate="no">accessapproval.  requests.  invalidate</code></p>
<p><code dir="ltr" translate="no">accessapproval.  serviceAccounts.  get</code></p>
<p><code dir="ltr" translate="no">accessapproval.settings.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Access Approval permissions

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
<td><h4 id="accessapproval.requests.approve" class="permission-name add-link" data-text="accessapproval.requests.approve" tabindex="-1"><code dir="ltr" translate="no">accessapproval.  requests.  approve</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.approver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="accessapproval.requests.dismiss" class="permission-name add-link" data-text="accessapproval.requests.dismiss" tabindex="-1"><code dir="ltr" translate="no">accessapproval.  requests.  dismiss</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.approver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="accessapproval.requests.get" class="permission-name add-link" data-text="accessapproval.requests.get" tabindex="-1"><code dir="ltr" translate="no">accessapproval.requests.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.editor">Access Approval Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.viewer">Access Approval Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.accessApprovalServiceAgent">Cloud Controls Partner Access Approval Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.accessApprovalServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="accessapproval.requests.invalidate" class="permission-name add-link" data-text="accessapproval.requests.invalidate" tabindex="-1"><code dir="ltr" translate="no">accessapproval.  requests.  invalidate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.invalidator">Access Approval Invalidator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.invalidator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="accessapproval.requests.list" class="permission-name add-link" data-text="accessapproval.requests.list" tabindex="-1"><code dir="ltr" translate="no">accessapproval.requests.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.editor">Access Approval Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.viewer">Access Approval Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.accessApprovalServiceAgent">Cloud Controls Partner Access Approval Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.accessApprovalServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="accessapproval.serviceAccounts.get" class="permission-name add-link" data-text="accessapproval.serviceAccounts.get" tabindex="-1"><code dir="ltr" translate="no">accessapproval.  serviceAccounts.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.editor">Access Approval Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.viewer">Access Approval Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.configEditor">Access Approval Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.configEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.invalidator">Access Approval Invalidator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.invalidator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="accessapproval.settings.delete" class="permission-name add-link" data-text="accessapproval.settings.delete" tabindex="-1"><code dir="ltr" translate="no">accessapproval.settings.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.configEditor">Access Approval Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.configEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="accessapproval.settings.get" class="permission-name add-link" data-text="accessapproval.settings.get" tabindex="-1"><code dir="ltr" translate="no">accessapproval.settings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.editor">Access Approval Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.viewer">Access Approval Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.configEditor">Access Approval Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.configEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.invalidator">Access Approval Invalidator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.invalidator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="accessapproval.settings.update" class="permission-name add-link" data-text="accessapproval.settings.update" tabindex="-1"><code dir="ltr" translate="no">accessapproval.settings.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.configEditor">Access Approval Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accessapproval.configEditor</code> )</p></td>
</tr>
</tbody>
</table>
