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
<td><h4 id="workflows.admin" class="role-title add-link" data-text="Workflows Admin" tabindex="-1">Workflows Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p>Full access to workflows and related resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workflows.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workflows.callbacks.list</code></li>
<li><code dir="ltr" translate="no">workflows.callbacks.send</code></li>
<li><code dir="ltr" translate="no">workflows.executions.cancel</code></li>
<li><code dir="ltr" translate="no">workflows.executions.create</code></li>
<li><code dir="ltr" translate="no">workflows.executions.get</code></li>
<li><code dir="ltr" translate="no">workflows.executions.list</code></li>
<li><code dir="ltr" translate="no">workflows.locations.get</code></li>
<li><code dir="ltr" translate="no">workflows.locations.list</code></li>
<li><code dir="ltr" translate="no">workflows.operations.cancel</code></li>
<li><code dir="ltr" translate="no">workflows.operations.get</code></li>
<li><code dir="ltr" translate="no">workflows.operations.list</code></li>
<li><code dir="ltr" translate="no">workflows.stepEntries.get</code></li>
<li><code dir="ltr" translate="no">workflows.stepEntries.list</code></li>
<li><code dir="ltr" translate="no">workflows.workflows.create</code></li>
<li><code dir="ltr" translate="no">workflows.  workflows.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">workflows.workflows.delete</code></li>
<li><code dir="ltr" translate="no">workflows.  workflows.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">workflows.workflows.get</code></li>
<li><code dir="ltr" translate="no">workflows.workflows.list</code></li>
<li><code dir="ltr" translate="no">workflows.  workflows.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">workflows.  workflows.  listRevision</code></li>
<li><code dir="ltr" translate="no">workflows.  workflows.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">workflows.workflows.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="workflows.editor" class="role-title add-link" data-text="Workflows Editor" tabindex="-1">Workflows Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p>Read and write access to workflows and related resources, including development and debugging of workflows.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workflows.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workflows.callbacks.list</code></li>
<li><code dir="ltr" translate="no">workflows.callbacks.send</code></li>
<li><code dir="ltr" translate="no">workflows.executions.cancel</code></li>
<li><code dir="ltr" translate="no">workflows.executions.create</code></li>
<li><code dir="ltr" translate="no">workflows.executions.get</code></li>
<li><code dir="ltr" translate="no">workflows.executions.list</code></li>
<li><code dir="ltr" translate="no">workflows.locations.get</code></li>
<li><code dir="ltr" translate="no">workflows.locations.list</code></li>
<li><code dir="ltr" translate="no">workflows.operations.cancel</code></li>
<li><code dir="ltr" translate="no">workflows.operations.get</code></li>
<li><code dir="ltr" translate="no">workflows.operations.list</code></li>
<li><code dir="ltr" translate="no">workflows.stepEntries.get</code></li>
<li><code dir="ltr" translate="no">workflows.stepEntries.list</code></li>
<li><code dir="ltr" translate="no">workflows.workflows.create</code></li>
<li><code dir="ltr" translate="no">workflows.  workflows.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">workflows.workflows.delete</code></li>
<li><code dir="ltr" translate="no">workflows.  workflows.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">workflows.workflows.get</code></li>
<li><code dir="ltr" translate="no">workflows.workflows.list</code></li>
<li><code dir="ltr" translate="no">workflows.  workflows.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">workflows.  workflows.  listRevision</code></li>
<li><code dir="ltr" translate="no">workflows.  workflows.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">workflows.workflows.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="workflows.viewer" class="role-title add-link" data-text="Workflows Viewer" tabindex="-1">Workflows Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p>Read-only access to workflows and related resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workflows.callbacks.list</code></p>
<p><code dir="ltr" translate="no">workflows.executions.get</code></p>
<p><code dir="ltr" translate="no">workflows.executions.list</code></p>
<p><code dir="ltr" translate="no">workflows.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workflows.locations.get</code></li>
<li><code dir="ltr" translate="no">workflows.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">workflows.operations.get</code></p>
<p><code dir="ltr" translate="no">workflows.operations.list</code></p>
<p><code dir="ltr" translate="no">workflows.stepEntries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workflows.stepEntries.get</code></li>
<li><code dir="ltr" translate="no">workflows.stepEntries.list</code></li>
</ul>
<p><code dir="ltr" translate="no">workflows.workflows.get</code></p>
<p><code dir="ltr" translate="no">workflows.workflows.list</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  listRevision</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  listTagBindings</code></p></td>
</tr>
<tr class="even">
<td><h4 id="workflows.invoker" class="role-title add-link" data-text="Workflows Invoker" tabindex="-1">Workflows Invoker</h4>
<p>( <code dir="ltr" translate="no">roles/  workflows.invoker</code> )</p>
<p>Access to execute workflows and manage the executions using the API. Does not provide access to develop and debug workflows.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workflows.callbacks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workflows.callbacks.list</code></li>
<li><code dir="ltr" translate="no">workflows.callbacks.send</code></li>
</ul>
<p><code dir="ltr" translate="no">workflows.executions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workflows.executions.cancel</code></li>
<li><code dir="ltr" translate="no">workflows.executions.create</code></li>
<li><code dir="ltr" translate="no">workflows.executions.get</code></li>
<li><code dir="ltr" translate="no">workflows.executions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">workflows.stepEntries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workflows.stepEntries.get</code></li>
<li><code dir="ltr" translate="no">workflows.stepEntries.list</code></li>
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
<td><h4 id="workflows.serviceAgent" class="role-title add-link" data-text="Cloud Workflows Service Agent" tabindex="-1">Cloud Workflows Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  workflows.serviceAgent</code> )</p>
<p>Gives Cloud Workflows service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">container.clusters.connect</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getOpenIdToken</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
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
<td><h4 id="workflows.callbacks.list" class="permission-name add-link" data-text="workflows.callbacks.list" tabindex="-1"><code dir="ltr" translate="no">workflows.callbacks.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.invoker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workflows.callbacks.send" class="permission-name add-link" data-text="workflows.callbacks.send" tabindex="-1"><code dir="ltr" translate="no">workflows.callbacks.send</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.invoker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workflows.executions.cancel" class="permission-name add-link" data-text="workflows.executions.cancel" tabindex="-1"><code dir="ltr" translate="no">workflows.executions.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.invoker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workflows.executions.create" class="permission-name add-link" data-text="workflows.executions.create" tabindex="-1"><code dir="ltr" translate="no">workflows.executions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.invoker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workflows.executions.get" class="permission-name add-link" data-text="workflows.executions.get" tabindex="-1"><code dir="ltr" translate="no">workflows.executions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.invoker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workflows.executions.list" class="permission-name add-link" data-text="workflows.executions.list" tabindex="-1"><code dir="ltr" translate="no">workflows.executions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.invoker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workflows.locations.get" class="permission-name add-link" data-text="workflows.locations.get" tabindex="-1"><code dir="ltr" translate="no">workflows.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workflows.locations.list" class="permission-name add-link" data-text="workflows.locations.list" tabindex="-1"><code dir="ltr" translate="no">workflows.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workflows.operations.cancel" class="permission-name add-link" data-text="workflows.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">workflows.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workflows.operations.get" class="permission-name add-link" data-text="workflows.operations.get" tabindex="-1"><code dir="ltr" translate="no">workflows.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="workflows.operations.list" class="permission-name add-link" data-text="workflows.operations.list" tabindex="-1"><code dir="ltr" translate="no">workflows.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workflows.stepEntries.get" class="permission-name add-link" data-text="workflows.stepEntries.get" tabindex="-1"><code dir="ltr" translate="no">workflows.stepEntries.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.invoker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workflows.stepEntries.list" class="permission-name add-link" data-text="workflows.stepEntries.list" tabindex="-1"><code dir="ltr" translate="no">workflows.stepEntries.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.invoker</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workflows.workflows.create" class="permission-name add-link" data-text="workflows.workflows.create" tabindex="-1"><code dir="ltr" translate="no">workflows.workflows.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="workflows.workflows.createTagBinding" class="permission-name add-link" data-text="workflows.workflows.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">workflows.  workflows.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workflows.workflows.delete" class="permission-name add-link" data-text="workflows.workflows.delete" tabindex="-1"><code dir="ltr" translate="no">workflows.workflows.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="workflows.workflows.deleteTagBinding" class="permission-name add-link" data-text="workflows.workflows.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">workflows.  workflows.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workflows.workflows.get" class="permission-name add-link" data-text="workflows.workflows.get" tabindex="-1"><code dir="ltr" translate="no">workflows.workflows.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  eventarc.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="workflows.workflows.list" class="permission-name add-link" data-text="workflows.workflows.list" tabindex="-1"><code dir="ltr" translate="no">workflows.workflows.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workflows.workflows.listEffectiveTags" class="permission-name add-link" data-text="workflows.workflows.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">workflows.  workflows.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workflows.workflows.listRevision" class="permission-name add-link" data-text="workflows.workflows.listRevision" tabindex="-1"><code dir="ltr" translate="no">workflows.  workflows.  listRevision</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workflows.workflows.listTagBindings" class="permission-name add-link" data-text="workflows.workflows.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">workflows.  workflows.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workflows.workflows.update" class="permission-name add-link" data-text="workflows.workflows.update" tabindex="-1"><code dir="ltr" translate="no">workflows.workflows.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workflows.editor</code> )</p></td>
</tr>
</tbody>
</table>
