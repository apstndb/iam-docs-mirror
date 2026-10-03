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
<td>Access Approval Admin
<p>( <code>roles/ accessapproval.admin</code> )</p>
<p>Admin role for Access Approval</p></td>
<td><p><code>accessapproval.*</code></p>
<ul>
<li><code>accessapproval. requests. approve</code></li>
<li><code>accessapproval. requests. dismiss</code></li>
<li><code>accessapproval.requests.get</code></li>
<li><code>accessapproval. requests. invalidate</code></li>
<li><code>accessapproval.requests.list</code></li>
<li><code>accessapproval. serviceAccounts. get</code></li>
<li><code>accessapproval.settings.delete</code></li>
<li><code>accessapproval.settings.get</code></li>
<li><code>accessapproval.settings.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Access Approval Editor
<p>( <code>roles/ accessapproval.editor</code> )</p>
<p>Editor role for Access Approval</p></td>
<td><p><code>accessapproval.requests.get</code></p>
<p><code>accessapproval.requests.list</code></p>
<p><code>accessapproval. serviceAccounts. get</code></p>
<p><code>accessapproval.settings.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Access Approval Viewer
<p>( <code>roles/ accessapproval.viewer</code> )</p>
<p>Ability to view access approval requests and configuration</p></td>
<td><p><code>accessapproval.requests.get</code></p>
<p><code>accessapproval.requests.list</code></p>
<p><code>accessapproval. serviceAccounts. get</code></p>
<p><code>accessapproval.settings.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Access Approval Approver
<p>( <code>roles/ accessapproval.approver</code> )</p>
<p>Ability to view or act on access approval requests and view configuration.</p></td>
<td><p><code>accessapproval.requests.*</code></p>
<ul>
<li><code>accessapproval. requests. approve</code></li>
<li><code>accessapproval. requests. dismiss</code></li>
<li><code>accessapproval.requests.get</code></li>
<li><code>accessapproval. requests. invalidate</code></li>
<li><code>accessapproval.requests.list</code></li>
</ul>
<p><code>accessapproval. serviceAccounts. get</code></p>
<p><code>accessapproval.settings.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Access Approval Config Editor
<p>( <code>roles/ accessapproval.configEditor</code> )</p>
<p>Ability to update the Access Approval configuration</p></td>
<td><p><code>accessapproval. serviceAccounts. get</code></p>
<p><code>accessapproval.settings.*</code></p>
<ul>
<li><code>accessapproval.settings.delete</code></li>
<li><code>accessapproval.settings.get</code></li>
<li><code>accessapproval.settings.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Access Approval Invalidator
<p>( <code>roles/ accessapproval.invalidator</code> )</p>
<p>Ability to invalidate existing approved approval requests</p></td>
<td><p><code>accessapproval. requests. invalidate</code></p>
<p><code>accessapproval. serviceAccounts. get</code></p>
<p><code>accessapproval.settings.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td><code>accessapproval. requests. approve</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code>roles/ accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code>roles/ accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>accessapproval. requests. dismiss</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code>roles/ accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code>roles/ accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>accessapproval.requests.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code>roles/ accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.editor">Access Approval Editor</a> ( <code>roles/ accessapproval.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.viewer">Access Approval Viewer</a> ( <code>roles/ accessapproval.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code>roles/ accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.accessApprovalServiceAgent">Cloud Controls Partner Access Approval Service Agent</a> ( <code>roles/ cloudcontrolspartner.accessApprovalServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>accessapproval. requests. invalidate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code>roles/ accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code>roles/ accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.invalidator">Access Approval Invalidator</a> ( <code>roles/ accessapproval.invalidator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>accessapproval.requests.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code>roles/ accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.editor">Access Approval Editor</a> ( <code>roles/ accessapproval.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.viewer">Access Approval Viewer</a> ( <code>roles/ accessapproval.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code>roles/ accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.accessApprovalServiceAgent">Cloud Controls Partner Access Approval Service Agent</a> ( <code>roles/ cloudcontrolspartner.accessApprovalServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>accessapproval. serviceAccounts. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code>roles/ accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.editor">Access Approval Editor</a> ( <code>roles/ accessapproval.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.viewer">Access Approval Viewer</a> ( <code>roles/ accessapproval.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code>roles/ accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.configEditor">Access Approval Config Editor</a> ( <code>roles/ accessapproval.configEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.invalidator">Access Approval Invalidator</a> ( <code>roles/ accessapproval.invalidator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>accessapproval.settings.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code>roles/ accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.configEditor">Access Approval Config Editor</a> ( <code>roles/ accessapproval.configEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>accessapproval.settings.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code>roles/ accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.editor">Access Approval Editor</a> ( <code>roles/ accessapproval.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.viewer">Access Approval Viewer</a> ( <code>roles/ accessapproval.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code>roles/ accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.configEditor">Access Approval Config Editor</a> ( <code>roles/ accessapproval.configEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.invalidator">Access Approval Invalidator</a> ( <code>roles/ accessapproval.invalidator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>accessapproval.settings.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code>roles/ accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.configEditor">Access Approval Config Editor</a> ( <code>roles/ accessapproval.configEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
</tbody>
</table>
