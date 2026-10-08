---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/workflows
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/workflows
title: Workflows roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Workflows. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Workflows roles

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
<td>Workflows Admin
<p>( <code>roles/ workflows.admin</code> )</p>
<p>Full access to workflows and related resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>workflows.*</code></p>
<ul>
<li><code>workflows.callbacks.list</code></li>
<li><code>workflows.callbacks.send</code></li>
<li><code>workflows.executions.cancel</code></li>
<li><code>workflows.executions.create</code></li>
<li><code>workflows.executions.get</code></li>
<li><code>workflows.executions.list</code></li>
<li><code>workflows.locations.get</code></li>
<li><code>workflows.locations.list</code></li>
<li><code>workflows.operations.cancel</code></li>
<li><code>workflows.operations.get</code></li>
<li><code>workflows.operations.list</code></li>
<li><code>workflows.stepEntries.get</code></li>
<li><code>workflows.stepEntries.list</code></li>
<li><code>workflows.workflows.create</code></li>
<li><code>workflows. workflows. createTagBinding</code></li>
<li><code>workflows.workflows.delete</code></li>
<li><code>workflows. workflows. deleteTagBinding</code></li>
<li><code>workflows.workflows.get</code></li>
<li><code>workflows.workflows.list</code></li>
<li><code>workflows. workflows. listEffectiveTags</code></li>
<li><code>workflows. workflows. listRevision</code></li>
<li><code>workflows. workflows. listTagBindings</code></li>
<li><code>workflows.workflows.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Workflows Editor
<p>( <code>roles/ workflows.editor</code> )</p>
<p>Read and write access to workflows and related resources, including development and debugging of workflows.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>workflows.*</code></p>
<ul>
<li><code>workflows.callbacks.list</code></li>
<li><code>workflows.callbacks.send</code></li>
<li><code>workflows.executions.cancel</code></li>
<li><code>workflows.executions.create</code></li>
<li><code>workflows.executions.get</code></li>
<li><code>workflows.executions.list</code></li>
<li><code>workflows.locations.get</code></li>
<li><code>workflows.locations.list</code></li>
<li><code>workflows.operations.cancel</code></li>
<li><code>workflows.operations.get</code></li>
<li><code>workflows.operations.list</code></li>
<li><code>workflows.stepEntries.get</code></li>
<li><code>workflows.stepEntries.list</code></li>
<li><code>workflows.workflows.create</code></li>
<li><code>workflows. workflows. createTagBinding</code></li>
<li><code>workflows.workflows.delete</code></li>
<li><code>workflows. workflows. deleteTagBinding</code></li>
<li><code>workflows.workflows.get</code></li>
<li><code>workflows.workflows.list</code></li>
<li><code>workflows. workflows. listEffectiveTags</code></li>
<li><code>workflows. workflows. listRevision</code></li>
<li><code>workflows. workflows. listTagBindings</code></li>
<li><code>workflows.workflows.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Workflows Viewer
<p>( <code>roles/ workflows.viewer</code> )</p>
<p>Read-only access to workflows and related resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>workflows.callbacks.list</code></p>
<p><code>workflows.executions.get</code></p>
<p><code>workflows.executions.list</code></p>
<p><code>workflows.locations.*</code></p>
<ul>
<li><code>workflows.locations.get</code></li>
<li><code>workflows.locations.list</code></li>
</ul>
<p><code>workflows.operations.get</code></p>
<p><code>workflows.operations.list</code></p>
<p><code>workflows.stepEntries.*</code></p>
<ul>
<li><code>workflows.stepEntries.get</code></li>
<li><code>workflows.stepEntries.list</code></li>
</ul>
<p><code>workflows.workflows.get</code></p>
<p><code>workflows.workflows.list</code></p>
<p><code>workflows. workflows. listEffectiveTags</code></p>
<p><code>workflows. workflows. listRevision</code></p>
<p><code>workflows. workflows. listTagBindings</code></p></td>
</tr>
<tr class="even">
<td>Workflows Invoker
<p>( <code>roles/ workflows.invoker</code> )</p>
<p>Access to execute workflows and manage the executions using the API. Does not provide access to develop and debug workflows.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>workflows.callbacks.*</code></p>
<ul>
<li><code>workflows.callbacks.list</code></li>
<li><code>workflows.callbacks.send</code></li>
</ul>
<p><code>workflows.executions.*</code></p>
<ul>
<li><code>workflows.executions.cancel</code></li>
<li><code>workflows.executions.create</code></li>
<li><code>workflows.executions.get</code></li>
<li><code>workflows.executions.list</code></li>
</ul>
<p><code>workflows.stepEntries.*</code></p>
<ul>
<li><code>workflows.stepEntries.get</code></li>
<li><code>workflows.stepEntries.list</code></li>
</ul></td>
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
<td>Cloud Workflows Service Agent
<p>( <code>roles/ workflows.serviceAgent</code> )</p>
<p>Gives Cloud Workflows service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>container.clusters.connect</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>iam. serviceAccounts. getOpenIdToken</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## Workflows permissions

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
<td><code>workflows.callbacks.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code>roles/ workflows.invoker</code> )</p></td>
</tr>
<tr class="even">
<td><code>workflows.callbacks.send</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code>roles/ workflows.invoker</code> )</p></td>
</tr>
<tr class="odd">
<td><code>workflows.executions.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code>roles/ workflows.invoker</code> )</p></td>
</tr>
<tr class="even">
<td><code>workflows.executions.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code>roles/ workflows.invoker</code> )</p></td>
</tr>
<tr class="odd">
<td><code>workflows.executions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code>roles/ workflows.invoker</code> )</p></td>
</tr>
<tr class="even">
<td><code>workflows.executions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code>roles/ workflows.invoker</code> )</p></td>
</tr>
<tr class="odd">
<td><code>workflows.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>workflows.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>workflows.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>workflows.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>workflows.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>workflows.stepEntries.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code>roles/ workflows.invoker</code> )</p></td>
</tr>
<tr class="odd">
<td><code>workflows.stepEntries.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code>roles/ workflows.invoker</code> )</p></td>
</tr>
<tr class="even">
<td><code>workflows.workflows.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>workflows. workflows. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>workflows.workflows.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>workflows. workflows. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>workflows.workflows.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code>roles/ eventarc.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>workflows.workflows.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>workflows. workflows. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>workflows. workflows. listRevision</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>workflows. workflows. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>workflows.workflows.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p></td>
</tr>
</tbody>
</table>
