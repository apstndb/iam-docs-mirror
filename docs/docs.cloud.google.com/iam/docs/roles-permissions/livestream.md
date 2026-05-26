---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/livestream
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/livestream
title: Live Stream roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Live Stream. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Live Stream roles

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
<td><h4 id="livestream.admin" class="role-title add-link" data-text="Live Stream Admin" tabindex="-1">Live Stream Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p>Admin role for livestream</p></td>
<td><p><code dir="ltr" translate="no">livestream.*</code></p>
<ul>
<li><code dir="ltr" translate="no">livestream.assets.create</code></li>
<li><code dir="ltr" translate="no">livestream.assets.delete</code></li>
<li><code dir="ltr" translate="no">livestream.assets.get</code></li>
<li><code dir="ltr" translate="no">livestream.assets.list</code></li>
<li><code dir="ltr" translate="no">livestream.channels.create</code></li>
<li><code dir="ltr" translate="no">livestream.  channels.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">livestream.channels.delete</code></li>
<li><code dir="ltr" translate="no">livestream.  channels.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">livestream.channels.get</code></li>
<li><code dir="ltr" translate="no">livestream.channels.list</code></li>
<li><code dir="ltr" translate="no">livestream.  channels.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">livestream.  channels.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">livestream.channels.start</code></li>
<li><code dir="ltr" translate="no">livestream.channels.stop</code></li>
<li><code dir="ltr" translate="no">livestream.channels.update</code></li>
<li><code dir="ltr" translate="no">livestream.clips.create</code></li>
<li><code dir="ltr" translate="no">livestream.clips.delete</code></li>
<li><code dir="ltr" translate="no">livestream.clips.get</code></li>
<li><code dir="ltr" translate="no">livestream.clips.list</code></li>
<li><code dir="ltr" translate="no">livestream.dvrSessions.create</code></li>
<li><code dir="ltr" translate="no">livestream.dvrSessions.delete</code></li>
<li><code dir="ltr" translate="no">livestream.dvrSessions.get</code></li>
<li><code dir="ltr" translate="no">livestream.dvrSessions.list</code></li>
<li><code dir="ltr" translate="no">livestream.dvrSessions.update</code></li>
<li><code dir="ltr" translate="no">livestream.events.create</code></li>
<li><code dir="ltr" translate="no">livestream.events.delete</code></li>
<li><code dir="ltr" translate="no">livestream.events.get</code></li>
<li><code dir="ltr" translate="no">livestream.events.list</code></li>
<li><code dir="ltr" translate="no">livestream.inputs.create</code></li>
<li><code dir="ltr" translate="no">livestream.  inputs.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">livestream.inputs.delete</code></li>
<li><code dir="ltr" translate="no">livestream.  inputs.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">livestream.inputs.get</code></li>
<li><code dir="ltr" translate="no">livestream.inputs.list</code></li>
<li><code dir="ltr" translate="no">livestream.  inputs.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">livestream.  inputs.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">livestream.inputs.update</code></li>
<li><code dir="ltr" translate="no">livestream.locations.get</code></li>
<li><code dir="ltr" translate="no">livestream.locations.list</code></li>
<li><code dir="ltr" translate="no">livestream.operations.cancel</code></li>
<li><code dir="ltr" translate="no">livestream.operations.delete</code></li>
<li><code dir="ltr" translate="no">livestream.operations.get</code></li>
<li><code dir="ltr" translate="no">livestream.operations.list</code></li>
<li><code dir="ltr" translate="no">livestream.  pools.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">livestream.  pools.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">livestream.pools.get</code></li>
<li><code dir="ltr" translate="no">livestream.  pools.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">livestream.  pools.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">livestream.pools.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.editor" class="role-title add-link" data-text="Live Stream Editor" tabindex="-1">Live Stream Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p>Full access to Live Stream resources.</p></td>
<td><p><code dir="ltr" translate="no">livestream.*</code></p>
<ul>
<li><code dir="ltr" translate="no">livestream.assets.create</code></li>
<li><code dir="ltr" translate="no">livestream.assets.delete</code></li>
<li><code dir="ltr" translate="no">livestream.assets.get</code></li>
<li><code dir="ltr" translate="no">livestream.assets.list</code></li>
<li><code dir="ltr" translate="no">livestream.channels.create</code></li>
<li><code dir="ltr" translate="no">livestream.  channels.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">livestream.channels.delete</code></li>
<li><code dir="ltr" translate="no">livestream.  channels.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">livestream.channels.get</code></li>
<li><code dir="ltr" translate="no">livestream.channels.list</code></li>
<li><code dir="ltr" translate="no">livestream.  channels.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">livestream.  channels.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">livestream.channels.start</code></li>
<li><code dir="ltr" translate="no">livestream.channels.stop</code></li>
<li><code dir="ltr" translate="no">livestream.channels.update</code></li>
<li><code dir="ltr" translate="no">livestream.clips.create</code></li>
<li><code dir="ltr" translate="no">livestream.clips.delete</code></li>
<li><code dir="ltr" translate="no">livestream.clips.get</code></li>
<li><code dir="ltr" translate="no">livestream.clips.list</code></li>
<li><code dir="ltr" translate="no">livestream.dvrSessions.create</code></li>
<li><code dir="ltr" translate="no">livestream.dvrSessions.delete</code></li>
<li><code dir="ltr" translate="no">livestream.dvrSessions.get</code></li>
<li><code dir="ltr" translate="no">livestream.dvrSessions.list</code></li>
<li><code dir="ltr" translate="no">livestream.dvrSessions.update</code></li>
<li><code dir="ltr" translate="no">livestream.events.create</code></li>
<li><code dir="ltr" translate="no">livestream.events.delete</code></li>
<li><code dir="ltr" translate="no">livestream.events.get</code></li>
<li><code dir="ltr" translate="no">livestream.events.list</code></li>
<li><code dir="ltr" translate="no">livestream.inputs.create</code></li>
<li><code dir="ltr" translate="no">livestream.  inputs.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">livestream.inputs.delete</code></li>
<li><code dir="ltr" translate="no">livestream.  inputs.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">livestream.inputs.get</code></li>
<li><code dir="ltr" translate="no">livestream.inputs.list</code></li>
<li><code dir="ltr" translate="no">livestream.  inputs.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">livestream.  inputs.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">livestream.inputs.update</code></li>
<li><code dir="ltr" translate="no">livestream.locations.get</code></li>
<li><code dir="ltr" translate="no">livestream.locations.list</code></li>
<li><code dir="ltr" translate="no">livestream.operations.cancel</code></li>
<li><code dir="ltr" translate="no">livestream.operations.delete</code></li>
<li><code dir="ltr" translate="no">livestream.operations.get</code></li>
<li><code dir="ltr" translate="no">livestream.operations.list</code></li>
<li><code dir="ltr" translate="no">livestream.  pools.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">livestream.  pools.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">livestream.pools.get</code></li>
<li><code dir="ltr" translate="no">livestream.  pools.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">livestream.  pools.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">livestream.pools.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.viewer" class="role-title add-link" data-text="Live Stream Viewer" tabindex="-1">Live Stream Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p>Read access to Live Stream resources.</p></td>
<td><p><code dir="ltr" translate="no">livestream.assets.get</code></p>
<p><code dir="ltr" translate="no">livestream.assets.list</code></p>
<p><code dir="ltr" translate="no">livestream.channels.get</code></p>
<p><code dir="ltr" translate="no">livestream.channels.list</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.clips.get</code></p>
<p><code dir="ltr" translate="no">livestream.clips.list</code></p>
<p><code dir="ltr" translate="no">livestream.dvrSessions.get</code></p>
<p><code dir="ltr" translate="no">livestream.dvrSessions.list</code></p>
<p><code dir="ltr" translate="no">livestream.events.get</code></p>
<p><code dir="ltr" translate="no">livestream.events.list</code></p>
<p><code dir="ltr" translate="no">livestream.inputs.get</code></p>
<p><code dir="ltr" translate="no">livestream.inputs.list</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">livestream.locations.get</code></li>
<li><code dir="ltr" translate="no">livestream.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">livestream.operations.get</code></p>
<p><code dir="ltr" translate="no">livestream.operations.list</code></p>
<p><code dir="ltr" translate="no">livestream.pools.get</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  listTagBindings</code></p>
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
<td><h4 id="livestream.serviceAgent" class="role-title add-link" data-text="Live Stream Service Agent" tabindex="-1">Live Stream Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  livestream.serviceAgent</code> )</p>
<p>Uploads media files to customer Cloud Storage buckets.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Live Stream permissions

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
<td><h4 id="livestream.assets.create" class="permission-name add-link" data-text="livestream.assets.create" tabindex="-1"><code dir="ltr" translate="no">livestream.assets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.assets.delete" class="permission-name add-link" data-text="livestream.assets.delete" tabindex="-1"><code dir="ltr" translate="no">livestream.assets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.assets.get" class="permission-name add-link" data-text="livestream.assets.get" tabindex="-1"><code dir="ltr" translate="no">livestream.assets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.assets.list" class="permission-name add-link" data-text="livestream.assets.list" tabindex="-1"><code dir="ltr" translate="no">livestream.assets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.channels.create" class="permission-name add-link" data-text="livestream.channels.create" tabindex="-1"><code dir="ltr" translate="no">livestream.channels.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.channels.createTagBinding" class="permission-name add-link" data-text="livestream.channels.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">livestream.  channels.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.channels.delete" class="permission-name add-link" data-text="livestream.channels.delete" tabindex="-1"><code dir="ltr" translate="no">livestream.channels.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.channels.deleteTagBinding" class="permission-name add-link" data-text="livestream.channels.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">livestream.  channels.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.channels.get" class="permission-name add-link" data-text="livestream.channels.get" tabindex="-1"><code dir="ltr" translate="no">livestream.channels.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.channels.list" class="permission-name add-link" data-text="livestream.channels.list" tabindex="-1"><code dir="ltr" translate="no">livestream.channels.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.channels.listEffectiveTags" class="permission-name add-link" data-text="livestream.channels.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">livestream.  channels.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.channels.listTagBindings" class="permission-name add-link" data-text="livestream.channels.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">livestream.  channels.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.channels.start" class="permission-name add-link" data-text="livestream.channels.start" tabindex="-1"><code dir="ltr" translate="no">livestream.channels.start</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.channels.stop" class="permission-name add-link" data-text="livestream.channels.stop" tabindex="-1"><code dir="ltr" translate="no">livestream.channels.stop</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.channels.update" class="permission-name add-link" data-text="livestream.channels.update" tabindex="-1"><code dir="ltr" translate="no">livestream.channels.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.clips.create" class="permission-name add-link" data-text="livestream.clips.create" tabindex="-1"><code dir="ltr" translate="no">livestream.clips.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.clips.delete" class="permission-name add-link" data-text="livestream.clips.delete" tabindex="-1"><code dir="ltr" translate="no">livestream.clips.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.clips.get" class="permission-name add-link" data-text="livestream.clips.get" tabindex="-1"><code dir="ltr" translate="no">livestream.clips.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.clips.list" class="permission-name add-link" data-text="livestream.clips.list" tabindex="-1"><code dir="ltr" translate="no">livestream.clips.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.dvrSessions.create" class="permission-name add-link" data-text="livestream.dvrSessions.create" tabindex="-1"><code dir="ltr" translate="no">livestream.dvrSessions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.dvrSessions.delete" class="permission-name add-link" data-text="livestream.dvrSessions.delete" tabindex="-1"><code dir="ltr" translate="no">livestream.dvrSessions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.dvrSessions.get" class="permission-name add-link" data-text="livestream.dvrSessions.get" tabindex="-1"><code dir="ltr" translate="no">livestream.dvrSessions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.dvrSessions.list" class="permission-name add-link" data-text="livestream.dvrSessions.list" tabindex="-1"><code dir="ltr" translate="no">livestream.dvrSessions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.dvrSessions.update" class="permission-name add-link" data-text="livestream.dvrSessions.update" tabindex="-1"><code dir="ltr" translate="no">livestream.dvrSessions.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.events.create" class="permission-name add-link" data-text="livestream.events.create" tabindex="-1"><code dir="ltr" translate="no">livestream.events.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.events.delete" class="permission-name add-link" data-text="livestream.events.delete" tabindex="-1"><code dir="ltr" translate="no">livestream.events.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.events.get" class="permission-name add-link" data-text="livestream.events.get" tabindex="-1"><code dir="ltr" translate="no">livestream.events.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.events.list" class="permission-name add-link" data-text="livestream.events.list" tabindex="-1"><code dir="ltr" translate="no">livestream.events.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.inputs.create" class="permission-name add-link" data-text="livestream.inputs.create" tabindex="-1"><code dir="ltr" translate="no">livestream.inputs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.inputs.createTagBinding" class="permission-name add-link" data-text="livestream.inputs.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">livestream.  inputs.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.inputs.delete" class="permission-name add-link" data-text="livestream.inputs.delete" tabindex="-1"><code dir="ltr" translate="no">livestream.inputs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.inputs.deleteTagBinding" class="permission-name add-link" data-text="livestream.inputs.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">livestream.  inputs.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.inputs.get" class="permission-name add-link" data-text="livestream.inputs.get" tabindex="-1"><code dir="ltr" translate="no">livestream.inputs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.inputs.list" class="permission-name add-link" data-text="livestream.inputs.list" tabindex="-1"><code dir="ltr" translate="no">livestream.inputs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.inputs.listEffectiveTags" class="permission-name add-link" data-text="livestream.inputs.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">livestream.  inputs.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.inputs.listTagBindings" class="permission-name add-link" data-text="livestream.inputs.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">livestream.  inputs.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.inputs.update" class="permission-name add-link" data-text="livestream.inputs.update" tabindex="-1"><code dir="ltr" translate="no">livestream.inputs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.locations.get" class="permission-name add-link" data-text="livestream.locations.get" tabindex="-1"><code dir="ltr" translate="no">livestream.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.locations.list" class="permission-name add-link" data-text="livestream.locations.list" tabindex="-1"><code dir="ltr" translate="no">livestream.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.operations.cancel" class="permission-name add-link" data-text="livestream.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">livestream.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.operations.delete" class="permission-name add-link" data-text="livestream.operations.delete" tabindex="-1"><code dir="ltr" translate="no">livestream.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.operations.get" class="permission-name add-link" data-text="livestream.operations.get" tabindex="-1"><code dir="ltr" translate="no">livestream.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.operations.list" class="permission-name add-link" data-text="livestream.operations.list" tabindex="-1"><code dir="ltr" translate="no">livestream.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.pools.createTagBinding" class="permission-name add-link" data-text="livestream.pools.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">livestream.  pools.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.pools.deleteTagBinding" class="permission-name add-link" data-text="livestream.pools.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">livestream.  pools.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.pools.get" class="permission-name add-link" data-text="livestream.pools.get" tabindex="-1"><code dir="ltr" translate="no">livestream.pools.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.pools.listEffectiveTags" class="permission-name add-link" data-text="livestream.pools.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">livestream.  pools.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="livestream.pools.listTagBindings" class="permission-name add-link" data-text="livestream.pools.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">livestream.  pools.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="livestream.pools.update" class="permission-name add-link" data-text="livestream.pools.update" tabindex="-1"><code dir="ltr" translate="no">livestream.pools.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  livestream.editor</code> )</p></td>
</tr>
</tbody>
</table>
