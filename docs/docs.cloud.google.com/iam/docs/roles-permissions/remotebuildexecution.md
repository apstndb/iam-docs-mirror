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
<td>Remotebuildexecution Admin <sup>Beta</sup>
<p>( <code>roles/ remotebuildexecution.admin</code> )</p>
<p>Admin role for remotebuildexecution</p></td>
<td><p><code>remotebuildexecution. actions. create</code></p>
<p><code>remotebuildexecution. actions. delete</code></p>
<p><code>remotebuildexecution. actions. get</code></p>
<p><code>remotebuildexecution. actions. update</code></p>
<p><code>remotebuildexecution.blobs.*</code></p>
<ul>
<li><code>remotebuildexecution. blobs. create</code></li>
<li><code>remotebuildexecution.blobs.get</code></li>
</ul>
<p><code>remotebuildexecution. botsessions.*</code></p>
<ul>
<li><code>remotebuildexecution. botsessions. create</code></li>
<li><code>remotebuildexecution. botsessions. update</code></li>
</ul>
<p><code>remotebuildexecution. instances.*</code></p>
<ul>
<li><code>remotebuildexecution. instances. create</code></li>
<li><code>remotebuildexecution. instances. delete</code></li>
<li><code>remotebuildexecution. instances. get</code></li>
<li><code>remotebuildexecution. instances. list</code></li>
<li><code>remotebuildexecution. instances. update</code></li>
</ul>
<p><code>remotebuildexecution. logstreams.*</code></p>
<ul>
<li><code>remotebuildexecution. logstreams. create</code></li>
<li><code>remotebuildexecution. logstreams. get</code></li>
<li><code>remotebuildexecution. logstreams. update</code></li>
</ul>
<p><code>remotebuildexecution. workerpools.*</code></p>
<ul>
<li><code>remotebuildexecution. workerpools. create</code></li>
<li><code>remotebuildexecution. workerpools. delete</code></li>
<li><code>remotebuildexecution. workerpools. get</code></li>
<li><code>remotebuildexecution. workerpools. list</code></li>
<li><code>remotebuildexecution. workerpools. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Remotebuildexecution Editor <sup>Beta</sup>
<p>( <code>roles/ remotebuildexecution.editor</code> )</p>
<p>Editor role for remotebuildexecution</p></td>
<td><p><code>remotebuildexecution. actions. create</code></p>
<p><code>remotebuildexecution. actions. delete</code></p>
<p><code>remotebuildexecution. actions. get</code></p>
<p><code>remotebuildexecution. actions. update</code></p>
<p><code>remotebuildexecution.blobs.*</code></p>
<ul>
<li><code>remotebuildexecution. blobs. create</code></li>
<li><code>remotebuildexecution.blobs.get</code></li>
</ul>
<p><code>remotebuildexecution. botsessions.*</code></p>
<ul>
<li><code>remotebuildexecution. botsessions. create</code></li>
<li><code>remotebuildexecution. botsessions. update</code></li>
</ul>
<p><code>remotebuildexecution. instances. create</code></p>
<p><code>remotebuildexecution. instances. get</code></p>
<p><code>remotebuildexecution. instances. list</code></p>
<p><code>remotebuildexecution. instances. update</code></p>
<p><code>remotebuildexecution. logstreams.*</code></p>
<ul>
<li><code>remotebuildexecution. logstreams. create</code></li>
<li><code>remotebuildexecution. logstreams. get</code></li>
<li><code>remotebuildexecution. logstreams. update</code></li>
</ul>
<p><code>remotebuildexecution. workerpools. create</code></p>
<p><code>remotebuildexecution. workerpools. get</code></p>
<p><code>remotebuildexecution. workerpools. list</code></p>
<p><code>remotebuildexecution. workerpools. update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Remotebuildexecution Viewer <sup>Beta</sup>
<p>( <code>roles/ remotebuildexecution.viewer</code> )</p>
<p>Viewer role for remotebuildexecution</p></td>
<td><p><code>remotebuildexecution. actions. get</code></p>
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>remotebuildexecution. instances. get</code></p>
<p><code>remotebuildexecution. instances. list</code></p>
<p><code>remotebuildexecution. logstreams. get</code></p>
<p><code>remotebuildexecution. workerpools. get</code></p>
<p><code>remotebuildexecution. workerpools. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Remote Build Execution Action Cache Writer <sup>Beta</sup>
<p>( <code>roles/ remotebuildexecution.actionCacheWriter</code> )</p>
<p>Remote Build Execution Action Cache Writer</p></td>
<td><p><code>remotebuildexecution. actions. set</code></p>
<p><code>remotebuildexecution. blobs. create</code></p></td>
</tr>
<tr class="odd">
<td>Remote Build Execution Artifact Admin <sup>Beta</sup>
<p>( <code>roles/ remotebuildexecution.artifactAdmin</code> )</p>
<p>Remote Build Execution Artifact Admin</p></td>
<td><p><code>remotebuildexecution. actions. create</code></p>
<p><code>remotebuildexecution. actions. delete</code></p>
<p><code>remotebuildexecution. actions. get</code></p>
<p><code>remotebuildexecution.blobs.*</code></p>
<ul>
<li><code>remotebuildexecution. blobs. create</code></li>
<li><code>remotebuildexecution.blobs.get</code></li>
</ul>
<p><code>remotebuildexecution. logstreams.*</code></p>
<ul>
<li><code>remotebuildexecution. logstreams. create</code></li>
<li><code>remotebuildexecution. logstreams. get</code></li>
<li><code>remotebuildexecution. logstreams. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Remote Build Execution Artifact Creator <sup>Beta</sup>
<p>( <code>roles/ remotebuildexecution.artifactCreator</code> )</p>
<p>Remote Build Execution Artifact Creator</p></td>
<td><p><code>remotebuildexecution. actions. create</code></p>
<p><code>remotebuildexecution. actions. get</code></p>
<p><code>remotebuildexecution.blobs.*</code></p>
<ul>
<li><code>remotebuildexecution. blobs. create</code></li>
<li><code>remotebuildexecution.blobs.get</code></li>
</ul>
<p><code>remotebuildexecution. logstreams.*</code></p>
<ul>
<li><code>remotebuildexecution. logstreams. create</code></li>
<li><code>remotebuildexecution. logstreams. get</code></li>
<li><code>remotebuildexecution. logstreams. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Remote Build Execution Artifact Viewer <sup>Beta</sup>
<p>( <code>roles/ remotebuildexecution.artifactViewer</code> )</p>
<p>Remote Build Execution Artifact Viewer</p></td>
<td><p><code>remotebuildexecution. actions. get</code></p>
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>remotebuildexecution. logstreams. get</code></p></td>
</tr>
<tr class="even">
<td>Remote Build Execution Configuration Admin <sup>Beta</sup>
<p>( <code>roles/ remotebuildexecution.configurationAdmin</code> )</p>
<p>Remote Build Execution Configuration Admin</p></td>
<td><p><code>remotebuildexecution. instances.*</code></p>
<ul>
<li><code>remotebuildexecution. instances. create</code></li>
<li><code>remotebuildexecution. instances. delete</code></li>
<li><code>remotebuildexecution. instances. get</code></li>
<li><code>remotebuildexecution. instances. list</code></li>
<li><code>remotebuildexecution. instances. update</code></li>
</ul>
<p><code>remotebuildexecution. workerpools.*</code></p>
<ul>
<li><code>remotebuildexecution. workerpools. create</code></li>
<li><code>remotebuildexecution. workerpools. delete</code></li>
<li><code>remotebuildexecution. workerpools. get</code></li>
<li><code>remotebuildexecution. workerpools. list</code></li>
<li><code>remotebuildexecution. workerpools. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Remote Build Execution Configuration Viewer <sup>Beta</sup>
<p>( <code>roles/ remotebuildexecution.configurationViewer</code> )</p>
<p>Remote Build Execution Configuration Viewer</p></td>
<td><p><code>remotebuildexecution. instances. get</code></p>
<p><code>remotebuildexecution. instances. list</code></p>
<p><code>remotebuildexecution. workerpools. get</code></p>
<p><code>remotebuildexecution. workerpools. list</code></p></td>
</tr>
<tr class="even">
<td>Remote Build Execution Logstream Writer <sup>Beta</sup>
<p>( <code>roles/ remotebuildexecution.logstreamWriter</code> )</p>
<p>Remote Build Execution Logstream Writer</p></td>
<td><p><code>remotebuildexecution. logstreams. create</code></p>
<p><code>remotebuildexecution. logstreams. update</code></p></td>
</tr>
<tr class="odd">
<td>Remote Build Execution Reservation Admin <sup>Beta</sup>
<p>( <code>roles/ remotebuildexecution.reservationAdmin</code> )</p>
<p>Remote Build Execution Reservation Admin</p></td>
<td><p><code>remotebuildexecution. actions. create</code></p>
<p><code>remotebuildexecution. actions. delete</code></p>
<p><code>remotebuildexecution. actions. get</code></p></td>
</tr>
<tr class="even">
<td>Remote Build Execution Worker <sup>Beta</sup>
<p>( <code>roles/ remotebuildexecution.worker</code> )</p>
<p>Remote Build Execution Worker</p></td>
<td><p><code>remotebuildexecution. actions. update</code></p>
<p><code>remotebuildexecution.blobs.*</code></p>
<ul>
<li><code>remotebuildexecution. blobs. create</code></li>
<li><code>remotebuildexecution.blobs.get</code></li>
</ul>
<p><code>remotebuildexecution. botsessions.*</code></p>
<ul>
<li><code>remotebuildexecution. botsessions. create</code></li>
<li><code>remotebuildexecution. botsessions. update</code></li>
</ul>
<p><code>remotebuildexecution. logstreams. create</code></p>
<p><code>remotebuildexecution. logstreams. update</code></p></td>
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
<td>Remote Build Execution Service Agent
<p>( <code>roles/ remotebuildexecution.serviceAgent</code> )</p>
<p>Gives Remote Build Execution service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>remotebuildexecution. actions. update</code></p>
<p><code>remotebuildexecution.blobs.*</code></p>
<ul>
<li><code>remotebuildexecution. blobs. create</code></li>
<li><code>remotebuildexecution.blobs.get</code></li>
</ul>
<p><code>remotebuildexecution. botsessions.*</code></p>
<ul>
<li><code>remotebuildexecution. botsessions. create</code></li>
<li><code>remotebuildexecution. botsessions. update</code></li>
</ul>
<p><code>remotebuildexecution. logstreams. create</code></p>
<p><code>remotebuildexecution. logstreams. update</code></p></td>
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
<td><code>remotebuildexecution. actions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code>roles/ remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code>roles/ remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.reservationAdmin">Remote Build Execution Reservation Admin</a> ( <code>roles/ remotebuildexecution.reservationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>remotebuildexecution. actions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code>roles/ remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.reservationAdmin">Remote Build Execution Reservation Admin</a> ( <code>roles/ remotebuildexecution.reservationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>remotebuildexecution. actions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code>roles/ remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code>roles/ remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code>roles/ remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactViewer">Remote Build Execution Artifact Viewer</a> ( <code>roles/ remotebuildexecution.artifactViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.reservationAdmin">Remote Build Execution Reservation Admin</a> ( <code>roles/ remotebuildexecution.reservationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>remotebuildexecution. actions. set</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.actionCacheWriter">Remote Build Execution Action Cache Writer</a> ( <code>roles/ remotebuildexecution.actionCacheWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><code>remotebuildexecution. actions. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code>roles/ remotebuildexecution.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code>roles/ remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>remotebuildexecution. blobs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.actionCacheWriter">Remote Build Execution Action Cache Writer</a> ( <code>roles/ remotebuildexecution.actionCacheWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code>roles/ remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code>roles/ remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code>roles/ remotebuildexecution.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code>roles/ remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>remotebuildexecution.blobs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code>roles/ cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code>roles/ remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.approver">Cloud Build Approver</a> ( <code>roles/ cloudbuild.builds.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.editor">Cloud Build Editor</a> ( <code>roles/ cloudbuild.builds.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.viewer">Cloud Build Viewer</a> ( <code>roles/ cloudbuild.builds.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code>roles/ remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code>roles/ remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactViewer">Remote Build Execution Artifact Viewer</a> ( <code>roles/ remotebuildexecution.artifactViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code>roles/ remotebuildexecution.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code>roles/ remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>remotebuildexecution. botsessions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code>roles/ remotebuildexecution.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code>roles/ remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>remotebuildexecution. botsessions. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code>roles/ remotebuildexecution.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code>roles/ remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>remotebuildexecution. instances. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code>roles/ remotebuildexecution.configurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>remotebuildexecution. instances. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code>roles/ remotebuildexecution.configurationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>remotebuildexecution. instances. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code>roles/ remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code>roles/ remotebuildexecution.configurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationViewer">Remote Build Execution Configuration Viewer</a> ( <code>roles/ remotebuildexecution.configurationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>remotebuildexecution. instances. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code>roles/ remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code>roles/ remotebuildexecution.configurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationViewer">Remote Build Execution Configuration Viewer</a> ( <code>roles/ remotebuildexecution.configurationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>remotebuildexecution. instances. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code>roles/ remotebuildexecution.configurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>remotebuildexecution. logstreams. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code>roles/ remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code>roles/ remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.logstreamWriter">Remote Build Execution Logstream Writer</a> ( <code>roles/ remotebuildexecution.logstreamWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code>roles/ remotebuildexecution.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code>roles/ remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>remotebuildexecution. logstreams. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code>roles/ remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code>roles/ remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code>roles/ remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactViewer">Remote Build Execution Artifact Viewer</a> ( <code>roles/ remotebuildexecution.artifactViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>remotebuildexecution. logstreams. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactAdmin">Remote Build Execution Artifact Admin</a> ( <code>roles/ remotebuildexecution.artifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.artifactCreator">Remote Build Execution Artifact Creator</a> ( <code>roles/ remotebuildexecution.artifactCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.logstreamWriter">Remote Build Execution Logstream Writer</a> ( <code>roles/ remotebuildexecution.logstreamWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.worker">Remote Build Execution Worker</a> ( <code>roles/ remotebuildexecution.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.serviceAgent">Remote Build Execution Service Agent</a> ( <code>roles/ remotebuildexecution.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>remotebuildexecution. workerpools. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code>roles/ remotebuildexecution.configurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>remotebuildexecution. workerpools. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code>roles/ remotebuildexecution.configurationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>remotebuildexecution. workerpools. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code>roles/ remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code>roles/ remotebuildexecution.configurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationViewer">Remote Build Execution Configuration Viewer</a> ( <code>roles/ remotebuildexecution.configurationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>remotebuildexecution. workerpools. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code>roles/ remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code>roles/ remotebuildexecution.configurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationViewer">Remote Build Execution Configuration Viewer</a> ( <code>roles/ remotebuildexecution.configurationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>remotebuildexecution. workerpools. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.configurationAdmin">Remote Build Execution Configuration Admin</a> ( <code>roles/ remotebuildexecution.configurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
