---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks
title: Cloud Tasks roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Tasks. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Tasks roles

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
<td><h4 id="cloudtasks.admin" class="role-title add-link" data-text="Cloud Tasks Admin Beta" tabindex="-1">Cloud Tasks Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p>Full access to queues and tasks.</p></td>
<td><p><code dir="ltr" translate="no">cloudtasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtasks.cmekConfig.get</code></li>
<li><code dir="ltr" translate="no">cloudtasks.cmekConfig.update</code></li>
<li><code dir="ltr" translate="no">cloudtasks.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudtasks.locations.list</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.create</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.delete</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.get</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.list</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.pause</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.purge</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.resume</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.update</code></li>
<li><code dir="ltr" translate="no">cloudtasks.tasks.create</code></li>
<li><code dir="ltr" translate="no">cloudtasks.tasks.delete</code></li>
<li><code dir="ltr" translate="no">cloudtasks.tasks.fullView</code></li>
<li><code dir="ltr" translate="no">cloudtasks.tasks.get</code></li>
<li><code dir="ltr" translate="no">cloudtasks.tasks.list</code></li>
<li><code dir="ltr" translate="no">cloudtasks.tasks.run</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtasks.editor" class="role-title add-link" data-text="Cloud Tasks Editor Beta" tabindex="-1">Cloud Tasks Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p>Editor role for cloudtasks</p></td>
<td><p><code dir="ltr" translate="no">cloudtasks.cmekConfig.get</code></p>
<p><code dir="ltr" translate="no">cloudtasks.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtasks.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudtasks.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtasks.queues.create</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.delete</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.get</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.list</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.pause</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.purge</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.resume</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.update</code></p>
<p><code dir="ltr" translate="no">cloudtasks.tasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtasks.tasks.create</code></li>
<li><code dir="ltr" translate="no">cloudtasks.tasks.delete</code></li>
<li><code dir="ltr" translate="no">cloudtasks.tasks.fullView</code></li>
<li><code dir="ltr" translate="no">cloudtasks.tasks.get</code></li>
<li><code dir="ltr" translate="no">cloudtasks.tasks.list</code></li>
<li><code dir="ltr" translate="no">cloudtasks.tasks.run</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtasks.viewer" class="role-title add-link" data-text="Cloud Tasks Viewer Beta" tabindex="-1">Cloud Tasks Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtasks.viewer</code> )</p>
<p>Get and list access to tasks, queues, and locations.</p></td>
<td><p><code dir="ltr" translate="no">cloudtasks.cmekConfig.get</code></p>
<p><code dir="ltr" translate="no">cloudtasks.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtasks.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudtasks.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtasks.queues.get</code></p>
<p><code dir="ltr" translate="no">cloudtasks.queues.list</code></p>
<p><code dir="ltr" translate="no">cloudtasks.tasks.fullView</code></p>
<p><code dir="ltr" translate="no">cloudtasks.tasks.get</code></p>
<p><code dir="ltr" translate="no">cloudtasks.tasks.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtasks.enqueuer" class="role-title add-link" data-text="Cloud Tasks Enqueuer Beta" tabindex="-1">Cloud Tasks Enqueuer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtasks.enqueuer</code> )</p>
<p>Access to create tasks.</p></td>
<td><p><code dir="ltr" translate="no">cloudtasks.tasks.create</code></p>
<p><code dir="ltr" translate="no">cloudtasks.tasks.fullView</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtasks.queueAdmin" class="role-title add-link" data-text="Cloud Tasks Queue Admin Beta" tabindex="-1">Cloud Tasks Queue Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p>Admin access to queues.</p></td>
<td><p><code dir="ltr" translate="no">cloudtasks.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtasks.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudtasks.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtasks.queues.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtasks.queues.create</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.delete</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.get</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.list</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.pause</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.purge</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.resume</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudtasks.queues.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtasks.taskDeleter" class="role-title add-link" data-text="Cloud Tasks Task Deleter Beta" tabindex="-1">Cloud Tasks Task Deleter <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtasks.taskDeleter</code> )</p>
<p>Access to delete tasks.</p></td>
<td><p><code dir="ltr" translate="no">cloudtasks.tasks.delete</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtasks.taskRunner" class="role-title add-link" data-text="Cloud Tasks Task Runner Beta" tabindex="-1">Cloud Tasks Task Runner <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtasks.taskRunner</code> )</p>
<p>Access to run tasks.</p></td>
<td><p><code dir="ltr" translate="no">cloudtasks.tasks.fullView</code></p>
<p><code dir="ltr" translate="no">cloudtasks.tasks.run</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="cloudtasks.serviceAgent" class="role-title add-link" data-text="Cloud Tasks Service Agent" tabindex="-1">Cloud Tasks Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtasks.serviceAgent</code> )</p>
<p>Grants Cloud Tasks Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getOpenIdToken</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p></td>
</tr>
</tbody>
</table>

## Cloud Tasks permissions

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
<td><h4 id="cloudtasks.cmekConfig.get" class="permission-name add-link" data-text="cloudtasks.cmekConfig.get" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.cmekConfig.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.viewer">Cloud Tasks Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtasks.cmekConfig.update" class="permission-name add-link" data-text="cloudtasks.cmekConfig.update" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.cmekConfig.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtasks.locations.get" class="permission-name add-link" data-text="cloudtasks.locations.get" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.viewer">Cloud Tasks Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudtasks.locations.list" class="permission-name add-link" data-text="cloudtasks.locations.list" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.viewer">Cloud Tasks Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtasks.queues.create" class="permission-name add-link" data-text="cloudtasks.queues.create" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.queues.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudtasks.queues.delete" class="permission-name add-link" data-text="cloudtasks.queues.delete" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.queues.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtasks.queues.get" class="permission-name add-link" data-text="cloudtasks.queues.get" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.queues.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.viewer">Cloud Tasks Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudtasks.queues.getIamPolicy" class="permission-name add-link" data-text="cloudtasks.queues.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.queues.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtasks.queues.list" class="permission-name add-link" data-text="cloudtasks.queues.list" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.queues.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.viewer">Cloud Tasks Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudtasks.queues.pause" class="permission-name add-link" data-text="cloudtasks.queues.pause" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.queues.pause</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtasks.queues.purge" class="permission-name add-link" data-text="cloudtasks.queues.purge" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.queues.purge</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudtasks.queues.resume" class="permission-name add-link" data-text="cloudtasks.queues.resume" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.queues.resume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtasks.queues.setIamPolicy" class="permission-name add-link" data-text="cloudtasks.queues.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.queues.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudtasks.queues.update" class="permission-name add-link" data-text="cloudtasks.queues.update" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.queues.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.queueAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtasks.tasks.create" class="permission-name add-link" data-text="cloudtasks.tasks.create" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.tasks.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.enqueuer">Cloud Tasks Enqueuer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.enqueuer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudtasks.tasks.delete" class="permission-name add-link" data-text="cloudtasks.tasks.delete" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.tasks.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.taskDeleter">Cloud Tasks Task Deleter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.taskDeleter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtasks.tasks.fullView" class="permission-name add-link" data-text="cloudtasks.tasks.fullView" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.tasks.fullView</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.viewer">Cloud Tasks Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.enqueuer">Cloud Tasks Enqueuer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.enqueuer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.taskRunner">Cloud Tasks Task Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.taskRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasemods.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudtasks.tasks.get" class="permission-name add-link" data-text="cloudtasks.tasks.get" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.tasks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.viewer">Cloud Tasks Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtasks.tasks.list" class="permission-name add-link" data-text="cloudtasks.tasks.list" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.tasks.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.viewer">Cloud Tasks Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtasks.tasks.run" class="permission-name add-link" data-text="cloudtasks.tasks.run" tabindex="-1"><code dir="ltr" translate="no">cloudtasks.tasks.run</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.taskRunner">Cloud Tasks Task Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtasks.taskRunner</code> )</p></td>
</tr>
</tbody>
</table>
