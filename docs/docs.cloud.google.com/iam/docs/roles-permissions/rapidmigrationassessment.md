---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment
title: Rapid Migration Assessment roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Rapid Migration Assessment. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Rapid Migration Assessment roles

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
<td><h4 id="rma.admin" class="role-title add-link" data-text="Rapid Migration Assessment Admin" tabindex="-1">Rapid Migration Assessment Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  rma.admin</code> )</p>
<p>Full access to Rapid Migration Assessment all resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">rma.*</code></p>
<ul>
<li><code dir="ltr" translate="no">rma.annotations.create</code></li>
<li><code dir="ltr" translate="no">rma.annotations.get</code></li>
<li><code dir="ltr" translate="no">rma.collectors.create</code></li>
<li><code dir="ltr" translate="no">rma.collectors.delete</code></li>
<li><code dir="ltr" translate="no">rma.collectors.get</code></li>
<li><code dir="ltr" translate="no">rma.collectors.list</code></li>
<li><code dir="ltr" translate="no">rma.collectors.update</code></li>
<li><code dir="ltr" translate="no">rma.locations.get</code></li>
<li><code dir="ltr" translate="no">rma.locations.list</code></li>
<li><code dir="ltr" translate="no">rma.operations.cancel</code></li>
<li><code dir="ltr" translate="no">rma.operations.delete</code></li>
<li><code dir="ltr" translate="no">rma.operations.get</code></li>
<li><code dir="ltr" translate="no">rma.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="rma.viewer" class="role-title add-link" data-text="Rapid Migration Assessment Viewer" tabindex="-1">Rapid Migration Assessment Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  rma.viewer</code> )</p>
<p>Read-only access to Rapid Migration Assessment all resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">rma.annotations.get</code></p>
<p><code dir="ltr" translate="no">rma.collectors.get</code></p>
<p><code dir="ltr" translate="no">rma.collectors.list</code></p>
<p><code dir="ltr" translate="no">rma.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">rma.locations.get</code></li>
<li><code dir="ltr" translate="no">rma.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">rma.operations.get</code></p>
<p><code dir="ltr" translate="no">rma.operations.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="rma.runner" class="role-title add-link" data-text="Rapid Migration Assessment Runner" tabindex="-1">Rapid Migration Assessment Runner</h4>
<p>( <code dir="ltr" translate="no">roles/  rma.runner</code> )</p>
<p>Update and Read access to Rapid Migration Assessment all resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">rma.annotations.get</code></p>
<p><code dir="ltr" translate="no">rma.collectors.get</code></p>
<p><code dir="ltr" translate="no">rma.collectors.list</code></p>
<p><code dir="ltr" translate="no">rma.collectors.update</code></p>
<p><code dir="ltr" translate="no">rma.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">rma.locations.get</code></li>
<li><code dir="ltr" translate="no">rma.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">rma.operations.get</code></p>
<p><code dir="ltr" translate="no">rma.operations.list</code></p></td>
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
<td><h4 id="rapidmigrationassessment.serviceAgent" class="role-title add-link" data-text="RMA Service Agent" tabindex="-1">RMA Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  rapidmigrationassessment.serviceAgent</code> )</p>
<p>Gives RMA service account access to MC resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">autoscaling.sites.writeMetrics</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">migrationcenter.assets.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  assets.  reportFrames</code></p>
<p><code dir="ltr" translate="no">migrationcenter.importJobs.get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  importJobs.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.sources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">migrationcenter.sources.create</code></li>
<li><code dir="ltr" translate="no">migrationcenter.sources.delete</code></li>
<li><code dir="ltr" translate="no">migrationcenter.sources.get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.sources.list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.sources.update</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
</tbody>
</table>

## Rapid Migration Assessment permissions

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
<td><h4 id="rma.annotations.create" class="permission-name add-link" data-text="rma.annotations.create" tabindex="-1"><code dir="ltr" translate="no">rma.annotations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="rma.annotations.get" class="permission-name add-link" data-text="rma.annotations.get" tabindex="-1"><code dir="ltr" translate="no">rma.annotations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.viewer">Rapid Migration Assessment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.runner">Rapid Migration Assessment Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.runner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="rma.collectors.create" class="permission-name add-link" data-text="rma.collectors.create" tabindex="-1"><code dir="ltr" translate="no">rma.collectors.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="rma.collectors.delete" class="permission-name add-link" data-text="rma.collectors.delete" tabindex="-1"><code dir="ltr" translate="no">rma.collectors.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="rma.collectors.get" class="permission-name add-link" data-text="rma.collectors.get" tabindex="-1"><code dir="ltr" translate="no">rma.collectors.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.viewer">Rapid Migration Assessment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.runner">Rapid Migration Assessment Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.runner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="rma.collectors.list" class="permission-name add-link" data-text="rma.collectors.list" tabindex="-1"><code dir="ltr" translate="no">rma.collectors.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.viewer">Rapid Migration Assessment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.runner">Rapid Migration Assessment Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.runner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="rma.collectors.update" class="permission-name add-link" data-text="rma.collectors.update" tabindex="-1"><code dir="ltr" translate="no">rma.collectors.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.runner">Rapid Migration Assessment Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.runner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="rma.locations.get" class="permission-name add-link" data-text="rma.locations.get" tabindex="-1"><code dir="ltr" translate="no">rma.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.viewer">Rapid Migration Assessment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.runner">Rapid Migration Assessment Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.runner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="rma.locations.list" class="permission-name add-link" data-text="rma.locations.list" tabindex="-1"><code dir="ltr" translate="no">rma.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.viewer">Rapid Migration Assessment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.runner">Rapid Migration Assessment Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.runner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="rma.operations.cancel" class="permission-name add-link" data-text="rma.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">rma.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="rma.operations.delete" class="permission-name add-link" data-text="rma.operations.delete" tabindex="-1"><code dir="ltr" translate="no">rma.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="rma.operations.get" class="permission-name add-link" data-text="rma.operations.get" tabindex="-1"><code dir="ltr" translate="no">rma.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.viewer">Rapid Migration Assessment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.runner">Rapid Migration Assessment Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.runner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="rma.operations.list" class="permission-name add-link" data-text="rma.operations.list" tabindex="-1"><code dir="ltr" translate="no">rma.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.viewer">Rapid Migration Assessment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.runner">Rapid Migration Assessment Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rma.runner</code> )</p></td>
</tr>
</tbody>
</table>
