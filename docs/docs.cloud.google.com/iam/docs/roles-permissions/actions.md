---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/actions
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/actions
title: Actions roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Actions. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Actions roles

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
<td><h4 id="actions.Admin" class="role-title add-link" data-text="Actions Admin" tabindex="-1">Actions Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  actions.Admin</code> )</p>
<p>Access to edit and deploy an action</p></td>
<td><p><code dir="ltr" translate="no">actions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">actions.  agent.  claimContentProvider</code></li>
<li><code dir="ltr" translate="no">actions.agent.get</code></li>
<li><code dir="ltr" translate="no">actions.agent.update</code></li>
<li><code dir="ltr" translate="no">actions.agentVersions.create</code></li>
<li><code dir="ltr" translate="no">actions.agentVersions.delete</code></li>
<li><code dir="ltr" translate="no">actions.agentVersions.deploy</code></li>
<li><code dir="ltr" translate="no">actions.agentVersions.get</code></li>
<li><code dir="ltr" translate="no">actions.agentVersions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebase.projects.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
<tr class="even">
<td><h4 id="actions.Viewer" class="role-title add-link" data-text="Actions Viewer" tabindex="-1">Actions Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  actions.Viewer</code> )</p>
<p>Access to view an action</p></td>
<td><p><code dir="ltr" translate="no">actions.agent.get</code></p>
<p><code dir="ltr" translate="no">actions.agentVersions.get</code></p>
<p><code dir="ltr" translate="no">actions.agentVersions.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## Actions permissions

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
<td><h4 id="actions.agent.claimContentProvider" class="permission-name add-link" data-text="actions.agent.claimContentProvider" tabindex="-1"><code dir="ltr" translate="no">actions.  agent.  claimContentProvider</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="actions.agent.get" class="permission-name add-link" data-text="actions.agent.get" tabindex="-1"><code dir="ltr" translate="no">actions.agent.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Viewer">Actions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="actions.agent.update" class="permission-name add-link" data-text="actions.agent.update" tabindex="-1"><code dir="ltr" translate="no">actions.agent.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="actions.agentVersions.create" class="permission-name add-link" data-text="actions.agentVersions.create" tabindex="-1"><code dir="ltr" translate="no">actions.agentVersions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.consoleAgentEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="actions.agentVersions.delete" class="permission-name add-link" data-text="actions.agentVersions.delete" tabindex="-1"><code dir="ltr" translate="no">actions.agentVersions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="actions.agentVersions.deploy" class="permission-name add-link" data-text="actions.agentVersions.deploy" tabindex="-1"><code dir="ltr" translate="no">actions.agentVersions.deploy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="actions.agentVersions.get" class="permission-name add-link" data-text="actions.agentVersions.get" tabindex="-1"><code dir="ltr" translate="no">actions.agentVersions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Viewer">Actions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="actions.agentVersions.list" class="permission-name add-link" data-text="actions.agentVersions.list" tabindex="-1"><code dir="ltr" translate="no">actions.agentVersions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Viewer">Actions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  actions.Viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
