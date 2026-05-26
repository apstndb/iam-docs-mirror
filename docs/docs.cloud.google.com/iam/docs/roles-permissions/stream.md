---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/stream
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/stream
title: Stream roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Stream. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Stream roles

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
<td><h4 id="stream.admin" class="role-title add-link" data-text="Stream Admin" tabindex="-1">Stream Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p>Full access to Stream all resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">stream.*</code></p>
<ul>
<li><code dir="ltr" translate="no">stream.locations.get</code></li>
<li><code dir="ltr" translate="no">stream.locations.list</code></li>
<li><code dir="ltr" translate="no">stream.operations.cancel</code></li>
<li><code dir="ltr" translate="no">stream.operations.delete</code></li>
<li><code dir="ltr" translate="no">stream.operations.get</code></li>
<li><code dir="ltr" translate="no">stream.operations.list</code></li>
<li><code dir="ltr" translate="no">stream.streamContents.build</code></li>
<li><code dir="ltr" translate="no">stream.streamContents.create</code></li>
<li><code dir="ltr" translate="no">stream.streamContents.delete</code></li>
<li><code dir="ltr" translate="no">stream.streamContents.get</code></li>
<li><code dir="ltr" translate="no">stream.streamContents.list</code></li>
<li><code dir="ltr" translate="no">stream.streamContents.update</code></li>
<li><code dir="ltr" translate="no">stream.streamInstances.create</code></li>
<li><code dir="ltr" translate="no">stream.streamInstances.delete</code></li>
<li><code dir="ltr" translate="no">stream.streamInstances.get</code></li>
<li><code dir="ltr" translate="no">stream.streamInstances.list</code></li>
<li><code dir="ltr" translate="no">stream.streamInstances.rollout</code></li>
<li><code dir="ltr" translate="no">stream.streamInstances.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="stream.viewer" class="role-title add-link" data-text="Stream Viewer" tabindex="-1">Stream Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  stream.viewer</code> )</p>
<p>Read-only access to Stream all resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">stream.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">stream.locations.get</code></li>
<li><code dir="ltr" translate="no">stream.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">stream.operations.get</code></p>
<p><code dir="ltr" translate="no">stream.operations.list</code></p>
<p><code dir="ltr" translate="no">stream.streamContents.get</code></p>
<p><code dir="ltr" translate="no">stream.streamContents.list</code></p>
<p><code dir="ltr" translate="no">stream.streamInstances.get</code></p>
<p><code dir="ltr" translate="no">stream.streamInstances.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="stream.contentAdmin" class="role-title add-link" data-text="Stream Content Admin" tabindex="-1">Stream Content Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  stream.contentAdmin</code> )</p>
<p>Full access to all StreamContent resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">stream.streamContents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">stream.streamContents.build</code></li>
<li><code dir="ltr" translate="no">stream.streamContents.create</code></li>
<li><code dir="ltr" translate="no">stream.streamContents.delete</code></li>
<li><code dir="ltr" translate="no">stream.streamContents.get</code></li>
<li><code dir="ltr" translate="no">stream.streamContents.list</code></li>
<li><code dir="ltr" translate="no">stream.streamContents.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="stream.contentBuilder" class="role-title add-link" data-text="Stream Content Builder" tabindex="-1">Stream Content Builder</h4>
<p>( <code dir="ltr" translate="no">roles/  stream.contentBuilder</code> )</p>
<p>Read and build access to StreamContent resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">stream.streamContents.build</code></p>
<p><code dir="ltr" translate="no">stream.streamContents.get</code></p>
<p><code dir="ltr" translate="no">stream.streamContents.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="stream.instanceAdmin" class="role-title add-link" data-text="Stream Instance Admin" tabindex="-1">Stream Instance Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  stream.instanceAdmin</code> )</p>
<p>Full access to all StreamInstance resources and Read access to all StreamContent resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">stream.streamContents.get</code></p>
<p><code dir="ltr" translate="no">stream.streamContents.list</code></p>
<p><code dir="ltr" translate="no">stream.streamInstances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">stream.streamInstances.create</code></li>
<li><code dir="ltr" translate="no">stream.streamInstances.delete</code></li>
<li><code dir="ltr" translate="no">stream.streamInstances.get</code></li>
<li><code dir="ltr" translate="no">stream.streamInstances.list</code></li>
<li><code dir="ltr" translate="no">stream.streamInstances.rollout</code></li>
<li><code dir="ltr" translate="no">stream.streamInstances.update</code></li>
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
<td><h4 id="stream.serviceAgent" class="role-title add-link" data-text="Stream Service Agent" tabindex="-1">Stream Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  stream.serviceAgent</code> )</p>
<p>Gives Immersive Stream for XR access to the required resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Stream permissions

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
<td><h4 id="stream.locations.get" class="permission-name add-link" data-text="stream.locations.get" tabindex="-1"><code dir="ltr" translate="no">stream.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.viewer">Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="stream.locations.list" class="permission-name add-link" data-text="stream.locations.list" tabindex="-1"><code dir="ltr" translate="no">stream.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.viewer">Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="stream.operations.cancel" class="permission-name add-link" data-text="stream.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">stream.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="stream.operations.delete" class="permission-name add-link" data-text="stream.operations.delete" tabindex="-1"><code dir="ltr" translate="no">stream.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="stream.operations.get" class="permission-name add-link" data-text="stream.operations.get" tabindex="-1"><code dir="ltr" translate="no">stream.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.viewer">Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="stream.operations.list" class="permission-name add-link" data-text="stream.operations.list" tabindex="-1"><code dir="ltr" translate="no">stream.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.viewer">Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="stream.streamContents.build" class="permission-name add-link" data-text="stream.streamContents.build" tabindex="-1"><code dir="ltr" translate="no">stream.streamContents.build</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentAdmin">Stream Content Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.contentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentBuilder">Stream Content Builder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.contentBuilder</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="stream.streamContents.create" class="permission-name add-link" data-text="stream.streamContents.create" tabindex="-1"><code dir="ltr" translate="no">stream.streamContents.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentAdmin">Stream Content Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.contentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="stream.streamContents.delete" class="permission-name add-link" data-text="stream.streamContents.delete" tabindex="-1"><code dir="ltr" translate="no">stream.streamContents.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentAdmin">Stream Content Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.contentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="stream.streamContents.get" class="permission-name add-link" data-text="stream.streamContents.get" tabindex="-1"><code dir="ltr" translate="no">stream.streamContents.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.viewer">Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentAdmin">Stream Content Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.contentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentBuilder">Stream Content Builder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.contentBuilder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.instanceAdmin">Stream Instance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.instanceAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="stream.streamContents.list" class="permission-name add-link" data-text="stream.streamContents.list" tabindex="-1"><code dir="ltr" translate="no">stream.streamContents.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.viewer">Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentAdmin">Stream Content Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.contentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentBuilder">Stream Content Builder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.contentBuilder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.instanceAdmin">Stream Instance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.instanceAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="stream.streamContents.update" class="permission-name add-link" data-text="stream.streamContents.update" tabindex="-1"><code dir="ltr" translate="no">stream.streamContents.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentAdmin">Stream Content Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.contentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="stream.streamInstances.create" class="permission-name add-link" data-text="stream.streamInstances.create" tabindex="-1"><code dir="ltr" translate="no">stream.streamInstances.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.instanceAdmin">Stream Instance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.instanceAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="stream.streamInstances.delete" class="permission-name add-link" data-text="stream.streamInstances.delete" tabindex="-1"><code dir="ltr" translate="no">stream.streamInstances.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.instanceAdmin">Stream Instance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.instanceAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="stream.streamInstances.get" class="permission-name add-link" data-text="stream.streamInstances.get" tabindex="-1"><code dir="ltr" translate="no">stream.streamInstances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.viewer">Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.instanceAdmin">Stream Instance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.instanceAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="stream.streamInstances.list" class="permission-name add-link" data-text="stream.streamInstances.list" tabindex="-1"><code dir="ltr" translate="no">stream.streamInstances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.viewer">Stream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.instanceAdmin">Stream Instance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.instanceAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="stream.streamInstances.rollout" class="permission-name add-link" data-text="stream.streamInstances.rollout" tabindex="-1"><code dir="ltr" translate="no">stream.streamInstances.rollout</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.instanceAdmin">Stream Instance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.instanceAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="stream.streamInstances.update" class="permission-name add-link" data-text="stream.streamInstances.update" tabindex="-1"><code dir="ltr" translate="no">stream.streamInstances.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.instanceAdmin">Stream Instance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  stream.instanceAdmin</code> )</p></td>
</tr>
</tbody>
</table>
