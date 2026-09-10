---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer
title: Storage Transfer Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Storage Transfer Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Storage Transfer Service roles

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
<td><h4 id="storagetransfer.admin" class="role-title add-link" data-text="Storage Transfer Admin" tabindex="-1">Storage Transfer Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p>Create, update and manage transfer jobs and operations.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storagetransfer.  agentpools.  create</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  agentpools.  delete</code></li>
<li><code dir="ltr" translate="no">storagetransfer.agentpools.get</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  agentpools.  list</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  agentpools.  report</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  agentpools.  update</code></li>
<li><code dir="ltr" translate="no">storagetransfer.jobs.create</code></li>
<li><code dir="ltr" translate="no">storagetransfer.jobs.delete</code></li>
<li><code dir="ltr" translate="no">storagetransfer.jobs.get</code></li>
<li><code dir="ltr" translate="no">storagetransfer.jobs.list</code></li>
<li><code dir="ltr" translate="no">storagetransfer.jobs.run</code></li>
<li><code dir="ltr" translate="no">storagetransfer.jobs.update</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  operations.  assign</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">storagetransfer.operations.get</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  operations.  list</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  operations.  pause</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  operations.  report</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  operations.  resume</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  projects.  getServiceAccount</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storagetransfer.viewer" class="role-title add-link" data-text="Storage Transfer Viewer" tabindex="-1">Storage Transfer Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  storagetransfer.viewer</code> )</p>
<p>Read access to storage transfer jobs and operations.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.agentpools.get</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  agentpools.  list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.jobs.get</code></p>
<p><code dir="ltr" translate="no">storagetransfer.jobs.list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.operations.get</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  operations.  list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  projects.  getServiceAccount</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="storagetransfer.transferAgent" class="role-title add-link" data-text="Storage Transfer Agent" tabindex="-1">Storage Transfer Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  storagetransfer.transferAgent</code> )</p>
<p>Perform transfers from an agent.</p></td>
<td><p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.create</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  agentpools.  report</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  operations.  assign</code></p>
<p><code dir="ltr" translate="no">storagetransfer.operations.get</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  operations.  report</code></p></td>
</tr>
<tr class="even">
<td><h4 id="storagetransfer.user" class="role-title add-link" data-text="Storage Transfer User" tabindex="-1">Storage Transfer User</h4>
<p>( <code dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p>
<p>Create and update storage transfer jobs and operations.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  agentpools.  create</code></p>
<p><code dir="ltr" translate="no">storagetransfer.agentpools.get</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  agentpools.  list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  agentpools.  report</code></p>
<p><code dir="ltr" translate="no">storagetransfer.  agentpools.  update</code></p>
<p><code dir="ltr" translate="no">storagetransfer.jobs.create</code></p>
<p><code dir="ltr" translate="no">storagetransfer.jobs.get</code></p>
<p><code dir="ltr" translate="no">storagetransfer.jobs.list</code></p>
<p><code dir="ltr" translate="no">storagetransfer.jobs.run</code></p>
<p><code dir="ltr" translate="no">storagetransfer.jobs.update</code></p>
<p><code dir="ltr" translate="no">storagetransfer.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storagetransfer.  operations.  assign</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">storagetransfer.operations.get</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  operations.  list</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  operations.  pause</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  operations.  report</code></li>
<li><code dir="ltr" translate="no">storagetransfer.  operations.  resume</code></li>
</ul>
<p><code dir="ltr" translate="no">storagetransfer.  projects.  getServiceAccount</code></p></td>
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
<td><h4 id="storagetransfer.serviceAgent" class="role-title add-link" data-text="Storage Transfer Service Agent" tabindex="-1">Storage Transfer Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  storagetransfer.serviceAgent</code> )</p>
<p>Grants Storage Transfer Service Agent permissions required to run transfers</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.update</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.create</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.delete</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.update</code></p></td>
</tr>
</tbody>
</table>

## Storage Transfer Service permissions

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
<td><h4 id="storagetransfer.agentpools.create" class="permission-name add-link" data-text="storagetransfer.agentpools.create" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.  agentpools.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storagetransfer.agentpools.delete" class="permission-name add-link" data-text="storagetransfer.agentpools.delete" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.  agentpools.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storagetransfer.agentpools.get" class="permission-name add-link" data-text="storagetransfer.agentpools.get" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.agentpools.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.viewer">Storage Transfer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storagetransfer.agentpools.list" class="permission-name add-link" data-text="storagetransfer.agentpools.list" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.  agentpools.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.viewer">Storage Transfer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storagetransfer.agentpools.report" class="permission-name add-link" data-text="storagetransfer.agentpools.report" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.  agentpools.  report</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.transferAgent">Storage Transfer Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.transferAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storagetransfer.agentpools.update" class="permission-name add-link" data-text="storagetransfer.agentpools.update" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.  agentpools.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storagetransfer.jobs.create" class="permission-name add-link" data-text="storagetransfer.jobs.create" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.jobs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storagetransfer.jobs.delete" class="permission-name add-link" data-text="storagetransfer.jobs.delete" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.jobs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storagetransfer.jobs.get" class="permission-name add-link" data-text="storagetransfer.jobs.get" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.jobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.viewer">Storage Transfer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storagetransfer.jobs.list" class="permission-name add-link" data-text="storagetransfer.jobs.list" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.jobs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.viewer">Storage Transfer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storagetransfer.jobs.run" class="permission-name add-link" data-text="storagetransfer.jobs.run" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.jobs.run</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storagetransfer.jobs.update" class="permission-name add-link" data-text="storagetransfer.jobs.update" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.jobs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storagetransfer.operations.assign" class="permission-name add-link" data-text="storagetransfer.operations.assign" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.  operations.  assign</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.transferAgent">Storage Transfer Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.transferAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storagetransfer.operations.cancel" class="permission-name add-link" data-text="storagetransfer.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storagetransfer.operations.get" class="permission-name add-link" data-text="storagetransfer.operations.get" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.viewer">Storage Transfer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.transferAgent">Storage Transfer Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.transferAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storagetransfer.operations.list" class="permission-name add-link" data-text="storagetransfer.operations.list" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.viewer">Storage Transfer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storagetransfer.operations.pause" class="permission-name add-link" data-text="storagetransfer.operations.pause" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.  operations.  pause</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storagetransfer.operations.report" class="permission-name add-link" data-text="storagetransfer.operations.report" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.  operations.  report</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.transferAgent">Storage Transfer Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.transferAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storagetransfer.operations.resume" class="permission-name add-link" data-text="storagetransfer.operations.resume" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.  operations.  resume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storagetransfer.projects.getServiceAccount" class="permission-name add-link" data-text="storagetransfer.projects.getServiceAccount" tabindex="-1"><code dir="ltr" translate="no">storagetransfer.  projects.  getServiceAccount</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.viewer">Storage Transfer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storagetransfer.user</code> )</p></td>
</tr>
</tbody>
</table>
