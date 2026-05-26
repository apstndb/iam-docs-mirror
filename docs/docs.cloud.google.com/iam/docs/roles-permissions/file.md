---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/file
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/file
title: Filestore roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Filestore. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Filestore roles

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
<td><h4 id="file.admin" class="role-title add-link" data-text="File Admin Beta" tabindex="-1">File Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p>Admin role for file</p></td>
<td><p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.locations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  serviceConfig.  initialize</code></p>
<p><code dir="ltr" translate="no">file.*</code></p>
<ul>
<li><code dir="ltr" translate="no">file.backups.create</code></li>
<li><code dir="ltr" translate="no">file.backups.createTagBinding</code></li>
<li><code dir="ltr" translate="no">file.backups.delete</code></li>
<li><code dir="ltr" translate="no">file.backups.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">file.backups.get</code></li>
<li><code dir="ltr" translate="no">file.backups.list</code></li>
<li><code dir="ltr" translate="no">file.backups.listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">file.backups.listTagBindings</code></li>
<li><code dir="ltr" translate="no">file.backups.update</code></li>
<li><code dir="ltr" translate="no">file.backups.useReadOnly</code></li>
<li><code dir="ltr" translate="no">file.instances.create</code></li>
<li><code dir="ltr" translate="no">file.  instances.  createCrossProjectBackup</code></li>
<li><code dir="ltr" translate="no">file.  instances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">file.instances.delete</code></li>
<li><code dir="ltr" translate="no">file.  instances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">file.instances.get</code></li>
<li><code dir="ltr" translate="no">file.instances.list</code></li>
<li><code dir="ltr" translate="no">file.  instances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">file.instances.listTagBindings</code></li>
<li><code dir="ltr" translate="no">file.instances.restore</code></li>
<li><code dir="ltr" translate="no">file.instances.revert</code></li>
<li><code dir="ltr" translate="no">file.instances.update</code></li>
<li><code dir="ltr" translate="no">file.locations.get</code></li>
<li><code dir="ltr" translate="no">file.locations.list</code></li>
<li><code dir="ltr" translate="no">file.operations.cancel</code></li>
<li><code dir="ltr" translate="no">file.operations.delete</code></li>
<li><code dir="ltr" translate="no">file.operations.get</code></li>
<li><code dir="ltr" translate="no">file.operations.list</code></li>
<li><code dir="ltr" translate="no">file.  snapshots.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">file.  snapshots.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">file.  snapshots.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">file.snapshots.listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="file.editor" class="role-title add-link" data-text="Cloud Filestore Editor Beta" tabindex="-1">Cloud Filestore Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p>Read-write access to Filestore instances and related resources.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.locations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  serviceConfig.  initialize</code></p>
<p><code dir="ltr" translate="no">file.*</code></p>
<ul>
<li><code dir="ltr" translate="no">file.backups.create</code></li>
<li><code dir="ltr" translate="no">file.backups.createTagBinding</code></li>
<li><code dir="ltr" translate="no">file.backups.delete</code></li>
<li><code dir="ltr" translate="no">file.backups.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">file.backups.get</code></li>
<li><code dir="ltr" translate="no">file.backups.list</code></li>
<li><code dir="ltr" translate="no">file.backups.listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">file.backups.listTagBindings</code></li>
<li><code dir="ltr" translate="no">file.backups.update</code></li>
<li><code dir="ltr" translate="no">file.backups.useReadOnly</code></li>
<li><code dir="ltr" translate="no">file.instances.create</code></li>
<li><code dir="ltr" translate="no">file.  instances.  createCrossProjectBackup</code></li>
<li><code dir="ltr" translate="no">file.  instances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">file.instances.delete</code></li>
<li><code dir="ltr" translate="no">file.  instances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">file.instances.get</code></li>
<li><code dir="ltr" translate="no">file.instances.list</code></li>
<li><code dir="ltr" translate="no">file.  instances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">file.instances.listTagBindings</code></li>
<li><code dir="ltr" translate="no">file.instances.restore</code></li>
<li><code dir="ltr" translate="no">file.instances.revert</code></li>
<li><code dir="ltr" translate="no">file.instances.update</code></li>
<li><code dir="ltr" translate="no">file.locations.get</code></li>
<li><code dir="ltr" translate="no">file.locations.list</code></li>
<li><code dir="ltr" translate="no">file.operations.cancel</code></li>
<li><code dir="ltr" translate="no">file.operations.delete</code></li>
<li><code dir="ltr" translate="no">file.operations.get</code></li>
<li><code dir="ltr" translate="no">file.operations.list</code></li>
<li><code dir="ltr" translate="no">file.  snapshots.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">file.  snapshots.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">file.  snapshots.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">file.snapshots.listTagBindings</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.viewer" class="role-title add-link" data-text="Cloud Filestore Viewer Beta" tabindex="-1">Cloud Filestore Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p>Read-only access to Filestore instances and related resources.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">file.backups.get</code></p>
<p><code dir="ltr" translate="no">file.backups.list</code></p>
<p><code dir="ltr" translate="no">file.backups.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">file.backups.listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.backups.useReadOnly</code></p>
<p><code dir="ltr" translate="no">file.instances.get</code></p>
<p><code dir="ltr" translate="no">file.instances.list</code></p>
<p><code dir="ltr" translate="no">file.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">file.instances.listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">file.locations.get</code></li>
<li><code dir="ltr" translate="no">file.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">file.operations.get</code></p>
<p><code dir="ltr" translate="no">file.operations.list</code></p>
<p><code dir="ltr" translate="no">file.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">file.snapshots.listTagBindings</code></p></td>
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
<td><h4 id="file.serviceAgent" class="role-title add-link" data-text="Cloud Filestore Service Agent" tabindex="-1">Cloud Filestore Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  file.serviceAgent</code> )</p>
<p>Gives Cloud Filestore service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.addPeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.removePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.update</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePeering</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Filestore permissions

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
<td><h4 id="file.backups.create" class="permission-name add-link" data-text="file.backups.create" tabindex="-1"><code dir="ltr" translate="no">file.backups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.filestoreOperator">Backup and DR Filestore Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.filestoreOperator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.backups.createTagBinding" class="permission-name add-link" data-text="file.backups.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">file.backups.createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.backups.delete" class="permission-name add-link" data-text="file.backups.delete" tabindex="-1"><code dir="ltr" translate="no">file.backups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.backups.deleteTagBinding" class="permission-name add-link" data-text="file.backups.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">file.backups.deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.backups.get" class="permission-name add-link" data-text="file.backups.get" tabindex="-1"><code dir="ltr" translate="no">file.backups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.backups.list" class="permission-name add-link" data-text="file.backups.list" tabindex="-1"><code dir="ltr" translate="no">file.backups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.backups.listEffectiveTags" class="permission-name add-link" data-text="file.backups.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">file.backups.listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.backups.listTagBindings" class="permission-name add-link" data-text="file.backups.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">file.backups.listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.backups.update" class="permission-name add-link" data-text="file.backups.update" tabindex="-1"><code dir="ltr" translate="no">file.backups.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.backups.useReadOnly" class="permission-name add-link" data-text="file.backups.useReadOnly" tabindex="-1"><code dir="ltr" translate="no">file.backups.useReadOnly</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.instances.create" class="permission-name add-link" data-text="file.instances.create" tabindex="-1"><code dir="ltr" translate="no">file.instances.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.instances.createCrossProjectBackup" class="permission-name add-link" data-text="file.instances.createCrossProjectBackup" tabindex="-1"><code dir="ltr" translate="no">file.  instances.  createCrossProjectBackup</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.filestoreOperator">Backup and DR Filestore Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.filestoreOperator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.instances.createTagBinding" class="permission-name add-link" data-text="file.instances.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">file.  instances.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.instances.delete" class="permission-name add-link" data-text="file.instances.delete" tabindex="-1"><code dir="ltr" translate="no">file.instances.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.instances.deleteTagBinding" class="permission-name add-link" data-text="file.instances.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">file.  instances.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.instances.get" class="permission-name add-link" data-text="file.instances.get" tabindex="-1"><code dir="ltr" translate="no">file.instances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.filestoreOperator">Backup and DR Filestore Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.filestoreOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.instances.list" class="permission-name add-link" data-text="file.instances.list" tabindex="-1"><code dir="ltr" translate="no">file.instances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.instances.listEffectiveTags" class="permission-name add-link" data-text="file.instances.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">file.  instances.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.instances.listTagBindings" class="permission-name add-link" data-text="file.instances.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">file.instances.listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.instances.restore" class="permission-name add-link" data-text="file.instances.restore" tabindex="-1"><code dir="ltr" translate="no">file.instances.restore</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.instances.revert" class="permission-name add-link" data-text="file.instances.revert" tabindex="-1"><code dir="ltr" translate="no">file.instances.revert</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.instances.update" class="permission-name add-link" data-text="file.instances.update" tabindex="-1"><code dir="ltr" translate="no">file.instances.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.locations.get" class="permission-name add-link" data-text="file.locations.get" tabindex="-1"><code dir="ltr" translate="no">file.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.locations.list" class="permission-name add-link" data-text="file.locations.list" tabindex="-1"><code dir="ltr" translate="no">file.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.operations.cancel" class="permission-name add-link" data-text="file.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">file.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.operations.delete" class="permission-name add-link" data-text="file.operations.delete" tabindex="-1"><code dir="ltr" translate="no">file.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.operations.get" class="permission-name add-link" data-text="file.operations.get" tabindex="-1"><code dir="ltr" translate="no">file.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.operations.list" class="permission-name add-link" data-text="file.operations.list" tabindex="-1"><code dir="ltr" translate="no">file.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.snapshots.createTagBinding" class="permission-name add-link" data-text="file.snapshots.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">file.  snapshots.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.snapshots.deleteTagBinding" class="permission-name add-link" data-text="file.snapshots.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">file.  snapshots.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="file.snapshots.listEffectiveTags" class="permission-name add-link" data-text="file.snapshots.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">file.  snapshots.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="file.snapshots.listTagBindings" class="permission-name add-link" data-text="file.snapshots.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">file.snapshots.listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
