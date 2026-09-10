---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter
title: Google Cloud Migration Center roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Cloud Migration Center. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Cloud Migration Center roles

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
<td><h4 id="migrationcenter.admin" class="role-title add-link" data-text="Migration Center Admin Beta" tabindex="-1">Migration Center Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p>Full access to Migration Center all resources.</p></td>
<td><p><code dir="ltr" translate="no">migrationcenter.*</code></p>
<ul>
<li><code dir="ltr" translate="no">migrationcenter.assets.delete</code></li>
<li><code dir="ltr" translate="no">migrationcenter.assets.get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.assets.list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  assets.  reportFrames</code></li>
<li><code dir="ltr" translate="no">migrationcenter.assets.update</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  create</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  delete</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  run</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  create</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  delete</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  sendHeartbeat</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  update</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  errorFrames.  get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  errorFrames.  list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.groups.create</code></li>
<li><code dir="ltr" translate="no">migrationcenter.groups.delete</code></li>
<li><code dir="ltr" translate="no">migrationcenter.groups.get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.groups.list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.groups.update</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  importDataFiles.  create</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  importDataFiles.  delete</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  importDataFiles.  get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  importDataFiles.  list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  importJobs.  create</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  importJobs.  delete</code></li>
<li><code dir="ltr" translate="no">migrationcenter.importJobs.get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  importJobs.  list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  importJobs.  update</code></li>
<li><code dir="ltr" translate="no">migrationcenter.locations.get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.locations.list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">migrationcenter.operations.get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  operations.  list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  create</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  delete</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  update</code></li>
<li><code dir="ltr" translate="no">migrationcenter.relations.get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.relations.list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  reportConfigs.  create</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  reportConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  reportConfigs.  get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  reportConfigs.  list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.reports.create</code></li>
<li><code dir="ltr" translate="no">migrationcenter.reports.delete</code></li>
<li><code dir="ltr" translate="no">migrationcenter.reports.get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.reports.list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.settings.get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  settings.  update</code></li>
<li><code dir="ltr" translate="no">migrationcenter.sources.create</code></li>
<li><code dir="ltr" translate="no">migrationcenter.sources.delete</code></li>
<li><code dir="ltr" translate="no">migrationcenter.sources.get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.sources.list</code></li>
<li><code dir="ltr" translate="no">migrationcenter.sources.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
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
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.viewer" class="role-title add-link" data-text="Migration Center Viewer Beta" tabindex="-1">Migration Center Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p>Read-only access to Migration Center all resources.</p></td>
<td><p><code dir="ltr" translate="no">migrationcenter.assets.get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.assets.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.errorFrames.*</code></p>
<ul>
<li><code dir="ltr" translate="no">migrationcenter.  errorFrames.  get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.  errorFrames.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">migrationcenter.groups.get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.groups.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  importDataFiles.  get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  importDataFiles.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.importJobs.get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  importJobs.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">migrationcenter.locations.get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">migrationcenter.operations.get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  operations.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.relations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">migrationcenter.relations.get</code></li>
<li><code dir="ltr" translate="no">migrationcenter.relations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">migrationcenter.  reportConfigs.  get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  reportConfigs.  list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.reports.get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.reports.list</code></p>
<p><code dir="ltr" translate="no">migrationcenter.settings.get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.sources.get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.sources.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
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
<p><code dir="ltr" translate="no">rma.operations.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.discoveryClient" class="role-title add-link" data-text="Migration Center Discovery Client Beta" tabindex="-1">Migration Center Discovery Client <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  migrationcenter.discoveryClient</code> )</p>
<p>Migration Center Discover Client role</p></td>
<td><p><code dir="ltr" translate="no">migrationcenter.  assets.  reportFrames</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  sendHeartbeat</code></p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.discoveryClientRegistrator" class="role-title add-link" data-text="Migration Center Discovery Client Registrator Beta" tabindex="-1">Migration Center Discovery Client Registrator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  migrationcenter.discoveryClientRegistrator</code> )</p>
<p>Registrator of Migration Center Discover Clients</p></td>
<td><p><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  create</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  delete</code></p>
<p><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  update</code></p>
<p><code dir="ltr" translate="no">migrationcenter.operations.get</code></p>
<p><code dir="ltr" translate="no">migrationcenter.sources.create</code></p>
<p><code dir="ltr" translate="no">migrationcenter.sources.delete</code></p>
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
<td><h4 id="migrationcenter.serviceAgent" class="role-title add-link" data-text="Migration Center Service Agent" tabindex="-1">Migration Center Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  migrationcenter.serviceAgent</code> )</p>
<p>Gives Migration Center Service Account access to objects storedin object store and Cloud Migration products.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">vmmigration.  migratingVms.  create</code></p></td>
</tr>
</tbody>
</table>

## Google Cloud Migration Center permissions

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
<td><h4 id="migrationcenter.assets.delete" class="permission-name add-link" data-text="migrationcenter.assets.delete" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.assets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.assets.get" class="permission-name add-link" data-text="migrationcenter.assets.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.assets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.assets.list" class="permission-name add-link" data-text="migrationcenter.assets.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.assets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rapidmigrationassessment.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.assets.reportFrames" class="permission-name add-link" data-text="migrationcenter.assets.reportFrames" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  assets.  reportFrames</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.discoveryClient">Migration Center Discovery Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.discoveryClient</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rapidmigrationassessment.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.assets.update" class="permission-name add-link" data-text="migrationcenter.assets.update" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.assets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.assetsExportJobs.create" class="permission-name add-link" data-text="migrationcenter.assetsExportJobs.create" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.assetsExportJobs.delete" class="permission-name add-link" data-text="migrationcenter.assetsExportJobs.delete" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.assetsExportJobs.get" class="permission-name add-link" data-text="migrationcenter.assetsExportJobs.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.assetsExportJobs.list" class="permission-name add-link" data-text="migrationcenter.assetsExportJobs.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.assetsExportJobs.run" class="permission-name add-link" data-text="migrationcenter.assetsExportJobs.run" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  assetsExportJobs.  run</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.discoveryClients.create" class="permission-name add-link" data-text="migrationcenter.discoveryClients.create" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.discoveryClientRegistrator">Migration Center Discovery Client Registrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.discoveryClientRegistrator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.discoveryClients.delete" class="permission-name add-link" data-text="migrationcenter.discoveryClients.delete" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.discoveryClientRegistrator">Migration Center Discovery Client Registrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.discoveryClientRegistrator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.discoveryClients.get" class="permission-name add-link" data-text="migrationcenter.discoveryClients.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.discoveryClient">Migration Center Discovery Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.discoveryClient</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.discoveryClients.list" class="permission-name add-link" data-text="migrationcenter.discoveryClients.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.discoveryClients.sendHeartbeat" class="permission-name add-link" data-text="migrationcenter.discoveryClients.sendHeartbeat" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  sendHeartbeat</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.discoveryClient">Migration Center Discovery Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.discoveryClient</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.discoveryClients.update" class="permission-name add-link" data-text="migrationcenter.discoveryClients.update" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  discoveryClients.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.discoveryClientRegistrator">Migration Center Discovery Client Registrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.discoveryClientRegistrator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.errorFrames.get" class="permission-name add-link" data-text="migrationcenter.errorFrames.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  errorFrames.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.errorFrames.list" class="permission-name add-link" data-text="migrationcenter.errorFrames.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  errorFrames.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.groups.create" class="permission-name add-link" data-text="migrationcenter.groups.create" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.groups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.groups.delete" class="permission-name add-link" data-text="migrationcenter.groups.delete" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.groups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.groups.get" class="permission-name add-link" data-text="migrationcenter.groups.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.groups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.groups.list" class="permission-name add-link" data-text="migrationcenter.groups.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.groups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.groups.update" class="permission-name add-link" data-text="migrationcenter.groups.update" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.groups.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.importDataFiles.create" class="permission-name add-link" data-text="migrationcenter.importDataFiles.create" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  importDataFiles.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.importDataFiles.delete" class="permission-name add-link" data-text="migrationcenter.importDataFiles.delete" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  importDataFiles.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.importDataFiles.get" class="permission-name add-link" data-text="migrationcenter.importDataFiles.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  importDataFiles.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.importDataFiles.list" class="permission-name add-link" data-text="migrationcenter.importDataFiles.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  importDataFiles.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.importJobs.create" class="permission-name add-link" data-text="migrationcenter.importJobs.create" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  importJobs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.importJobs.delete" class="permission-name add-link" data-text="migrationcenter.importJobs.delete" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  importJobs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.importJobs.get" class="permission-name add-link" data-text="migrationcenter.importJobs.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.importJobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rapidmigrationassessment.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.importJobs.list" class="permission-name add-link" data-text="migrationcenter.importJobs.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  importJobs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rapidmigrationassessment.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.importJobs.update" class="permission-name add-link" data-text="migrationcenter.importJobs.update" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  importJobs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.locations.get" class="permission-name add-link" data-text="migrationcenter.locations.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.locations.list" class="permission-name add-link" data-text="migrationcenter.locations.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.operations.cancel" class="permission-name add-link" data-text="migrationcenter.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.operations.delete" class="permission-name add-link" data-text="migrationcenter.operations.delete" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.operations.get" class="permission-name add-link" data-text="migrationcenter.operations.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.discoveryClientRegistrator">Migration Center Discovery Client Registrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.discoveryClientRegistrator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.operations.list" class="permission-name add-link" data-text="migrationcenter.operations.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.preferenceSets.create" class="permission-name add-link" data-text="migrationcenter.preferenceSets.create" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.preferenceSets.delete" class="permission-name add-link" data-text="migrationcenter.preferenceSets.delete" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.preferenceSets.get" class="permission-name add-link" data-text="migrationcenter.preferenceSets.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.preferenceSets.list" class="permission-name add-link" data-text="migrationcenter.preferenceSets.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.preferenceSets.update" class="permission-name add-link" data-text="migrationcenter.preferenceSets.update" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  preferenceSets.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.relations.get" class="permission-name add-link" data-text="migrationcenter.relations.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.relations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.relations.list" class="permission-name add-link" data-text="migrationcenter.relations.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.relations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.reportConfigs.create" class="permission-name add-link" data-text="migrationcenter.reportConfigs.create" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  reportConfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.reportConfigs.delete" class="permission-name add-link" data-text="migrationcenter.reportConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  reportConfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.reportConfigs.get" class="permission-name add-link" data-text="migrationcenter.reportConfigs.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  reportConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.reportConfigs.list" class="permission-name add-link" data-text="migrationcenter.reportConfigs.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  reportConfigs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.reports.create" class="permission-name add-link" data-text="migrationcenter.reports.create" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.reports.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.reports.delete" class="permission-name add-link" data-text="migrationcenter.reports.delete" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.reports.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.reports.get" class="permission-name add-link" data-text="migrationcenter.reports.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.reports.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.reports.list" class="permission-name add-link" data-text="migrationcenter.reports.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.reports.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.settings.get" class="permission-name add-link" data-text="migrationcenter.settings.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.settings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.settings.update" class="permission-name add-link" data-text="migrationcenter.settings.update" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.  settings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.sources.create" class="permission-name add-link" data-text="migrationcenter.sources.create" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.sources.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.discoveryClientRegistrator">Migration Center Discovery Client Registrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.discoveryClientRegistrator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rapidmigrationassessment.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.sources.delete" class="permission-name add-link" data-text="migrationcenter.sources.delete" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.sources.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.discoveryClientRegistrator">Migration Center Discovery Client Registrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.discoveryClientRegistrator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rapidmigrationassessment.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.sources.get" class="permission-name add-link" data-text="migrationcenter.sources.get" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.sources.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rapidmigrationassessment.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="migrationcenter.sources.list" class="permission-name add-link" data-text="migrationcenter.sources.list" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.sources.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rapidmigrationassessment.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="migrationcenter.sources.update" class="permission-name add-link" data-text="migrationcenter.sources.update" tabindex="-1"><code dir="ltr" translate="no">migrationcenter.sources.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  rapidmigrationassessment.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
