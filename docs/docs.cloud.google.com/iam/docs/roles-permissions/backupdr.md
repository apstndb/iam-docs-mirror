---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/backupdr
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr
title: Backup and Disaster Recovery roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Backup and Disaster Recovery. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Backup and Disaster Recovery roles

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
<td><h4 id="backupdr.admin" class="role-title add-link" data-text="Backup and DR Admin" tabindex="-1">Backup and DR Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p>Provides full access to all Backup and DR resources.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  list</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForFilestoreInstance</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.backupPlanRevisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  get</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.backupPlans.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.backupPlans.create</code></li>
<li><code dir="ltr" translate="no">backupdr.backupPlans.delete</code></li>
<li><code dir="ltr" translate="no">backupdr.backupPlans.get</code></li>
<li><code dir="ltr" translate="no">backupdr.backupPlans.list</code></li>
<li><code dir="ltr" translate="no">backupdr.backupPlans.update</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForFilestoreInstance</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.backupVaults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  backupVaults.  associate</code></li>
<li><code dir="ltr" translate="no">backupdr.backupVaults.create</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupVaults.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">backupdr.backupVaults.delete</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupVaults.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">backupdr.backupVaults.get</code></li>
<li><code dir="ltr" translate="no">backupdr.backupVaults.list</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupVaults.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupVaults.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">backupdr.backupVaults.update</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.bvbackups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.bvbackups.delete</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.bvbackups.get</code></li>
<li><code dir="ltr" translate="no">backupdr.bvbackups.list</code></li>
<li><code dir="ltr" translate="no">backupdr.bvbackups.restore</code></li>
<li><code dir="ltr" translate="no">backupdr.bvbackups.update</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForFilestoreInstance</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  abandonBackup</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  fetchAccessToken</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  finalizeBackup</code></li>
<li><code dir="ltr" translate="no">backupdr.bvdataSources.get</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  initiateBackup</code></li>
<li><code dir="ltr" translate="no">backupdr.bvdataSources.list</code></li>
<li><code dir="ltr" translate="no">backupdr.bvdataSources.remove</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  setInternalStatus</code></li>
<li><code dir="ltr" translate="no">backupdr.bvdataSources.update</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForCloudSqlInstance</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.  compute.  restoreFromBackupVault</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.locations.get</code></li>
<li><code dir="ltr" translate="no">backupdr.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.managementServers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  access</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  accessSensitiveData</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  assignBackupPlans</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  backupAccess</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  create</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  createConnection</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  createDynamicProtection</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  delete</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  deleteDynamicProtection</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">backupdr.managementServers.get</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  getDynamicProtection</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  list</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  listDynamicProtection</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageApplications</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageBackupPlans</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageBackupServers</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageBackups</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageClones</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageExpiration</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageHosts</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageInternalACL</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageJobs</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageLiveClones</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageMigrations</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageMirroring</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageMounts</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageRestores</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageSensitiveData</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageStorage</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageSystem</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  manageWorkflows</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  refreshWorkflows</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  runWorkflows</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  testFailOvers</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupPlans</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupServers</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  viewReports</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  viewStorage</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  viewSystem</code></li>
<li><code dir="ltr" translate="no">backupdr.  managementServers.  viewWorkflows</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.operations.cancel</code></li>
<li><code dir="ltr" translate="no">backupdr.operations.delete</code></li>
<li><code dir="ltr" translate="no">backupdr.operations.get</code></li>
<li><code dir="ltr" translate="no">backupdr.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.  serviceConfig.  initialize</code></p>
<p><code dir="ltr" translate="no">backupdr.trial.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.trial.end</code></li>
<li><code dir="ltr" translate="no">backupdr.trial.get</code></li>
<li><code dir="ltr" translate="no">backupdr.trial.subscribe</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.editor" class="role-title add-link" data-text="Backupdr Editor" tabindex="-1">Backupdr Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p>Editor role for backupdr</p></td>
<td><p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  list</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForFilestoreInstance</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.backupPlanRevisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  get</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.backupPlans.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.backupPlans.create</code></li>
<li><code dir="ltr" translate="no">backupdr.backupPlans.delete</code></li>
<li><code dir="ltr" translate="no">backupdr.backupPlans.get</code></li>
<li><code dir="ltr" translate="no">backupdr.backupPlans.list</code></li>
<li><code dir="ltr" translate="no">backupdr.backupPlans.update</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForFilestoreInstance</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  associate</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.create</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.delete</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.update</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.bvbackups.delete</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.bvbackups.get</code></li>
<li><code dir="ltr" translate="no">backupdr.bvbackups.list</code></li>
<li><code dir="ltr" translate="no">backupdr.bvbackups.restore</code></li>
<li><code dir="ltr" translate="no">backupdr.bvbackups.update</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForFilestoreInstance</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  abandonBackup</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  fetchAccessToken</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  finalizeBackup</code></li>
<li><code dir="ltr" translate="no">backupdr.bvdataSources.get</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  initiateBackup</code></li>
<li><code dir="ltr" translate="no">backupdr.bvdataSources.list</code></li>
<li><code dir="ltr" translate="no">backupdr.bvdataSources.remove</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  setInternalStatus</code></li>
<li><code dir="ltr" translate="no">backupdr.bvdataSources.update</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForCloudSqlInstance</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.  compute.  restoreFromBackupVault</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.locations.get</code></li>
<li><code dir="ltr" translate="no">backupdr.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  access</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  accessSensitiveData</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  assignBackupPlans</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  backupAccess</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  create</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  createConnection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  createDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  delete</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  deleteDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.managementServers.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  getDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageApplications</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageBackupPlans</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageBackupServers</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageBackups</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageClones</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageExpiration</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageHosts</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageInternalACL</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageJobs</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageLiveClones</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageMigrations</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageMirroring</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageMounts</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageRestores</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageStorage</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageSystem</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  refreshWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  runWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  testFailOvers</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupPlans</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupServers</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewReports</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewStorage</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewSystem</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.operations.cancel</code></li>
<li><code dir="ltr" translate="no">backupdr.operations.delete</code></li>
<li><code dir="ltr" translate="no">backupdr.operations.get</code></li>
<li><code dir="ltr" translate="no">backupdr.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.  serviceConfig.  initialize</code></p>
<p><code dir="ltr" translate="no">backupdr.trial.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.trial.end</code></li>
<li><code dir="ltr" translate="no">backupdr.trial.get</code></li>
<li><code dir="ltr" translate="no">backupdr.trial.subscribe</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.viewer" class="role-title add-link" data-text="Backup and DR Viewer" tabindex="-1">Backup and DR Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p>Provides read-only access to all Backup and DR resources.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlanRevisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  get</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.get</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.get</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.locations.get</code></li>
<li><code dir="ltr" translate="no">backupdr.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  access</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  backupAccess</code></p>
<p><code dir="ltr" translate="no">backupdr.managementServers.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  getDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupPlans</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupServers</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewReports</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewStorage</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewSystem</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.trial.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.alloydbOperator" class="role-title add-link" data-text="Backup and DR AlloyDB Operator" tabindex="-1">Backup and DR AlloyDB Operator</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.alloydbOperator</code> )</p>
<p>Allows a Backup and DR service account to discover and backup AlloyDB clusters.</p></td>
<td><p><code dir="ltr" translate="no">alloydb.operations.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupConfigViewer" class="role-title add-link" data-text="Backup and DR Backup Config Viewer" tabindex="-1">Backup and DR Backup Config Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.backupConfigViewer</code> )</p>
<p>Provides read access to resource backup config. Resource backup config has the metadata of a Google Cloud resource that can be backed up, along with its backup configurations.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.locations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  resourceBackupConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  resourceBackupConfigs.  get</code></li>
<li><code dir="ltr" translate="no">backupdr.  resourceBackupConfigs.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupUser" class="role-title add-link" data-text="Backup and DR Backup User" tabindex="-1">Backup and DR Backup User</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p>Allows the user to apply existing backup plans. This role cannot create backup plans or restore from a backup.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  list</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForFilestoreInstance</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.backupPlanRevisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  get</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.get</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.get</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.locations.get</code></li>
<li><code dir="ltr" translate="no">backupdr.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  access</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  assignBackupPlans</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  createDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  deleteDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.managementServers.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  getDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageApplications</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageBackups</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageHosts</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupPlans</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewReports</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewStorage</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewSystem</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupvaultAccessor" class="role-title add-link" data-text="Backup and DR Backup Vault Accessor" tabindex="-1">Backup and DR Backup Vault Accessor</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p>Allows the Backup Appliance permissions to create and manage backups in a backup vault.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.delete</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.get</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.update</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvdataSources.  abandonBackup</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvdataSources.  fetchAccessToken</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvdataSources.  finalizeBackup</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvdataSources.  initiateBackup</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.remove</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvdataSources.  setInternalStatus</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.update</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.operations.cancel</code></li>
<li><code dir="ltr" translate="no">backupdr.operations.delete</code></li>
<li><code dir="ltr" translate="no">backupdr.operations.get</code></li>
<li><code dir="ltr" translate="no">backupdr.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupvaultAdmin" class="role-title add-link" data-text="Backup and DR Backup Vault Admin" tabindex="-1">Backup and DR Backup Vault Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p>Allows the Backup Appliance full administrative control of backup vault resources.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.backupVaults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  backupVaults.  associate</code></li>
<li><code dir="ltr" translate="no">backupdr.backupVaults.create</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupVaults.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">backupdr.backupVaults.delete</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupVaults.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">backupdr.backupVaults.get</code></li>
<li><code dir="ltr" translate="no">backupdr.backupVaults.list</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupVaults.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupVaults.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">backupdr.backupVaults.update</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.bvbackups.delete</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.get</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.restore</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.update</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.get</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.update</code></p>
<p><code dir="ltr" translate="no">backupdr.  compute.  restoreFromBackupVault</code></p>
<p><code dir="ltr" translate="no">backupdr.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.locations.get</code></li>
<li><code dir="ltr" translate="no">backupdr.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.operations.cancel</code></li>
<li><code dir="ltr" translate="no">backupdr.operations.delete</code></li>
<li><code dir="ltr" translate="no">backupdr.operations.get</code></li>
<li><code dir="ltr" translate="no">backupdr.operations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupvaultLister" class="role-title add-link" data-text="Backup and DR Backup Vault Lister" tabindex="-1">Backup and DR Backup Vault Lister</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.backupvaultLister</code> )</p>
<p>Allows the Backup Appliance permission to list backup vaults in a given project.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupvaultViewer" class="role-title add-link" data-text="Backup and DR Backup Vault Viewer" tabindex="-1">Backup and DR Backup Vault Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.backupvaultViewer</code> )</p>
<p>Allows read-only permissions to access backup vault resources and backups.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.get</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.get</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.list</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.cloudSqlOperator" class="role-title add-link" data-text="Backup and DR Cloud SQL Operator" tabindex="-1">Backup and DR Cloud SQL Operator</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.cloudSqlOperator</code> )</p>
<p>Allows a Backup and DR service account to discover and backup Cloud SQL instances.</p></td>
<td><p><code dir="ltr" translate="no">cloudsql.  instances.  createBackupDrBackup</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.cloudStorageOperator" class="role-title add-link" data-text="Backup and DR Cloud Storage Operator" tabindex="-1">Backup and DR Cloud Storage Operator</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.cloudStorageOperator</code> )</p>
<p>Allows a Backup and DR service account to store and manage data (backups or metadata) in Cloud Storage.</p></td>
<td><p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.computeEngineOperator" class="role-title add-link" data-text="Backup and DR Compute Engine Operator" tabindex="-1">Backup and DR Compute Engine Operator</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.computeEngineOperator</code> )</p>
<p>Allows a Backup and DR service account to discover, back up, and restore Compute Engine VM instances.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.  managementServers.  createConnection</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.addresses.use</code></p>
<p><code dir="ltr" translate="no">compute.addresses.useInternal</code></p>
<p><code dir="ltr" translate="no">compute.diskTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.diskTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.diskTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.disks.create</code></p>
<p><code dir="ltr" translate="no">compute.disks.createSnapshot</code></p>
<p><code dir="ltr" translate="no">compute.disks.delete</code></p>
<p><code dir="ltr" translate="no">compute.disks.get</code></p>
<p><code dir="ltr" translate="no">compute.disks.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.disks.use</code></p>
<p><code dir="ltr" translate="no">compute.disks.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.images.create</code></p>
<p><code dir="ltr" translate="no">compute.images.delete</code></p>
<p><code dir="ltr" translate="no">compute.images.get</code></p>
<p><code dir="ltr" translate="no">compute.images.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.instances.attachDisk</code></p>
<p><code dir="ltr" translate="no">compute.instances.create</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.instances.delete</code></p>
<p><code dir="ltr" translate="no">compute.instances.detachDisk</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  pscInterfaceCreate</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  setDeletionProtection</code></p>
<p><code dir="ltr" translate="no">compute.instances.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.instances.setMetadata</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  setServiceAccount</code></p>
<p><code dir="ltr" translate="no">compute.instances.setTags</code></p>
<p><code dir="ltr" translate="no">compute.instances.start</code></p>
<p><code dir="ltr" translate="no">compute.instances.stop</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  updateDisplayDevice</code></p>
<p><code dir="ltr" translate="no">compute.instances.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.machineTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.machineTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.nodeGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.nodeGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.nodeTemplates.get</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.resourcePolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.create</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.delete</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.get</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.zones.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.diskOperator" class="role-title add-link" data-text="Backup and DR Disk Operator" tabindex="-1">Backup and DR Disk Operator</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.diskOperator</code> )</p>
<p>Allows a Backup and DR service account to store and manage data (backups or metadata) in Disk.</p></td>
<td><p><code dir="ltr" translate="no">compute.disks.create</code></p>
<p><code dir="ltr" translate="no">compute.disks.createSnapshot</code></p>
<p><code dir="ltr" translate="no">compute.disks.createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.disks.get</code></p>
<p><code dir="ltr" translate="no">compute.disks.list</code></p>
<p><code dir="ltr" translate="no">compute.disks.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.disks.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.use</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.filestoreOperator" class="role-title add-link" data-text="Backup and DR Filestore Operator Beta" tabindex="-1">Backup and DR Filestore Operator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.filestoreOperator</code> )</p>
<p>Allows a Backup and DR service account to discover and backup Filestore instances.</p></td>
<td><p><code dir="ltr" translate="no">file.backups.create</code></p>
<p><code dir="ltr" translate="no">file.  instances.  createCrossProjectBackup</code></p>
<p><code dir="ltr" translate="no">file.instances.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServerAccessor" class="role-title add-link" data-text="Backup and DR Management Server Accessor" tabindex="-1">Backup and DR Management Server Accessor</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.managementServerAccessor</code> )</p>
<p>Grants the Backup and DR management server access role to Backup Appliances.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.  managementServers.  createConnection</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.mountUser" class="role-title add-link" data-text="Backup and DR Mount User" tabindex="-1">Backup and DR Mount User</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p>Allows the user to mount from a backup. This role cannot create a backup plan or restore from a backup.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.locations.get</code></li>
<li><code dir="ltr" translate="no">backupdr.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  access</code></p>
<p><code dir="ltr" translate="no">backupdr.managementServers.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  getDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageApplications</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageClones</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageHosts</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageLiveClones</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageMirroring</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageMounts</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  refreshWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  runWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupPlans</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewReports</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewStorage</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewSystem</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.restoreUser" class="role-title add-link" data-text="Backup and DR Restore User" tabindex="-1">Backup and DR Restore User</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p>Allows the user to restore or mount from a backup. This role cannot create a backup plan.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.get</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.restore</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.get</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  compute.  restoreFromBackupVault</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.locations.get</code></li>
<li><code dir="ltr" translate="no">backupdr.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  access</code></p>
<p><code dir="ltr" translate="no">backupdr.managementServers.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  getDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageApplications</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageClones</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageHosts</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageLiveClones</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageMigrations</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageMirroring</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageMounts</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageRestores</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  refreshWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  runWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  testFailOvers</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupPlans</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewReports</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewStorage</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewSystem</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.user" class="role-title add-link" data-text="Backup and DR User" tabindex="-1">Backup and DR User</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p>Provides access to management console. Granular Backup and DR permissions depend on ACL configuration provided by Backup and DR admin within the management console.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  access</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  backupAccess</code></p>
<p><code dir="ltr" translate="no">backupdr.managementServers.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  getDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupPlans</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupServers</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewReports</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewStorage</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewSystem</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.trial.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.userv2" class="role-title add-link" data-text="Backup and DR User V2" tabindex="-1">Backup and DR User V2</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p>Provides full access to Backup and DR resources except deploying and managing backup infrastructure, expiring backups, changing data sensitivity and configuring on-premises billing.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  list</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForFilestoreInstance</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.backupPlanRevisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  get</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.backupPlans.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.backupPlans.create</code></li>
<li><code dir="ltr" translate="no">backupdr.backupPlans.delete</code></li>
<li><code dir="ltr" translate="no">backupdr.backupPlans.get</code></li>
<li><code dir="ltr" translate="no">backupdr.backupPlans.list</code></li>
<li><code dir="ltr" translate="no">backupdr.backupPlans.update</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeDisk</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  backupPlans.  useForFilestoreInstance</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  associate</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.get</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.list</code></p>
<p><code dir="ltr" translate="no">backupdr.bvbackups.restore</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForFilestoreInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.get</code></p>
<p><code dir="ltr" translate="no">backupdr.bvdataSources.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  compute.  restoreFromBackupVault</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForAlloydbCluster</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForCloudSqlInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForFilestoreInstance</code></li>
<li><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">backupdr.locations.get</code></li>
<li><code dir="ltr" translate="no">backupdr.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  access</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  assignBackupPlans</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  backupAccess</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  createDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  deleteDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.managementServers.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  getDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listDynamicProtection</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageApplications</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageBackupPlans</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageBackups</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageClones</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageHosts</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageJobs</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageLiveClones</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageMigrations</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageMirroring</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageMounts</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageRestores</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  manageWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  refreshWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  runWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  testFailOvers</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupPlans</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupServers</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewReports</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewStorage</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewSystem</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  viewWorkflows</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.trial.get</code></p>
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
<td><h4 id="backupdr.serviceAgent" class="role-title add-link" data-text="Backup and DR Service Agent" tabindex="-1">Backup and DR Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</p>
<p>Grants the Backup and DR Service access to protect Compute Engine instances.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">alloydb.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  createBackupDrBackup</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.addresses.use</code></p>
<p><code dir="ltr" translate="no">compute.addresses.useInternal</code></p>
<p><code dir="ltr" translate="no">compute.diskTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.diskTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.diskTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.disks.create</code></p>
<p><code dir="ltr" translate="no">compute.disks.createSnapshot</code></p>
<p><code dir="ltr" translate="no">compute.disks.createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.disks.delete</code></p>
<p><code dir="ltr" translate="no">compute.disks.get</code></p>
<p><code dir="ltr" translate="no">compute.disks.list</code></p>
<p><code dir="ltr" translate="no">compute.disks.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.disks.use</code></p>
<p><code dir="ltr" translate="no">compute.disks.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.images.create</code></p>
<p><code dir="ltr" translate="no">compute.images.delete</code></p>
<p><code dir="ltr" translate="no">compute.images.get</code></p>
<p><code dir="ltr" translate="no">compute.images.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.instances.attachDisk</code></p>
<p><code dir="ltr" translate="no">compute.instances.create</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.instances.delete</code></p>
<p><code dir="ltr" translate="no">compute.instances.detachDisk</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  pscInterfaceCreate</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  setDeletionProtection</code></p>
<p><code dir="ltr" translate="no">compute.instances.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.instances.setMetadata</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  setServiceAccount</code></p>
<p><code dir="ltr" translate="no">compute.instances.setTags</code></p>
<p><code dir="ltr" translate="no">compute.instances.start</code></p>
<p><code dir="ltr" translate="no">compute.instances.stop</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  updateDisplayDevice</code></p>
<p><code dir="ltr" translate="no">compute.instances.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.machineTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.machineTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.nodeGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.nodeGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.nodeTemplates.get</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.resourcePolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.create</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.delete</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.get</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.use</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.zones.list</code></p>
<p><code dir="ltr" translate="no">file.backups.create</code></p>
<p><code dir="ltr" translate="no">file.  instances.  createCrossProjectBackup</code></p>
<p><code dir="ltr" translate="no">file.instances.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">netapp.operations.get</code></p>
<p><code dir="ltr" translate="no">netapp.volumes.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Backup and Disaster Recovery permissions

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
<td><h4 id="backupdr.backupPlanAssociations.createForAlloydbCluster" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.createForAlloydbCluster" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForAlloydbCluster</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.createForCloudSqlInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.createForCloudSqlInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForCloudSqlInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanAssociations.createForComputeDisk" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.createForComputeDisk" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeDisk</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.createForComputeInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.createForComputeInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanAssociations.createForFilestoreInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.createForFilestoreInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForFilestoreInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.deleteForAlloydbCluster" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.deleteForAlloydbCluster" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForAlloydbCluster</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanAssociations.deleteForCloudSqlInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.deleteForCloudSqlInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForCloudSqlInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.deleteForComputeDisk" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.deleteForComputeDisk" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeDisk</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanAssociations.deleteForComputeInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.deleteForComputeInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.deleteForFilestoreInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.deleteForFilestoreInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForFilestoreInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanAssociations.fetchForAlloydbCluster" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.fetchForAlloydbCluster" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForAlloydbCluster</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.fetchForCloudSqlInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.fetchForCloudSqlInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForCloudSqlInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanAssociations.fetchForComputeDisk" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.fetchForComputeDisk" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeDisk</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.fetchForComputeInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.fetchForComputeInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanAssociations.fetchForFilestoreInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.fetchForFilestoreInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForFilestoreInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
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
<td><h4 id="backupdr.backupPlanAssociations.getForAlloydbCluster" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.getForAlloydbCluster" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForAlloydbCluster</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanAssociations.getForCloudSqlInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.getForCloudSqlInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForCloudSqlInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.getForComputeDisk" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.getForComputeDisk" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeDisk</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanAssociations.getForComputeInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.getForComputeInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.getForFilestoreInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.getForFilestoreInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForFilestoreInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
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
<td><h4 id="backupdr.backupPlanAssociations.list" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.list" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.triggerBackupForAlloydbCluster" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.triggerBackupForAlloydbCluster" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForAlloydbCluster</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanAssociations.triggerBackupForCloudSqlInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.triggerBackupForCloudSqlInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForCloudSqlInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.triggerBackupForComputeDisk" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.triggerBackupForComputeDisk" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeDisk</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanAssociations.triggerBackupForComputeInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.triggerBackupForComputeInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.triggerBackupForFilestoreInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.triggerBackupForFilestoreInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForFilestoreInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanAssociations.updateForAlloydbCluster" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.updateForAlloydbCluster" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForAlloydbCluster</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.updateForComputeDisk" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.updateForComputeDisk" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeDisk</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanAssociations.updateForComputeInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.updateForComputeInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanAssociations.updateForFilestoreInstance" class="permission-name add-link" data-text="backupdr.backupPlanAssociations.updateForFilestoreInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForFilestoreInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlanRevisions.get" class="permission-name add-link" data-text="backupdr.backupPlanRevisions.get" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlanRevisions.list" class="permission-name add-link" data-text="backupdr.backupPlanRevisions.list" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlanRevisions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlans.create" class="permission-name add-link" data-text="backupdr.backupPlans.create" tabindex="-1"><code dir="ltr" translate="no">backupdr.backupPlans.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlans.delete" class="permission-name add-link" data-text="backupdr.backupPlans.delete" tabindex="-1"><code dir="ltr" translate="no">backupdr.backupPlans.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlans.get" class="permission-name add-link" data-text="backupdr.backupPlans.get" tabindex="-1"><code dir="ltr" translate="no">backupdr.backupPlans.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlans.list" class="permission-name add-link" data-text="backupdr.backupPlans.list" tabindex="-1"><code dir="ltr" translate="no">backupdr.backupPlans.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlans.update" class="permission-name add-link" data-text="backupdr.backupPlans.update" tabindex="-1"><code dir="ltr" translate="no">backupdr.backupPlans.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlans.useForAlloydbCluster" class="permission-name add-link" data-text="backupdr.backupPlans.useForAlloydbCluster" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlans.  useForAlloydbCluster</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlans.useForCloudSqlInstance" class="permission-name add-link" data-text="backupdr.backupPlans.useForCloudSqlInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlans.  useForCloudSqlInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlans.useForComputeDisk" class="permission-name add-link" data-text="backupdr.backupPlans.useForComputeDisk" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeDisk</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupPlans.useForComputeInstance" class="permission-name add-link" data-text="backupdr.backupPlans.useForComputeInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupPlans.useForFilestoreInstance" class="permission-name add-link" data-text="backupdr.backupPlans.useForFilestoreInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupPlans.  useForFilestoreInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupVaults.associate" class="permission-name add-link" data-text="backupdr.backupVaults.associate" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupVaults.  associate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupVaults.create" class="permission-name add-link" data-text="backupdr.backupVaults.create" tabindex="-1"><code dir="ltr" translate="no">backupdr.backupVaults.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupVaults.createTagBinding" class="permission-name add-link" data-text="backupdr.backupVaults.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupVaults.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupVaults.delete" class="permission-name add-link" data-text="backupdr.backupVaults.delete" tabindex="-1"><code dir="ltr" translate="no">backupdr.backupVaults.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupVaults.deleteTagBinding" class="permission-name add-link" data-text="backupdr.backupVaults.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupVaults.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupVaults.get" class="permission-name add-link" data-text="backupdr.backupVaults.get" tabindex="-1"><code dir="ltr" translate="no">backupdr.backupVaults.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupVaults.list" class="permission-name add-link" data-text="backupdr.backupVaults.list" tabindex="-1"><code dir="ltr" translate="no">backupdr.backupVaults.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultLister">Backup and DR Backup Vault Lister</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultLister</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupVaults.listEffectiveTags" class="permission-name add-link" data-text="backupdr.backupVaults.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupVaults.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.backupVaults.listTagBindings" class="permission-name add-link" data-text="backupdr.backupVaults.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">backupdr.  backupVaults.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.backupVaults.update" class="permission-name add-link" data-text="backupdr.backupVaults.update" tabindex="-1"><code dir="ltr" translate="no">backupdr.backupVaults.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.bvbackups.delete" class="permission-name add-link" data-text="backupdr.bvbackups.delete" tabindex="-1"><code dir="ltr" translate="no">backupdr.bvbackups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.bvbackups.fetchForCloudSqlInstance" class="permission-name add-link" data-text="backupdr.bvbackups.fetchForCloudSqlInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForCloudSqlInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.bvbackups.fetchForComputeDisk" class="permission-name add-link" data-text="backupdr.bvbackups.fetchForComputeDisk" tabindex="-1"><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeDisk</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.bvbackups.fetchForComputeInstance" class="permission-name add-link" data-text="backupdr.bvbackups.fetchForComputeInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForComputeInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.bvbackups.get" class="permission-name add-link" data-text="backupdr.bvbackups.get" tabindex="-1"><code dir="ltr" translate="no">backupdr.bvbackups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.bvbackups.list" class="permission-name add-link" data-text="backupdr.bvbackups.list" tabindex="-1"><code dir="ltr" translate="no">backupdr.bvbackups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.bvbackups.restore" class="permission-name add-link" data-text="backupdr.bvbackups.restore" tabindex="-1"><code dir="ltr" translate="no">backupdr.bvbackups.restore</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.bvbackups.update" class="permission-name add-link" data-text="backupdr.bvbackups.update" tabindex="-1"><code dir="ltr" translate="no">backupdr.bvbackups.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.bvbackups.useReadOnlyForAlloydbCluster" class="permission-name add-link" data-text="backupdr.bvbackups.useReadOnlyForAlloydbCluster" tabindex="-1"><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForAlloydbCluster</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.bvbackups.useReadOnlyForCloudSqlInstance" class="permission-name add-link" data-text="backupdr.bvbackups.useReadOnlyForCloudSqlInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForCloudSqlInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.bvbackups.useReadOnlyForFilestoreInstance" class="permission-name add-link" data-text="backupdr.bvbackups.useReadOnlyForFilestoreInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForFilestoreInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.bvdataSources.abandonBackup" class="permission-name add-link" data-text="backupdr.bvdataSources.abandonBackup" tabindex="-1"><code dir="ltr" translate="no">backupdr.  bvdataSources.  abandonBackup</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.bvdataSources.fetchAccessToken" class="permission-name add-link" data-text="backupdr.bvdataSources.fetchAccessToken" tabindex="-1"><code dir="ltr" translate="no">backupdr.  bvdataSources.  fetchAccessToken</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.bvdataSources.finalizeBackup" class="permission-name add-link" data-text="backupdr.bvdataSources.finalizeBackup" tabindex="-1"><code dir="ltr" translate="no">backupdr.  bvdataSources.  finalizeBackup</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.bvdataSources.get" class="permission-name add-link" data-text="backupdr.bvdataSources.get" tabindex="-1"><code dir="ltr" translate="no">backupdr.bvdataSources.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.bvdataSources.initiateBackup" class="permission-name add-link" data-text="backupdr.bvdataSources.initiateBackup" tabindex="-1"><code dir="ltr" translate="no">backupdr.  bvdataSources.  initiateBackup</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.bvdataSources.list" class="permission-name add-link" data-text="backupdr.bvdataSources.list" tabindex="-1"><code dir="ltr" translate="no">backupdr.bvdataSources.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.bvdataSources.remove" class="permission-name add-link" data-text="backupdr.bvdataSources.remove" tabindex="-1"><code dir="ltr" translate="no">backupdr.bvdataSources.remove</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.bvdataSources.setInternalStatus" class="permission-name add-link" data-text="backupdr.bvdataSources.setInternalStatus" tabindex="-1"><code dir="ltr" translate="no">backupdr.  bvdataSources.  setInternalStatus</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.bvdataSources.update" class="permission-name add-link" data-text="backupdr.bvdataSources.update" tabindex="-1"><code dir="ltr" translate="no">backupdr.bvdataSources.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.bvdataSources.useReadOnlyForAlloydbCluster" class="permission-name add-link" data-text="backupdr.bvdataSources.useReadOnlyForAlloydbCluster" tabindex="-1"><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForAlloydbCluster</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.bvdataSources.useReadOnlyForCloudSqlInstance" class="permission-name add-link" data-text="backupdr.bvdataSources.useReadOnlyForCloudSqlInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForCloudSqlInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.compute.restoreFromBackupVault" class="permission-name add-link" data-text="backupdr.compute.restoreFromBackupVault" tabindex="-1"><code dir="ltr" translate="no">backupdr.  compute.  restoreFromBackupVault</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.dataSourceReferences.fetchForAlloydbCluster" class="permission-name add-link" data-text="backupdr.dataSourceReferences.fetchForAlloydbCluster" tabindex="-1"><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForAlloydbCluster</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.dataSourceReferences.fetchForCloudSqlInstance" class="permission-name add-link" data-text="backupdr.dataSourceReferences.fetchForCloudSqlInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForCloudSqlInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.dataSourceReferences.fetchForFilestoreInstance" class="permission-name add-link" data-text="backupdr.dataSourceReferences.fetchForFilestoreInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForFilestoreInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
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
<td><h4 id="backupdr.dataSourceReferences.getForAlloydbCluster" class="permission-name add-link" data-text="backupdr.dataSourceReferences.getForAlloydbCluster" tabindex="-1"><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForAlloydbCluster</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.dataSourceReferences.getForCloudSqlInstance" class="permission-name add-link" data-text="backupdr.dataSourceReferences.getForCloudSqlInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForCloudSqlInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.dataSourceReferences.getForFilestoreInstance" class="permission-name add-link" data-text="backupdr.dataSourceReferences.getForFilestoreInstance" tabindex="-1"><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForFilestoreInstance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
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
<td><h4 id="backupdr.dataSourceReferences.list" class="permission-name add-link" data-text="backupdr.dataSourceReferences.list" tabindex="-1"><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.locations.get" class="permission-name add-link" data-text="backupdr.locations.get" tabindex="-1"><code dir="ltr" translate="no">backupdr.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.locations.list" class="permission-name add-link" data-text="backupdr.locations.list" tabindex="-1"><code dir="ltr" translate="no">backupdr.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupConfigViewer">Backup and DR Backup Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.access" class="permission-name add-link" data-text="backupdr.managementServers.access" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  access</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.accessSensitiveData" class="permission-name add-link" data-text="backupdr.managementServers.accessSensitiveData" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  accessSensitiveData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.assignBackupPlans" class="permission-name add-link" data-text="backupdr.managementServers.assignBackupPlans" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  assignBackupPlans</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.backupAccess" class="permission-name add-link" data-text="backupdr.managementServers.backupAccess" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  backupAccess</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.create" class="permission-name add-link" data-text="backupdr.managementServers.create" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.createConnection" class="permission-name add-link" data-text="backupdr.managementServers.createConnection" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  createConnection</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.computeEngineOperator">Backup and DR Compute Engine Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.computeEngineOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.managementServerAccessor">Backup and DR Management Server Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.managementServerAccessor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.createDynamicProtection" class="permission-name add-link" data-text="backupdr.managementServers.createDynamicProtection" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  createDynamicProtection</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.createTagBinding" class="permission-name add-link" data-text="backupdr.managementServers.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.delete" class="permission-name add-link" data-text="backupdr.managementServers.delete" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.deleteDynamicProtection" class="permission-name add-link" data-text="backupdr.managementServers.deleteDynamicProtection" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  deleteDynamicProtection</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.deleteTagBinding" class="permission-name add-link" data-text="backupdr.managementServers.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.get" class="permission-name add-link" data-text="backupdr.managementServers.get" tabindex="-1"><code dir="ltr" translate="no">backupdr.managementServers.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.getDynamicProtection" class="permission-name add-link" data-text="backupdr.managementServers.getDynamicProtection" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  getDynamicProtection</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.getIamPolicy" class="permission-name add-link" data-text="backupdr.managementServers.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.list" class="permission-name add-link" data-text="backupdr.managementServers.list" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.listDynamicProtection" class="permission-name add-link" data-text="backupdr.managementServers.listDynamicProtection" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  listDynamicProtection</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.listEffectiveTags" class="permission-name add-link" data-text="backupdr.managementServers.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.listTagBindings" class="permission-name add-link" data-text="backupdr.managementServers.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.manageApplications" class="permission-name add-link" data-text="backupdr.managementServers.manageApplications" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageApplications</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.manageBackupPlans" class="permission-name add-link" data-text="backupdr.managementServers.manageBackupPlans" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageBackupPlans</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.manageBackupServers" class="permission-name add-link" data-text="backupdr.managementServers.manageBackupServers" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageBackupServers</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.manageBackups" class="permission-name add-link" data-text="backupdr.managementServers.manageBackups" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageBackups</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.manageClones" class="permission-name add-link" data-text="backupdr.managementServers.manageClones" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageClones</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.manageExpiration" class="permission-name add-link" data-text="backupdr.managementServers.manageExpiration" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageExpiration</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.manageHosts" class="permission-name add-link" data-text="backupdr.managementServers.manageHosts" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageHosts</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.manageInternalACL" class="permission-name add-link" data-text="backupdr.managementServers.manageInternalACL" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageInternalACL</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.manageJobs" class="permission-name add-link" data-text="backupdr.managementServers.manageJobs" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageJobs</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.manageLiveClones" class="permission-name add-link" data-text="backupdr.managementServers.manageLiveClones" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageLiveClones</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.manageMigrations" class="permission-name add-link" data-text="backupdr.managementServers.manageMigrations" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageMigrations</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.manageMirroring" class="permission-name add-link" data-text="backupdr.managementServers.manageMirroring" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageMirroring</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.manageMounts" class="permission-name add-link" data-text="backupdr.managementServers.manageMounts" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageMounts</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.manageRestores" class="permission-name add-link" data-text="backupdr.managementServers.manageRestores" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageRestores</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.manageSensitiveData" class="permission-name add-link" data-text="backupdr.managementServers.manageSensitiveData" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageSensitiveData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.manageStorage" class="permission-name add-link" data-text="backupdr.managementServers.manageStorage" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageStorage</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.manageSystem" class="permission-name add-link" data-text="backupdr.managementServers.manageSystem" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageSystem</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.manageWorkflows" class="permission-name add-link" data-text="backupdr.managementServers.manageWorkflows" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  manageWorkflows</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.refreshWorkflows" class="permission-name add-link" data-text="backupdr.managementServers.refreshWorkflows" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  refreshWorkflows</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.runWorkflows" class="permission-name add-link" data-text="backupdr.managementServers.runWorkflows" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  runWorkflows</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.setIamPolicy" class="permission-name add-link" data-text="backupdr.managementServers.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.testFailOvers" class="permission-name add-link" data-text="backupdr.managementServers.testFailOvers" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  testFailOvers</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.viewBackupPlans" class="permission-name add-link" data-text="backupdr.managementServers.viewBackupPlans" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupPlans</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.viewBackupServers" class="permission-name add-link" data-text="backupdr.managementServers.viewBackupServers" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  viewBackupServers</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.viewReports" class="permission-name add-link" data-text="backupdr.managementServers.viewReports" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  viewReports</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.viewStorage" class="permission-name add-link" data-text="backupdr.managementServers.viewStorage" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  viewStorage</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.managementServers.viewSystem" class="permission-name add-link" data-text="backupdr.managementServers.viewSystem" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  viewSystem</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.managementServers.viewWorkflows" class="permission-name add-link" data-text="backupdr.managementServers.viewWorkflows" tabindex="-1"><code dir="ltr" translate="no">backupdr.  managementServers.  viewWorkflows</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.operations.cancel" class="permission-name add-link" data-text="backupdr.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">backupdr.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.operations.delete" class="permission-name add-link" data-text="backupdr.operations.delete" tabindex="-1"><code dir="ltr" translate="no">backupdr.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.operations.get" class="permission-name add-link" data-text="backupdr.operations.get" tabindex="-1"><code dir="ltr" translate="no">backupdr.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.operations.list" class="permission-name add-link" data-text="backupdr.operations.list" tabindex="-1"><code dir="ltr" translate="no">backupdr.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.resourceBackupConfigs.get" class="permission-name add-link" data-text="backupdr.resourceBackupConfigs.get" tabindex="-1"><code dir="ltr" translate="no">backupdr.  resourceBackupConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupConfigViewer">Backup and DR Backup Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.resourceBackupConfigs.list" class="permission-name add-link" data-text="backupdr.resourceBackupConfigs.list" tabindex="-1"><code dir="ltr" translate="no">backupdr.  resourceBackupConfigs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupConfigViewer">Backup and DR Backup Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.backupConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.serviceConfig.initialize" class="permission-name add-link" data-text="backupdr.serviceConfig.initialize" tabindex="-1"><code dir="ltr" translate="no">backupdr.  serviceConfig.  initialize</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.legacyAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.trial.end" class="permission-name add-link" data-text="backupdr.trial.end" tabindex="-1"><code dir="ltr" translate="no">backupdr.trial.end</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="backupdr.trial.get" class="permission-name add-link" data-text="backupdr.trial.get" tabindex="-1"><code dir="ltr" translate="no">backupdr.trial.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="backupdr.trial.subscribe" class="permission-name add-link" data-text="backupdr.trial.subscribe" tabindex="-1"><code dir="ltr" translate="no">backupdr.trial.subscribe</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.editor</code> )</p></td>
</tr>
</tbody>
</table>
