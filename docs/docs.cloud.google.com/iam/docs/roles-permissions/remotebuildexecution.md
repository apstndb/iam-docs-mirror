---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution
title: Remote Build Execution roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Remote Build Execution. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Remote Build Execution roles

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
<td><h4 id="remotebuildexecution.admin" class="role-title add-link" data-text="Remotebuildexecution Admin Beta" tabindex="-1">Remotebuildexecution Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p>Admin role for remotebuildexecution</p></td>
<td><p><code dir="ltr" translate="no">remotebuildexecution.  actions.  create</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  actions.  delete</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  actions.  get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  actions.  update</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  blobs.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  botsessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  botsessions.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  botsessions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  instances.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  instances.  delete</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  instances.  get</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  instances.  list</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  instances.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  logstreams.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  get</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  workerpools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  delete</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  get</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  list</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.editor" class="role-title add-link" data-text="Remotebuildexecution Editor Beta" tabindex="-1">Remotebuildexecution Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p>Editor role for remotebuildexecution</p></td>
<td><p><code dir="ltr" translate="no">remotebuildexecution.  actions.  create</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  actions.  delete</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  actions.  get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  actions.  update</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  blobs.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  botsessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  botsessions.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  botsessions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  instances.  create</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  instances.  get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  instances.  list</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  instances.  update</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  logstreams.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  get</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  create</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  list</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.viewer" class="role-title add-link" data-text="Remotebuildexecution Viewer Beta" tabindex="-1">Remotebuildexecution Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  remotebuildexecution.viewer</code> )</p>
<p>Viewer role for remotebuildexecution</p></td>
<td><p><code dir="ltr" translate="no">remotebuildexecution.  actions.  get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  instances.  get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  instances.  list</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.actionCacheWriter" class="role-title add-link" data-text="Remote Build Execution Action Cache Writer Beta" tabindex="-1">Remote Build Execution Action Cache Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  remotebuildexecution.actionCacheWriter</code> )</p>
<p>Remote Build Execution Action Cache Writer</p></td>
<td><p><code dir="ltr" translate="no">remotebuildexecution.  actions.  set</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  blobs.  create</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.artifactAdmin" class="role-title add-link" data-text="Remote Build Execution Artifact Admin Beta" tabindex="-1">Remote Build Execution Artifact Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  remotebuildexecution.artifactAdmin</code> )</p>
<p>Remote Build Execution Artifact Admin</p></td>
<td><p><code dir="ltr" translate="no">remotebuildexecution.  actions.  create</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  actions.  delete</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  actions.  get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  blobs.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  logstreams.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  get</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.artifactCreator" class="role-title add-link" data-text="Remote Build Execution Artifact Creator Beta" tabindex="-1">Remote Build Execution Artifact Creator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  remotebuildexecution.artifactCreator</code> )</p>
<p>Remote Build Execution Artifact Creator</p></td>
<td><p><code dir="ltr" translate="no">remotebuildexecution.  actions.  create</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  actions.  get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  blobs.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  logstreams.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  get</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.artifactViewer" class="role-title add-link" data-text="Remote Build Execution Artifact Viewer Beta" tabindex="-1">Remote Build Execution Artifact Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  remotebuildexecution.artifactViewer</code> )</p>
<p>Remote Build Execution Artifact Viewer</p></td>
<td><p><code dir="ltr" translate="no">remotebuildexecution.  actions.  get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.configurationAdmin" class="role-title add-link" data-text="Remote Build Execution Configuration Admin Beta" tabindex="-1">Remote Build Execution Configuration Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  remotebuildexecution.configurationAdmin</code> )</p>
<p>Remote Build Execution Configuration Admin</p></td>
<td><p><code dir="ltr" translate="no">remotebuildexecution.  instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  instances.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  instances.  delete</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  instances.  get</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  instances.  list</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  instances.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  workerpools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  delete</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  get</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  list</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.configurationViewer" class="role-title add-link" data-text="Remote Build Execution Configuration Viewer Beta" tabindex="-1">Remote Build Execution Configuration Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  remotebuildexecution.configurationViewer</code> )</p>
<p>Remote Build Execution Configuration Viewer</p></td>
<td><p><code dir="ltr" translate="no">remotebuildexecution.  instances.  get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  instances.  list</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  get</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.logstreamWriter" class="role-title add-link" data-text="Remote Build Execution Logstream Writer Beta" tabindex="-1">Remote Build Execution Logstream Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  remotebuildexecution.logstreamWriter</code> )</p>
<p>Remote Build Execution Logstream Writer</p></td>
<td><p><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  create</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.reservationAdmin" class="role-title add-link" data-text="Remote Build Execution Reservation Admin Beta" tabindex="-1">Remote Build Execution Reservation Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  remotebuildexecution.reservationAdmin</code> )</p>
<p>Remote Build Execution Reservation Admin</p></td>
<td><p><code dir="ltr" translate="no">remotebuildexecution.  actions.  create</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  actions.  delete</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  actions.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.worker" class="role-title add-link" data-text="Remote Build Execution Worker Beta" tabindex="-1">Remote Build Execution Worker <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  remotebuildexecution.worker</code> )</p>
<p>Remote Build Execution Worker</p></td>
<td><p><code dir="ltr" translate="no">remotebuildexecution.  actions.  update</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  blobs.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  botsessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  botsessions.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  botsessions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  create</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  update</code></p></td>
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
<td><h4 id="remotebuildexecution.serviceAgent" class="role-title add-link" data-text="Remote Build Execution Service Agent" tabindex="-1">Remote Build Execution Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  remotebuildexecution.serviceAgent</code> )</p>
<p>Gives Remote Build Execution service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">remotebuildexecution.  actions.  update</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  blobs.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  botsessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">remotebuildexecution.  botsessions.  create</code></li>
<li><code dir="ltr" translate="no">remotebuildexecution.  botsessions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  create</code></p>
<p><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  update</code></p></td>
</tr>
</tbody>
</table>

## Remote Build Execution permissions

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
<td><h4 id="remotebuildexecution.actions.create" class="permission-name add-link" data-text="remotebuildexecution.actions.create" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  actions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.reservationAdmin">Remote Build Execution Reservation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.reservationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.actions.delete" class="permission-name add-link" data-text="remotebuildexecution.actions.delete" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  actions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.reservationAdmin">Remote Build Execution Reservation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.reservationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.actions.get" class="permission-name add-link" data-text="remotebuildexecution.actions.get" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  actions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactViewer">Remote Build Execution Artifact Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.reservationAdmin">Remote Build Execution Reservation Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.reservationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.actions.set" class="permission-name add-link" data-text="remotebuildexecution.actions.set" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  actions.  set</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.actionCacheWriter">Remote Build Execution Action Cache Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.actionCacheWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.actions.update" class="permission-name add-link" data-text="remotebuildexecution.actions.update" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  actions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.blobs.create" class="permission-name add-link" data-text="remotebuildexecution.blobs.create" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  blobs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.actionCacheWriter">Remote Build Execution Action Cache Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.actionCacheWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.blobs.get" class="permission-name add-link" data-text="remotebuildexecution.blobs.get" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.approver">Cloud Build Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.editor">Cloud Build Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.viewer">Cloud Build Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.builds.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactViewer">Remote Build Execution Artifact Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.sourceViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.botsessions.create" class="permission-name add-link" data-text="remotebuildexecution.botsessions.create" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  botsessions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.botsessions.update" class="permission-name add-link" data-text="remotebuildexecution.botsessions.update" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  botsessions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.instances.create" class="permission-name add-link" data-text="remotebuildexecution.instances.create" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  instances.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.instances.delete" class="permission-name add-link" data-text="remotebuildexecution.instances.delete" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  instances.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.instances.get" class="permission-name add-link" data-text="remotebuildexecution.instances.get" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  instances.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationViewer">Remote Build Execution Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.instances.list" class="permission-name add-link" data-text="remotebuildexecution.instances.list" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  instances.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationViewer">Remote Build Execution Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.instances.update" class="permission-name add-link" data-text="remotebuildexecution.instances.update" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  instances.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.logstreams.create" class="permission-name add-link" data-text="remotebuildexecution.logstreams.create" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.logstreamWriter">Remote Build Execution Logstream Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.logstreamWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.logstreams.get" class="permission-name add-link" data-text="remotebuildexecution.logstreams.get" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactViewer">Remote Build Execution Artifact Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.logstreams.update" class="permission-name add-link" data-text="remotebuildexecution.logstreams.update" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  logstreams.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.logstreamWriter">Remote Build Execution Logstream Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.logstreamWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.worker</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.workerpools.create" class="permission-name add-link" data-text="remotebuildexecution.workerpools.create" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.workerpools.delete" class="permission-name add-link" data-text="remotebuildexecution.workerpools.delete" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.workerpools.get" class="permission-name add-link" data-text="remotebuildexecution.workerpools.get" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationViewer">Remote Build Execution Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="remotebuildexecution.workerpools.list" class="permission-name add-link" data-text="remotebuildexecution.workerpools.list" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationViewer">Remote Build Execution Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="remotebuildexecution.workerpools.update" class="permission-name add-link" data-text="remotebuildexecution.workerpools.update" tabindex="-1"><code dir="ltr" translate="no">remotebuildexecution.  workerpools.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  remotebuildexecution.configurationAdmin</code> )</p></td>
</tr>
</tbody>
</table>
