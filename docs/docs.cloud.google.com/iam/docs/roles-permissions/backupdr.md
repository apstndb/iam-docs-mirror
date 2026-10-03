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
<td>Backup and DR Admin
<p>( <code>roles/ backupdr.admin</code> )</p>
<p>Provides full access to all Backup and DR resources.</p></td>
<td><p><code>backupdr. appliedAutoProtectionPolicies.*</code></p>
<ul>
<li><code>backupdr. appliedAutoProtectionPolicies. authorize</code></li>
<li><code>backupdr. appliedAutoProtectionPolicies. list</code></li>
<li><code>backupdr. appliedAutoProtectionPolicies. viewMatchingResources</code></li>
</ul>
<p><code>backupdr. autoProtectionBindings.*</code></p>
<ul>
<li><code>backupdr. autoProtectionBindings. create</code></li>
<li><code>backupdr. autoProtectionBindings. delete</code></li>
<li><code>backupdr. autoProtectionBindings. get</code></li>
<li><code>backupdr. autoProtectionBindings. list</code></li>
</ul>
<p><code>backupdr. autoProtectionPolicies.*</code></p>
<ul>
<li><code>backupdr. autoProtectionPolicies. create</code></li>
<li><code>backupdr. autoProtectionPolicies. delete</code></li>
<li><code>backupdr. autoProtectionPolicies. get</code></li>
<li><code>backupdr. autoProtectionPolicies. list</code></li>
<li><code>backupdr. autoProtectionPolicies. update</code></li>
</ul>
<p><code>backupdr. backupPlanAssociations.*</code></p>
<ul>
<li><code>backupdr. backupPlanAssociations. createForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. createForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. createForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. createForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. createForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. getForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. getForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. getForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. getForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. getForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. list</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. updateForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. updateForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. updateForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. updateForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. updateForFilestoreInstance</code></li>
</ul>
<p><code>backupdr.backupPlanRevisions.*</code></p>
<ul>
<li><code>backupdr. backupPlanRevisions. get</code></li>
<li><code>backupdr. backupPlanRevisions. list</code></li>
</ul>
<p><code>backupdr.backupPlans.*</code></p>
<ul>
<li><code>backupdr.backupPlans.create</code></li>
<li><code>backupdr.backupPlans.delete</code></li>
<li><code>backupdr.backupPlans.get</code></li>
<li><code>backupdr.backupPlans.list</code></li>
<li><code>backupdr.backupPlans.update</code></li>
<li><code>backupdr. backupPlans. useForAlloydbCluster</code></li>
<li><code>backupdr. backupPlans. useForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlans. useForComputeDisk</code></li>
<li><code>backupdr. backupPlans. useForComputeInstance</code></li>
<li><code>backupdr. backupPlans. useForFilestoreInstance</code></li>
</ul>
<p><code>backupdr.backupVaults.*</code></p>
<ul>
<li><code>backupdr. backupVaults. associate</code></li>
<li><code>backupdr.backupVaults.create</code></li>
<li><code>backupdr. backupVaults. createTagBinding</code></li>
<li><code>backupdr.backupVaults.delete</code></li>
<li><code>backupdr. backupVaults. deleteTagBinding</code></li>
<li><code>backupdr.backupVaults.get</code></li>
<li><code>backupdr.backupVaults.list</code></li>
<li><code>backupdr. backupVaults. listEffectiveTags</code></li>
<li><code>backupdr. backupVaults. listTagBindings</code></li>
<li><code>backupdr.backupVaults.update</code></li>
</ul>
<p><code>backupdr. bindingMatchingResources. list</code></p>
<p><code>backupdr.bvbackups.*</code></p>
<ul>
<li><code>backupdr.bvbackups.delete</code></li>
<li><code>backupdr. bvbackups. fetchForCloudSqlInstance</code></li>
<li><code>backupdr. bvbackups. fetchForComputeDisk</code></li>
<li><code>backupdr. bvbackups. fetchForComputeInstance</code></li>
<li><code>backupdr.bvbackups.get</code></li>
<li><code>backupdr.bvbackups.list</code></li>
<li><code>backupdr.bvbackups.restore</code></li>
<li><code>backupdr.bvbackups.update</code></li>
<li><code>backupdr. bvbackups. useReadOnlyForAlloydbCluster</code></li>
<li><code>backupdr. bvbackups. useReadOnlyForCloudSqlInstance</code></li>
<li><code>backupdr. bvbackups. useReadOnlyForFilestoreInstance</code></li>
</ul>
<p><code>backupdr.bvdataSources.*</code></p>
<ul>
<li><code>backupdr. bvdataSources. abandonBackup</code></li>
<li><code>backupdr. bvdataSources. fetchAccessToken</code></li>
<li><code>backupdr. bvdataSources. finalizeBackup</code></li>
<li><code>backupdr.bvdataSources.get</code></li>
<li><code>backupdr. bvdataSources. initiateBackup</code></li>
<li><code>backupdr.bvdataSources.list</code></li>
<li><code>backupdr.bvdataSources.remove</code></li>
<li><code>backupdr. bvdataSources. setInternalStatus</code></li>
<li><code>backupdr.bvdataSources.update</code></li>
<li><code>backupdr. bvdataSources. useReadOnlyForAlloydbCluster</code></li>
<li><code>backupdr. bvdataSources. useReadOnlyForCloudSqlInstance</code></li>
</ul>
<p><code>backupdr. compute. restoreFromBackupVault</code></p>
<p><code>backupdr. dataSourceReferences.*</code></p>
<ul>
<li><code>backupdr. dataSourceReferences. fetchForAlloydbCluster</code></li>
<li><code>backupdr. dataSourceReferences. fetchForCloudSqlInstance</code></li>
<li><code>backupdr. dataSourceReferences. fetchForFilestoreInstance</code></li>
<li><code>backupdr. dataSourceReferences. getForAlloydbCluster</code></li>
<li><code>backupdr. dataSourceReferences. getForCloudSqlInstance</code></li>
<li><code>backupdr. dataSourceReferences. getForFilestoreInstance</code></li>
<li><code>backupdr. dataSourceReferences. list</code></li>
</ul>
<p><code>backupdr.locations.*</code></p>
<ul>
<li><code>backupdr.locations.get</code></li>
<li><code>backupdr.locations.list</code></li>
</ul>
<p><code>backupdr.managementServers.*</code></p>
<ul>
<li><code>backupdr. managementServers. access</code></li>
<li><code>backupdr. managementServers. accessSensitiveData</code></li>
<li><code>backupdr. managementServers. assignBackupPlans</code></li>
<li><code>backupdr. managementServers. backupAccess</code></li>
<li><code>backupdr. managementServers. create</code></li>
<li><code>backupdr. managementServers. createConnection</code></li>
<li><code>backupdr. managementServers. createDynamicProtection</code></li>
<li><code>backupdr. managementServers. createTagBinding</code></li>
<li><code>backupdr. managementServers. delete</code></li>
<li><code>backupdr. managementServers. deleteDynamicProtection</code></li>
<li><code>backupdr. managementServers. deleteTagBinding</code></li>
<li><code>backupdr.managementServers.get</code></li>
<li><code>backupdr. managementServers. getDynamicProtection</code></li>
<li><code>backupdr. managementServers. getIamPolicy</code></li>
<li><code>backupdr. managementServers. list</code></li>
<li><code>backupdr. managementServers. listDynamicProtection</code></li>
<li><code>backupdr. managementServers. listEffectiveTags</code></li>
<li><code>backupdr. managementServers. listTagBindings</code></li>
<li><code>backupdr. managementServers. manageApplications</code></li>
<li><code>backupdr. managementServers. manageBackupPlans</code></li>
<li><code>backupdr. managementServers. manageBackupServers</code></li>
<li><code>backupdr. managementServers. manageBackups</code></li>
<li><code>backupdr. managementServers. manageClones</code></li>
<li><code>backupdr. managementServers. manageExpiration</code></li>
<li><code>backupdr. managementServers. manageHosts</code></li>
<li><code>backupdr. managementServers. manageInternalACL</code></li>
<li><code>backupdr. managementServers. manageJobs</code></li>
<li><code>backupdr. managementServers. manageLiveClones</code></li>
<li><code>backupdr. managementServers. manageMigrations</code></li>
<li><code>backupdr. managementServers. manageMirroring</code></li>
<li><code>backupdr. managementServers. manageMounts</code></li>
<li><code>backupdr. managementServers. manageRestores</code></li>
<li><code>backupdr. managementServers. manageSensitiveData</code></li>
<li><code>backupdr. managementServers. manageStorage</code></li>
<li><code>backupdr. managementServers. manageSystem</code></li>
<li><code>backupdr. managementServers. manageWorkflows</code></li>
<li><code>backupdr. managementServers. refreshWorkflows</code></li>
<li><code>backupdr. managementServers. runWorkflows</code></li>
<li><code>backupdr. managementServers. setIamPolicy</code></li>
<li><code>backupdr. managementServers. testFailOvers</code></li>
<li><code>backupdr. managementServers. viewBackupPlans</code></li>
<li><code>backupdr. managementServers. viewBackupServers</code></li>
<li><code>backupdr. managementServers. viewReports</code></li>
<li><code>backupdr. managementServers. viewStorage</code></li>
<li><code>backupdr. managementServers. viewSystem</code></li>
<li><code>backupdr. managementServers. viewWorkflows</code></li>
</ul>
<p><code>backupdr.operations.*</code></p>
<ul>
<li><code>backupdr.operations.cancel</code></li>
<li><code>backupdr.operations.delete</code></li>
<li><code>backupdr.operations.get</code></li>
<li><code>backupdr.operations.list</code></li>
</ul>
<p><code>backupdr. serviceConfig. initialize</code></p>
<p><code>backupdr.trial.*</code></p>
<ul>
<li><code>backupdr.trial.end</code></li>
<li><code>backupdr.trial.get</code></li>
<li><code>backupdr.trial.subscribe</code></li>
</ul>
<p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Backupdr Editor
<p>( <code>roles/ backupdr.editor</code> )</p>
<p>Editor role for backupdr</p></td>
<td><p><code>backupdr. appliedAutoProtectionPolicies.*</code></p>
<ul>
<li><code>backupdr. appliedAutoProtectionPolicies. authorize</code></li>
<li><code>backupdr. appliedAutoProtectionPolicies. list</code></li>
<li><code>backupdr. appliedAutoProtectionPolicies. viewMatchingResources</code></li>
</ul>
<p><code>backupdr. autoProtectionBindings.*</code></p>
<ul>
<li><code>backupdr. autoProtectionBindings. create</code></li>
<li><code>backupdr. autoProtectionBindings. delete</code></li>
<li><code>backupdr. autoProtectionBindings. get</code></li>
<li><code>backupdr. autoProtectionBindings. list</code></li>
</ul>
<p><code>backupdr. autoProtectionPolicies.*</code></p>
<ul>
<li><code>backupdr. autoProtectionPolicies. create</code></li>
<li><code>backupdr. autoProtectionPolicies. delete</code></li>
<li><code>backupdr. autoProtectionPolicies. get</code></li>
<li><code>backupdr. autoProtectionPolicies. list</code></li>
<li><code>backupdr. autoProtectionPolicies. update</code></li>
</ul>
<p><code>backupdr. backupPlanAssociations.*</code></p>
<ul>
<li><code>backupdr. backupPlanAssociations. createForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. createForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. createForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. createForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. createForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. getForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. getForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. getForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. getForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. getForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. list</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. updateForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. updateForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. updateForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. updateForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. updateForFilestoreInstance</code></li>
</ul>
<p><code>backupdr.backupPlanRevisions.*</code></p>
<ul>
<li><code>backupdr. backupPlanRevisions. get</code></li>
<li><code>backupdr. backupPlanRevisions. list</code></li>
</ul>
<p><code>backupdr.backupPlans.*</code></p>
<ul>
<li><code>backupdr.backupPlans.create</code></li>
<li><code>backupdr.backupPlans.delete</code></li>
<li><code>backupdr.backupPlans.get</code></li>
<li><code>backupdr.backupPlans.list</code></li>
<li><code>backupdr.backupPlans.update</code></li>
<li><code>backupdr. backupPlans. useForAlloydbCluster</code></li>
<li><code>backupdr. backupPlans. useForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlans. useForComputeDisk</code></li>
<li><code>backupdr. backupPlans. useForComputeInstance</code></li>
<li><code>backupdr. backupPlans. useForFilestoreInstance</code></li>
</ul>
<p><code>backupdr. backupVaults. associate</code></p>
<p><code>backupdr.backupVaults.create</code></p>
<p><code>backupdr.backupVaults.delete</code></p>
<p><code>backupdr.backupVaults.get</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr. backupVaults. listEffectiveTags</code></p>
<p><code>backupdr. backupVaults. listTagBindings</code></p>
<p><code>backupdr.backupVaults.update</code></p>
<p><code>backupdr. bindingMatchingResources. list</code></p>
<p><code>backupdr.bvbackups.*</code></p>
<ul>
<li><code>backupdr.bvbackups.delete</code></li>
<li><code>backupdr. bvbackups. fetchForCloudSqlInstance</code></li>
<li><code>backupdr. bvbackups. fetchForComputeDisk</code></li>
<li><code>backupdr. bvbackups. fetchForComputeInstance</code></li>
<li><code>backupdr.bvbackups.get</code></li>
<li><code>backupdr.bvbackups.list</code></li>
<li><code>backupdr.bvbackups.restore</code></li>
<li><code>backupdr.bvbackups.update</code></li>
<li><code>backupdr. bvbackups. useReadOnlyForAlloydbCluster</code></li>
<li><code>backupdr. bvbackups. useReadOnlyForCloudSqlInstance</code></li>
<li><code>backupdr. bvbackups. useReadOnlyForFilestoreInstance</code></li>
</ul>
<p><code>backupdr.bvdataSources.*</code></p>
<ul>
<li><code>backupdr. bvdataSources. abandonBackup</code></li>
<li><code>backupdr. bvdataSources. fetchAccessToken</code></li>
<li><code>backupdr. bvdataSources. finalizeBackup</code></li>
<li><code>backupdr.bvdataSources.get</code></li>
<li><code>backupdr. bvdataSources. initiateBackup</code></li>
<li><code>backupdr.bvdataSources.list</code></li>
<li><code>backupdr.bvdataSources.remove</code></li>
<li><code>backupdr. bvdataSources. setInternalStatus</code></li>
<li><code>backupdr.bvdataSources.update</code></li>
<li><code>backupdr. bvdataSources. useReadOnlyForAlloydbCluster</code></li>
<li><code>backupdr. bvdataSources. useReadOnlyForCloudSqlInstance</code></li>
</ul>
<p><code>backupdr. compute. restoreFromBackupVault</code></p>
<p><code>backupdr. dataSourceReferences.*</code></p>
<ul>
<li><code>backupdr. dataSourceReferences. fetchForAlloydbCluster</code></li>
<li><code>backupdr. dataSourceReferences. fetchForCloudSqlInstance</code></li>
<li><code>backupdr. dataSourceReferences. fetchForFilestoreInstance</code></li>
<li><code>backupdr. dataSourceReferences. getForAlloydbCluster</code></li>
<li><code>backupdr. dataSourceReferences. getForCloudSqlInstance</code></li>
<li><code>backupdr. dataSourceReferences. getForFilestoreInstance</code></li>
<li><code>backupdr. dataSourceReferences. list</code></li>
</ul>
<p><code>backupdr.locations.*</code></p>
<ul>
<li><code>backupdr.locations.get</code></li>
<li><code>backupdr.locations.list</code></li>
</ul>
<p><code>backupdr. managementServers. access</code></p>
<p><code>backupdr. managementServers. accessSensitiveData</code></p>
<p><code>backupdr. managementServers. assignBackupPlans</code></p>
<p><code>backupdr. managementServers. backupAccess</code></p>
<p><code>backupdr. managementServers. create</code></p>
<p><code>backupdr. managementServers. createConnection</code></p>
<p><code>backupdr. managementServers. createDynamicProtection</code></p>
<p><code>backupdr. managementServers. delete</code></p>
<p><code>backupdr. managementServers. deleteDynamicProtection</code></p>
<p><code>backupdr.managementServers.get</code></p>
<p><code>backupdr. managementServers. getDynamicProtection</code></p>
<p><code>backupdr. managementServers. getIamPolicy</code></p>
<p><code>backupdr. managementServers. list</code></p>
<p><code>backupdr. managementServers. listDynamicProtection</code></p>
<p><code>backupdr. managementServers. listEffectiveTags</code></p>
<p><code>backupdr. managementServers. listTagBindings</code></p>
<p><code>backupdr. managementServers. manageApplications</code></p>
<p><code>backupdr. managementServers. manageBackupPlans</code></p>
<p><code>backupdr. managementServers. manageBackupServers</code></p>
<p><code>backupdr. managementServers. manageBackups</code></p>
<p><code>backupdr. managementServers. manageClones</code></p>
<p><code>backupdr. managementServers. manageExpiration</code></p>
<p><code>backupdr. managementServers. manageHosts</code></p>
<p><code>backupdr. managementServers. manageInternalACL</code></p>
<p><code>backupdr. managementServers. manageJobs</code></p>
<p><code>backupdr. managementServers. manageLiveClones</code></p>
<p><code>backupdr. managementServers. manageMigrations</code></p>
<p><code>backupdr. managementServers. manageMirroring</code></p>
<p><code>backupdr. managementServers. manageMounts</code></p>
<p><code>backupdr. managementServers. manageRestores</code></p>
<p><code>backupdr. managementServers. manageStorage</code></p>
<p><code>backupdr. managementServers. manageSystem</code></p>
<p><code>backupdr. managementServers. manageWorkflows</code></p>
<p><code>backupdr. managementServers. refreshWorkflows</code></p>
<p><code>backupdr. managementServers. runWorkflows</code></p>
<p><code>backupdr. managementServers. testFailOvers</code></p>
<p><code>backupdr. managementServers. viewBackupPlans</code></p>
<p><code>backupdr. managementServers. viewBackupServers</code></p>
<p><code>backupdr. managementServers. viewReports</code></p>
<p><code>backupdr. managementServers. viewStorage</code></p>
<p><code>backupdr. managementServers. viewSystem</code></p>
<p><code>backupdr. managementServers. viewWorkflows</code></p>
<p><code>backupdr.operations.*</code></p>
<ul>
<li><code>backupdr.operations.cancel</code></li>
<li><code>backupdr.operations.delete</code></li>
<li><code>backupdr.operations.get</code></li>
<li><code>backupdr.operations.list</code></li>
</ul>
<p><code>backupdr. serviceConfig. initialize</code></p>
<p><code>backupdr.trial.*</code></p>
<ul>
<li><code>backupdr.trial.end</code></li>
<li><code>backupdr.trial.get</code></li>
<li><code>backupdr.trial.subscribe</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Backup and DR Viewer
<p>( <code>roles/ backupdr.viewer</code> )</p>
<p>Provides read-only access to all Backup and DR resources.</p></td>
<td><p><code>backupdr. appliedAutoProtectionPolicies. list</code></p>
<p><code>backupdr. appliedAutoProtectionPolicies. viewMatchingResources</code></p>
<p><code>backupdr. autoProtectionBindings. get</code></p>
<p><code>backupdr. autoProtectionBindings. list</code></p>
<p><code>backupdr. autoProtectionPolicies. get</code></p>
<p><code>backupdr. autoProtectionPolicies. list</code></p>
<p><code>backupdr. backupPlanAssociations. fetchForAlloydbCluster</code></p>
<p><code>backupdr. backupPlanAssociations. fetchForCloudSqlInstance</code></p>
<p><code>backupdr. backupPlanAssociations. fetchForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. fetchForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. fetchForFilestoreInstance</code></p>
<p><code>backupdr. backupPlanAssociations. getForAlloydbCluster</code></p>
<p><code>backupdr. backupPlanAssociations. getForCloudSqlInstance</code></p>
<p><code>backupdr. backupPlanAssociations. getForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. getForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. getForFilestoreInstance</code></p>
<p><code>backupdr. backupPlanAssociations. list</code></p>
<p><code>backupdr.backupPlanRevisions.*</code></p>
<ul>
<li><code>backupdr. backupPlanRevisions. get</code></li>
<li><code>backupdr. backupPlanRevisions. list</code></li>
</ul>
<p><code>backupdr.backupPlans.get</code></p>
<p><code>backupdr.backupPlans.list</code></p>
<p><code>backupdr.backupVaults.get</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr. backupVaults. listEffectiveTags</code></p>
<p><code>backupdr. backupVaults. listTagBindings</code></p>
<p><code>backupdr. bindingMatchingResources. list</code></p>
<p><code>backupdr. bvbackups. fetchForCloudSqlInstance</code></p>
<p><code>backupdr. bvbackups. fetchForComputeDisk</code></p>
<p><code>backupdr. bvbackups. fetchForComputeInstance</code></p>
<p><code>backupdr.bvbackups.get</code></p>
<p><code>backupdr.bvbackups.list</code></p>
<p><code>backupdr.bvdataSources.get</code></p>
<p><code>backupdr.bvdataSources.list</code></p>
<p><code>backupdr. dataSourceReferences.*</code></p>
<ul>
<li><code>backupdr. dataSourceReferences. fetchForAlloydbCluster</code></li>
<li><code>backupdr. dataSourceReferences. fetchForCloudSqlInstance</code></li>
<li><code>backupdr. dataSourceReferences. fetchForFilestoreInstance</code></li>
<li><code>backupdr. dataSourceReferences. getForAlloydbCluster</code></li>
<li><code>backupdr. dataSourceReferences. getForCloudSqlInstance</code></li>
<li><code>backupdr. dataSourceReferences. getForFilestoreInstance</code></li>
<li><code>backupdr. dataSourceReferences. list</code></li>
</ul>
<p><code>backupdr.locations.*</code></p>
<ul>
<li><code>backupdr.locations.get</code></li>
<li><code>backupdr.locations.list</code></li>
</ul>
<p><code>backupdr. managementServers. access</code></p>
<p><code>backupdr. managementServers. backupAccess</code></p>
<p><code>backupdr.managementServers.get</code></p>
<p><code>backupdr. managementServers. getDynamicProtection</code></p>
<p><code>backupdr. managementServers. getIamPolicy</code></p>
<p><code>backupdr. managementServers. list</code></p>
<p><code>backupdr. managementServers. listDynamicProtection</code></p>
<p><code>backupdr. managementServers. listEffectiveTags</code></p>
<p><code>backupdr. managementServers. listTagBindings</code></p>
<p><code>backupdr. managementServers. viewBackupPlans</code></p>
<p><code>backupdr. managementServers. viewBackupServers</code></p>
<p><code>backupdr. managementServers. viewReports</code></p>
<p><code>backupdr. managementServers. viewStorage</code></p>
<p><code>backupdr. managementServers. viewSystem</code></p>
<p><code>backupdr. managementServers. viewWorkflows</code></p>
<p><code>backupdr.operations.get</code></p>
<p><code>backupdr.operations.list</code></p>
<p><code>backupdr.trial.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Backup and DR AlloyDB Operator
<p>( <code>roles/ backupdr.alloydbOperator</code> )</p>
<p>Allows a Backup and DR service account to discover and backup AlloyDB clusters.</p></td>
<td><p><code>alloydb.operations.get</code></p></td>
</tr>
<tr class="odd">
<td>Backup and DR Backup Config Viewer
<p>( <code>roles/ backupdr.backupConfigViewer</code> )</p>
<p>Provides read access to resource backup config. Resource backup config has the metadata of a Google Cloud resource that can be backed up, along with its backup configurations.</p></td>
<td><p><code>backupdr.locations.list</code></p>
<p><code>backupdr. resourceBackupConfigs.*</code></p>
<ul>
<li><code>backupdr. resourceBackupConfigs. fetch</code></li>
<li><code>backupdr. resourceBackupConfigs. get</code></li>
<li><code>backupdr. resourceBackupConfigs. list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Backup and DR Backup User
<p>( <code>roles/ backupdr.backupUser</code> )</p>
<p>Allows the user to apply existing backup plans. This role cannot create backup plans or restore from a backup.</p></td>
<td><p><code>backupdr. backupPlanAssociations.*</code></p>
<ul>
<li><code>backupdr. backupPlanAssociations. createForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. createForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. createForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. createForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. createForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. getForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. getForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. getForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. getForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. getForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. list</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. updateForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. updateForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. updateForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. updateForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. updateForFilestoreInstance</code></li>
</ul>
<p><code>backupdr.backupPlanRevisions.*</code></p>
<ul>
<li><code>backupdr. backupPlanRevisions. get</code></li>
<li><code>backupdr. backupPlanRevisions. list</code></li>
</ul>
<p><code>backupdr.backupPlans.get</code></p>
<p><code>backupdr.backupPlans.list</code></p>
<p><code>backupdr. backupPlans. useForAlloydbCluster</code></p>
<p><code>backupdr. backupPlans. useForCloudSqlInstance</code></p>
<p><code>backupdr. backupPlans. useForComputeDisk</code></p>
<p><code>backupdr. backupPlans. useForComputeInstance</code></p>
<p><code>backupdr. backupPlans. useForFilestoreInstance</code></p>
<p><code>backupdr.backupVaults.get</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr. bvbackups. fetchForCloudSqlInstance</code></p>
<p><code>backupdr. bvbackups. fetchForComputeDisk</code></p>
<p><code>backupdr. bvbackups. fetchForComputeInstance</code></p>
<p><code>backupdr.bvbackups.get</code></p>
<p><code>backupdr.bvbackups.list</code></p>
<p><code>backupdr.bvdataSources.get</code></p>
<p><code>backupdr.bvdataSources.list</code></p>
<p><code>backupdr. dataSourceReferences.*</code></p>
<ul>
<li><code>backupdr. dataSourceReferences. fetchForAlloydbCluster</code></li>
<li><code>backupdr. dataSourceReferences. fetchForCloudSqlInstance</code></li>
<li><code>backupdr. dataSourceReferences. fetchForFilestoreInstance</code></li>
<li><code>backupdr. dataSourceReferences. getForAlloydbCluster</code></li>
<li><code>backupdr. dataSourceReferences. getForCloudSqlInstance</code></li>
<li><code>backupdr. dataSourceReferences. getForFilestoreInstance</code></li>
<li><code>backupdr. dataSourceReferences. list</code></li>
</ul>
<p><code>backupdr.locations.*</code></p>
<ul>
<li><code>backupdr.locations.get</code></li>
<li><code>backupdr.locations.list</code></li>
</ul>
<p><code>backupdr. managementServers. access</code></p>
<p><code>backupdr. managementServers. assignBackupPlans</code></p>
<p><code>backupdr. managementServers. createDynamicProtection</code></p>
<p><code>backupdr. managementServers. deleteDynamicProtection</code></p>
<p><code>backupdr.managementServers.get</code></p>
<p><code>backupdr. managementServers. getDynamicProtection</code></p>
<p><code>backupdr. managementServers. list</code></p>
<p><code>backupdr. managementServers. listDynamicProtection</code></p>
<p><code>backupdr. managementServers. listEffectiveTags</code></p>
<p><code>backupdr. managementServers. listTagBindings</code></p>
<p><code>backupdr. managementServers. manageApplications</code></p>
<p><code>backupdr. managementServers. manageBackups</code></p>
<p><code>backupdr. managementServers. manageHosts</code></p>
<p><code>backupdr. managementServers. viewBackupPlans</code></p>
<p><code>backupdr. managementServers. viewReports</code></p>
<p><code>backupdr. managementServers. viewStorage</code></p>
<p><code>backupdr. managementServers. viewSystem</code></p>
<p><code>backupdr.operations.get</code></p>
<p><code>backupdr.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Backup and DR Backup Vault Accessor
<p>( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p>Allows the Backup Appliance permissions to create and manage backups in a backup vault.</p></td>
<td><p><code>backupdr.backupVaults.get</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr.bvbackups.delete</code></p>
<p><code>backupdr.bvbackups.get</code></p>
<p><code>backupdr.bvbackups.list</code></p>
<p><code>backupdr.bvbackups.update</code></p>
<p><code>backupdr. bvdataSources. abandonBackup</code></p>
<p><code>backupdr. bvdataSources. fetchAccessToken</code></p>
<p><code>backupdr. bvdataSources. finalizeBackup</code></p>
<p><code>backupdr.bvdataSources.get</code></p>
<p><code>backupdr. bvdataSources. initiateBackup</code></p>
<p><code>backupdr.bvdataSources.list</code></p>
<p><code>backupdr.bvdataSources.remove</code></p>
<p><code>backupdr. bvdataSources. setInternalStatus</code></p>
<p><code>backupdr.bvdataSources.update</code></p>
<p><code>backupdr.operations.*</code></p>
<ul>
<li><code>backupdr.operations.cancel</code></li>
<li><code>backupdr.operations.delete</code></li>
<li><code>backupdr.operations.get</code></li>
<li><code>backupdr.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Backup and DR Backup Vault Admin
<p>( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p>Allows the Backup Appliance full administrative control of backup vault resources.</p></td>
<td><p><code>backupdr.backupVaults.*</code></p>
<ul>
<li><code>backupdr. backupVaults. associate</code></li>
<li><code>backupdr.backupVaults.create</code></li>
<li><code>backupdr. backupVaults. createTagBinding</code></li>
<li><code>backupdr.backupVaults.delete</code></li>
<li><code>backupdr. backupVaults. deleteTagBinding</code></li>
<li><code>backupdr.backupVaults.get</code></li>
<li><code>backupdr.backupVaults.list</code></li>
<li><code>backupdr. backupVaults. listEffectiveTags</code></li>
<li><code>backupdr. backupVaults. listTagBindings</code></li>
<li><code>backupdr.backupVaults.update</code></li>
</ul>
<p><code>backupdr.bvbackups.delete</code></p>
<p><code>backupdr.bvbackups.get</code></p>
<p><code>backupdr.bvbackups.list</code></p>
<p><code>backupdr.bvbackups.restore</code></p>
<p><code>backupdr.bvbackups.update</code></p>
<p><code>backupdr.bvdataSources.get</code></p>
<p><code>backupdr.bvdataSources.list</code></p>
<p><code>backupdr.bvdataSources.update</code></p>
<p><code>backupdr. compute. restoreFromBackupVault</code></p>
<p><code>backupdr.locations.*</code></p>
<ul>
<li><code>backupdr.locations.get</code></li>
<li><code>backupdr.locations.list</code></li>
</ul>
<p><code>backupdr.operations.*</code></p>
<ul>
<li><code>backupdr.operations.cancel</code></li>
<li><code>backupdr.operations.delete</code></li>
<li><code>backupdr.operations.get</code></li>
<li><code>backupdr.operations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Backup and DR Backup Vault Lister
<p>( <code>roles/ backupdr.backupvaultLister</code> )</p>
<p>Allows the Backup Appliance permission to list backup vaults in a given project.</p></td>
<td><p><code>backupdr.backupVaults.list</code></p></td>
</tr>
<tr class="even">
<td>Backup and DR Backup Vault Viewer
<p>( <code>roles/ backupdr.backupvaultViewer</code> )</p>
<p>Allows read-only permissions to access backup vault resources and backups.</p></td>
<td><p><code>backupdr.backupVaults.get</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr.bvbackups.get</code></p>
<p><code>backupdr.bvbackups.list</code></p>
<p><code>backupdr.bvdataSources.get</code></p>
<p><code>backupdr.bvdataSources.list</code></p>
<p><code>backupdr.operations.get</code></p>
<p><code>backupdr.operations.list</code></p></td>
</tr>
<tr class="odd">
<td>Backup and DR Cloud SQL Operator
<p>( <code>roles/ backupdr.cloudSqlOperator</code> )</p>
<p>Allows a Backup and DR service account to discover and backup Cloud SQL instances.</p></td>
<td><p><code>cloudsql. instances. createBackupDrBackup</code></p>
<p><code>cloudsql.instances.get</code></p></td>
</tr>
<tr class="even">
<td>Backup and DR Cloud Storage Operator
<p>( <code>roles/ backupdr.cloudStorageOperator</code> )</p>
<p>Allows a Backup and DR service account to store and manage data (backups or metadata) in Cloud Storage.</p></td>
<td><p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td>Backup and DR Compute Engine Operator
<p>( <code>roles/ backupdr.computeEngineOperator</code> )</p>
<p>Allows a Backup and DR service account to discover, back up, and restore Compute Engine VM instances.</p></td>
<td><p><code>backupdr. managementServers. createConnection</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.addresses.use</code></p>
<p><code>compute.addresses.useInternal</code></p>
<p><code>compute.diskTypes.*</code></p>
<ul>
<li><code>compute.diskTypes.get</code></li>
<li><code>compute.diskTypes.list</code></li>
</ul>
<p><code>compute.disks.create</code></p>
<p><code>compute.disks.createSnapshot</code></p>
<p><code>compute.disks.delete</code></p>
<p><code>compute.disks.get</code></p>
<p><code>compute.disks.list</code></p>
<p><code>compute.disks.setLabels</code></p>
<p><code>compute.disks.use</code></p>
<p><code>compute.disks.useReadOnly</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.images.create</code></p>
<p><code>compute.images.delete</code></p>
<p><code>compute.images.get</code></p>
<p><code>compute.images.useReadOnly</code></p>
<p><code>compute.instances.attachDisk</code></p>
<p><code>compute.instances.create</code></p>
<p><code>compute. instances. createTagBinding</code></p>
<p><code>compute.instances.delete</code></p>
<p><code>compute.instances.detachDisk</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute. instances. listEffectiveTags</code></p>
<p><code>compute. instances. pscInterfaceCreate</code></p>
<p><code>compute. instances. setDeletionProtection</code></p>
<p><code>compute.instances.setLabels</code></p>
<p><code>compute.instances.setMetadata</code></p>
<p><code>compute. instances. setServiceAccount</code></p>
<p><code>compute.instances.setTags</code></p>
<p><code>compute.instances.start</code></p>
<p><code>compute.instances.stop</code></p>
<p><code>compute. instances. updateDisplayDevice</code></p>
<p><code>compute.instances.useReadOnly</code></p>
<p><code>compute.machineTypes.*</code></p>
<ul>
<li><code>compute.machineTypes.get</code></li>
<li><code>compute.machineTypes.list</code></li>
</ul>
<p><code>compute.networks.list</code></p>
<p><code>compute.nodeGroups.get</code></p>
<p><code>compute.nodeGroups.list</code></p>
<p><code>compute.nodeTemplates.get</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.resourcePolicies.use</code></p>
<p><code>compute.snapshots.create</code></p>
<p><code>compute.snapshots.delete</code></p>
<p><code>compute.snapshots.get</code></p>
<p><code>compute.snapshots.setLabels</code></p>
<p><code>compute.snapshots.useReadOnly</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>compute. subnetworks. useExternalIp</code></p>
<p><code>compute.zoneOperations.get</code></p>
<p><code>compute.zones.list</code></p>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Backup and DR Disk Operator
<p>( <code>roles/ backupdr.diskOperator</code> )</p>
<p>Allows a Backup and DR service account to store and manage data (backups or metadata) in Disk.</p></td>
<td><p><code>compute.disks.create</code></p>
<p><code>compute.disks.createSnapshot</code></p>
<p><code>compute.disks.createTagBinding</code></p>
<p><code>compute.disks.get</code></p>
<p><code>compute.disks.list</code></p>
<p><code>compute.disks.setLabels</code></p>
<p><code>compute.disks.useReadOnly</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.resourcePolicies.use</code></p>
<p><code>compute.snapshots.setLabels</code></p>
<p><code>compute.snapshots.useReadOnly</code></p>
<p><code>compute.storagePools.use</code></p>
<p><code>compute.zoneOperations.get</code></p></td>
</tr>
<tr class="odd">
<td>Backup and DR Filestore Operator <sup>Beta</sup>
<p>( <code>roles/ backupdr.filestoreOperator</code> )</p>
<p>Allows a Backup and DR service account to discover and backup Filestore instances.</p></td>
<td><p><code>file.backups.create</code></p>
<p><code>file. instances. createCrossProjectBackup</code></p>
<p><code>file.instances.get</code></p></td>
</tr>
<tr class="even">
<td>Backup and DR Management Server Accessor
<p>( <code>roles/ backupdr.managementServerAccessor</code> )</p>
<p>Grants the Backup and DR management server access role to Backup Appliances.</p></td>
<td><p><code>backupdr. managementServers. createConnection</code></p></td>
</tr>
<tr class="odd">
<td>Backup and DR Mount User
<p>( <code>roles/ backupdr.mountUser</code> )</p>
<p>Allows the user to mount from a backup. This role cannot create a backup plan or restore from a backup.</p></td>
<td><p><code>backupdr.locations.*</code></p>
<ul>
<li><code>backupdr.locations.get</code></li>
<li><code>backupdr.locations.list</code></li>
</ul>
<p><code>backupdr. managementServers. access</code></p>
<p><code>backupdr.managementServers.get</code></p>
<p><code>backupdr. managementServers. getDynamicProtection</code></p>
<p><code>backupdr. managementServers. list</code></p>
<p><code>backupdr. managementServers. listDynamicProtection</code></p>
<p><code>backupdr. managementServers. listEffectiveTags</code></p>
<p><code>backupdr. managementServers. listTagBindings</code></p>
<p><code>backupdr. managementServers. manageApplications</code></p>
<p><code>backupdr. managementServers. manageClones</code></p>
<p><code>backupdr. managementServers. manageHosts</code></p>
<p><code>backupdr. managementServers. manageLiveClones</code></p>
<p><code>backupdr. managementServers. manageMirroring</code></p>
<p><code>backupdr. managementServers. manageMounts</code></p>
<p><code>backupdr. managementServers. manageWorkflows</code></p>
<p><code>backupdr. managementServers. refreshWorkflows</code></p>
<p><code>backupdr. managementServers. runWorkflows</code></p>
<p><code>backupdr. managementServers. viewBackupPlans</code></p>
<p><code>backupdr. managementServers. viewReports</code></p>
<p><code>backupdr. managementServers. viewStorage</code></p>
<p><code>backupdr. managementServers. viewSystem</code></p>
<p><code>backupdr. managementServers. viewWorkflows</code></p>
<p><code>backupdr.operations.get</code></p>
<p><code>backupdr.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Backup and DR Restore User
<p>( <code>roles/ backupdr.restoreUser</code> )</p>
<p>Allows the user to restore or mount from a backup. This role cannot create a backup plan.</p></td>
<td><p><code>backupdr.backupVaults.get</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr. bvbackups. fetchForCloudSqlInstance</code></p>
<p><code>backupdr. bvbackups. fetchForComputeDisk</code></p>
<p><code>backupdr. bvbackups. fetchForComputeInstance</code></p>
<p><code>backupdr.bvbackups.get</code></p>
<p><code>backupdr.bvbackups.list</code></p>
<p><code>backupdr.bvbackups.restore</code></p>
<p><code>backupdr. bvbackups. useReadOnlyForAlloydbCluster</code></p>
<p><code>backupdr. bvbackups. useReadOnlyForCloudSqlInstance</code></p>
<p><code>backupdr. bvbackups. useReadOnlyForFilestoreInstance</code></p>
<p><code>backupdr.bvdataSources.get</code></p>
<p><code>backupdr.bvdataSources.list</code></p>
<p><code>backupdr. bvdataSources. useReadOnlyForAlloydbCluster</code></p>
<p><code>backupdr. bvdataSources. useReadOnlyForCloudSqlInstance</code></p>
<p><code>backupdr. compute. restoreFromBackupVault</code></p>
<p><code>backupdr. dataSourceReferences.*</code></p>
<ul>
<li><code>backupdr. dataSourceReferences. fetchForAlloydbCluster</code></li>
<li><code>backupdr. dataSourceReferences. fetchForCloudSqlInstance</code></li>
<li><code>backupdr. dataSourceReferences. fetchForFilestoreInstance</code></li>
<li><code>backupdr. dataSourceReferences. getForAlloydbCluster</code></li>
<li><code>backupdr. dataSourceReferences. getForCloudSqlInstance</code></li>
<li><code>backupdr. dataSourceReferences. getForFilestoreInstance</code></li>
<li><code>backupdr. dataSourceReferences. list</code></li>
</ul>
<p><code>backupdr.locations.*</code></p>
<ul>
<li><code>backupdr.locations.get</code></li>
<li><code>backupdr.locations.list</code></li>
</ul>
<p><code>backupdr. managementServers. access</code></p>
<p><code>backupdr.managementServers.get</code></p>
<p><code>backupdr. managementServers. getDynamicProtection</code></p>
<p><code>backupdr. managementServers. list</code></p>
<p><code>backupdr. managementServers. listDynamicProtection</code></p>
<p><code>backupdr. managementServers. listEffectiveTags</code></p>
<p><code>backupdr. managementServers. listTagBindings</code></p>
<p><code>backupdr. managementServers. manageApplications</code></p>
<p><code>backupdr. managementServers. manageClones</code></p>
<p><code>backupdr. managementServers. manageHosts</code></p>
<p><code>backupdr. managementServers. manageLiveClones</code></p>
<p><code>backupdr. managementServers. manageMigrations</code></p>
<p><code>backupdr. managementServers. manageMirroring</code></p>
<p><code>backupdr. managementServers. manageMounts</code></p>
<p><code>backupdr. managementServers. manageRestores</code></p>
<p><code>backupdr. managementServers. manageWorkflows</code></p>
<p><code>backupdr. managementServers. refreshWorkflows</code></p>
<p><code>backupdr. managementServers. runWorkflows</code></p>
<p><code>backupdr. managementServers. testFailOvers</code></p>
<p><code>backupdr. managementServers. viewBackupPlans</code></p>
<p><code>backupdr. managementServers. viewReports</code></p>
<p><code>backupdr. managementServers. viewStorage</code></p>
<p><code>backupdr. managementServers. viewSystem</code></p>
<p><code>backupdr. managementServers. viewWorkflows</code></p>
<p><code>backupdr.operations.get</code></p>
<p><code>backupdr.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Backup and DR User
<p>( <code>roles/ backupdr.user</code> )</p>
<p>Provides access to management console. Granular Backup and DR permissions depend on ACL configuration provided by Backup and DR admin within the management console.</p></td>
<td><p><code>backupdr. backupPlanAssociations. createForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. deleteForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. updateForComputeInstance</code></p>
<p><code>backupdr. managementServers. access</code></p>
<p><code>backupdr. managementServers. backupAccess</code></p>
<p><code>backupdr.managementServers.get</code></p>
<p><code>backupdr. managementServers. getDynamicProtection</code></p>
<p><code>backupdr. managementServers. getIamPolicy</code></p>
<p><code>backupdr. managementServers. list</code></p>
<p><code>backupdr. managementServers. listDynamicProtection</code></p>
<p><code>backupdr. managementServers. listEffectiveTags</code></p>
<p><code>backupdr. managementServers. listTagBindings</code></p>
<p><code>backupdr. managementServers. viewBackupPlans</code></p>
<p><code>backupdr. managementServers. viewBackupServers</code></p>
<p><code>backupdr. managementServers. viewReports</code></p>
<p><code>backupdr. managementServers. viewStorage</code></p>
<p><code>backupdr. managementServers. viewSystem</code></p>
<p><code>backupdr. managementServers. viewWorkflows</code></p>
<p><code>backupdr.operations.get</code></p>
<p><code>backupdr.operations.list</code></p>
<p><code>backupdr.trial.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Backup and DR User V2
<p>( <code>roles/ backupdr.userv2</code> )</p>
<p>Provides full access to Backup and DR resources except deploying and managing backup infrastructure, expiring backups, changing data sensitivity and configuring on-premises billing.</p></td>
<td><p><code>backupdr. appliedAutoProtectionPolicies. list</code></p>
<p><code>backupdr. appliedAutoProtectionPolicies. viewMatchingResources</code></p>
<p><code>backupdr. autoProtectionBindings. get</code></p>
<p><code>backupdr. autoProtectionBindings. list</code></p>
<p><code>backupdr. autoProtectionPolicies. get</code></p>
<p><code>backupdr. autoProtectionPolicies. list</code></p>
<p><code>backupdr. backupPlanAssociations.*</code></p>
<ul>
<li><code>backupdr. backupPlanAssociations. createForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. createForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. createForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. createForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. createForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. deleteForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. fetchForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. getForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. getForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. getForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. getForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. getForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. list</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. triggerBackupForFilestoreInstance</code></li>
<li><code>backupdr. backupPlanAssociations. updateForAlloydbCluster</code></li>
<li><code>backupdr. backupPlanAssociations. updateForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlanAssociations. updateForComputeDisk</code></li>
<li><code>backupdr. backupPlanAssociations. updateForComputeInstance</code></li>
<li><code>backupdr. backupPlanAssociations. updateForFilestoreInstance</code></li>
</ul>
<p><code>backupdr.backupPlanRevisions.*</code></p>
<ul>
<li><code>backupdr. backupPlanRevisions. get</code></li>
<li><code>backupdr. backupPlanRevisions. list</code></li>
</ul>
<p><code>backupdr.backupPlans.*</code></p>
<ul>
<li><code>backupdr.backupPlans.create</code></li>
<li><code>backupdr.backupPlans.delete</code></li>
<li><code>backupdr.backupPlans.get</code></li>
<li><code>backupdr.backupPlans.list</code></li>
<li><code>backupdr.backupPlans.update</code></li>
<li><code>backupdr. backupPlans. useForAlloydbCluster</code></li>
<li><code>backupdr. backupPlans. useForCloudSqlInstance</code></li>
<li><code>backupdr. backupPlans. useForComputeDisk</code></li>
<li><code>backupdr. backupPlans. useForComputeInstance</code></li>
<li><code>backupdr. backupPlans. useForFilestoreInstance</code></li>
</ul>
<p><code>backupdr. backupVaults. associate</code></p>
<p><code>backupdr.backupVaults.get</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr. backupVaults. listEffectiveTags</code></p>
<p><code>backupdr. backupVaults. listTagBindings</code></p>
<p><code>backupdr. bindingMatchingResources. list</code></p>
<p><code>backupdr. bvbackups. fetchForCloudSqlInstance</code></p>
<p><code>backupdr. bvbackups. fetchForComputeDisk</code></p>
<p><code>backupdr. bvbackups. fetchForComputeInstance</code></p>
<p><code>backupdr.bvbackups.get</code></p>
<p><code>backupdr.bvbackups.list</code></p>
<p><code>backupdr.bvbackups.restore</code></p>
<p><code>backupdr. bvbackups. useReadOnlyForAlloydbCluster</code></p>
<p><code>backupdr. bvbackups. useReadOnlyForCloudSqlInstance</code></p>
<p><code>backupdr. bvbackups. useReadOnlyForFilestoreInstance</code></p>
<p><code>backupdr.bvdataSources.get</code></p>
<p><code>backupdr.bvdataSources.list</code></p>
<p><code>backupdr. bvdataSources. useReadOnlyForAlloydbCluster</code></p>
<p><code>backupdr. bvdataSources. useReadOnlyForCloudSqlInstance</code></p>
<p><code>backupdr. compute. restoreFromBackupVault</code></p>
<p><code>backupdr. dataSourceReferences.*</code></p>
<ul>
<li><code>backupdr. dataSourceReferences. fetchForAlloydbCluster</code></li>
<li><code>backupdr. dataSourceReferences. fetchForCloudSqlInstance</code></li>
<li><code>backupdr. dataSourceReferences. fetchForFilestoreInstance</code></li>
<li><code>backupdr. dataSourceReferences. getForAlloydbCluster</code></li>
<li><code>backupdr. dataSourceReferences. getForCloudSqlInstance</code></li>
<li><code>backupdr. dataSourceReferences. getForFilestoreInstance</code></li>
<li><code>backupdr. dataSourceReferences. list</code></li>
</ul>
<p><code>backupdr.locations.*</code></p>
<ul>
<li><code>backupdr.locations.get</code></li>
<li><code>backupdr.locations.list</code></li>
</ul>
<p><code>backupdr. managementServers. access</code></p>
<p><code>backupdr. managementServers. assignBackupPlans</code></p>
<p><code>backupdr. managementServers. backupAccess</code></p>
<p><code>backupdr. managementServers. createDynamicProtection</code></p>
<p><code>backupdr. managementServers. deleteDynamicProtection</code></p>
<p><code>backupdr.managementServers.get</code></p>
<p><code>backupdr. managementServers. getDynamicProtection</code></p>
<p><code>backupdr. managementServers. getIamPolicy</code></p>
<p><code>backupdr. managementServers. list</code></p>
<p><code>backupdr. managementServers. listDynamicProtection</code></p>
<p><code>backupdr. managementServers. listEffectiveTags</code></p>
<p><code>backupdr. managementServers. listTagBindings</code></p>
<p><code>backupdr. managementServers. manageApplications</code></p>
<p><code>backupdr. managementServers. manageBackupPlans</code></p>
<p><code>backupdr. managementServers. manageBackups</code></p>
<p><code>backupdr. managementServers. manageClones</code></p>
<p><code>backupdr. managementServers. manageHosts</code></p>
<p><code>backupdr. managementServers. manageJobs</code></p>
<p><code>backupdr. managementServers. manageLiveClones</code></p>
<p><code>backupdr. managementServers. manageMigrations</code></p>
<p><code>backupdr. managementServers. manageMirroring</code></p>
<p><code>backupdr. managementServers. manageMounts</code></p>
<p><code>backupdr. managementServers. manageRestores</code></p>
<p><code>backupdr. managementServers. manageWorkflows</code></p>
<p><code>backupdr. managementServers. refreshWorkflows</code></p>
<p><code>backupdr. managementServers. runWorkflows</code></p>
<p><code>backupdr. managementServers. testFailOvers</code></p>
<p><code>backupdr. managementServers. viewBackupPlans</code></p>
<p><code>backupdr. managementServers. viewBackupServers</code></p>
<p><code>backupdr. managementServers. viewReports</code></p>
<p><code>backupdr. managementServers. viewStorage</code></p>
<p><code>backupdr. managementServers. viewSystem</code></p>
<p><code>backupdr. managementServers. viewWorkflows</code></p>
<p><code>backupdr.operations.get</code></p>
<p><code>backupdr.operations.list</code></p>
<p><code>backupdr.trial.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td>Backup and DR Service Agent
<p>( <code>roles/ backupdr.serviceAgent</code> )</p>
<p>Grants the Backup and DR Service access to protect Compute Engine instances.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>alloydb.operations.get</code></p>
<p><code>backupdr. backupPlanAssociations. createForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. createForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. deleteForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. deleteForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. updateForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. updateForComputeInstance</code></p>
<p><code>backupdr.operations.get</code></p>
<p><code>cloudsql. instances. createBackupDrBackup</code></p>
<p><code>cloudsql.instances.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.addresses.use</code></p>
<p><code>compute.addresses.useInternal</code></p>
<p><code>compute.diskTypes.*</code></p>
<ul>
<li><code>compute.diskTypes.get</code></li>
<li><code>compute.diskTypes.list</code></li>
</ul>
<p><code>compute.disks.create</code></p>
<p><code>compute.disks.createSnapshot</code></p>
<p><code>compute.disks.createTagBinding</code></p>
<p><code>compute.disks.delete</code></p>
<p><code>compute.disks.get</code></p>
<p><code>compute.disks.list</code></p>
<p><code>compute.disks.setLabels</code></p>
<p><code>compute.disks.use</code></p>
<p><code>compute.disks.useReadOnly</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.images.create</code></p>
<p><code>compute.images.delete</code></p>
<p><code>compute.images.get</code></p>
<p><code>compute.images.useReadOnly</code></p>
<p><code>compute.instances.attachDisk</code></p>
<p><code>compute.instances.create</code></p>
<p><code>compute. instances. createTagBinding</code></p>
<p><code>compute.instances.delete</code></p>
<p><code>compute.instances.detachDisk</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute. instances. listEffectiveTags</code></p>
<p><code>compute. instances. pscInterfaceCreate</code></p>
<p><code>compute. instances. setDeletionProtection</code></p>
<p><code>compute.instances.setLabels</code></p>
<p><code>compute.instances.setMetadata</code></p>
<p><code>compute. instances. setServiceAccount</code></p>
<p><code>compute.instances.setTags</code></p>
<p><code>compute.instances.start</code></p>
<p><code>compute.instances.stop</code></p>
<p><code>compute. instances. updateDisplayDevice</code></p>
<p><code>compute.instances.useReadOnly</code></p>
<p><code>compute.machineTypes.*</code></p>
<ul>
<li><code>compute.machineTypes.get</code></li>
<li><code>compute.machineTypes.list</code></li>
</ul>
<p><code>compute.networks.list</code></p>
<p><code>compute.nodeGroups.get</code></p>
<p><code>compute.nodeGroups.list</code></p>
<p><code>compute.nodeTemplates.get</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.resourcePolicies.use</code></p>
<p><code>compute.snapshots.create</code></p>
<p><code>compute.snapshots.delete</code></p>
<p><code>compute.snapshots.get</code></p>
<p><code>compute.snapshots.setLabels</code></p>
<p><code>compute.snapshots.useReadOnly</code></p>
<p><code>compute.storagePools.use</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>compute. subnetworks. useExternalIp</code></p>
<p><code>compute.zoneOperations.get</code></p>
<p><code>compute.zones.list</code></p>
<p><code>file.backups.create</code></p>
<p><code>file. instances. createCrossProjectBackup</code></p>
<p><code>file.instances.get</code></p>
<p><code>file.operations.get</code></p>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>netapp.ontap.get</code></p>
<p><code>netapp.operations.get</code></p>
<p><code>netapp.storagePools.get</code></p>
<p><code>netapp. volumes. createCrossProjectBackup</code></p>
<p><code>netapp.volumes.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td><code>backupdr. appliedAutoProtectionPolicies. authorize</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. appliedAutoProtectionPolicies. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. appliedAutoProtectionPolicies. viewMatchingResources</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. autoProtectionBindings. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. autoProtectionBindings. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. autoProtectionBindings. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. autoProtectionBindings. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. autoProtectionPolicies. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. autoProtectionPolicies. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. autoProtectionPolicies. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. autoProtectionPolicies. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. autoProtectionPolicies. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. createForAlloydbCluster</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. createForCloudSqlInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. createForComputeDisk</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code>roles/ backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. createForComputeInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code>roles/ backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. createForFilestoreInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. deleteForAlloydbCluster</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. deleteForCloudSqlInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. deleteForComputeDisk</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code>roles/ backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. deleteForComputeInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code>roles/ backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. deleteForFilestoreInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. fetchForAlloydbCluster</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. fetchForCloudSqlInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. fetchForComputeDisk</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. fetchForComputeInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. fetchForFilestoreInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code>roles/ file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. getForAlloydbCluster</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. getForCloudSqlInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. getForComputeDisk</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. getForComputeInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. getForFilestoreInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code>roles/ file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. triggerBackupForAlloydbCluster</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. triggerBackupForCloudSqlInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. triggerBackupForComputeDisk</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. triggerBackupForComputeInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. triggerBackupForFilestoreInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. updateForAlloydbCluster</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. updateForCloudSqlInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. updateForComputeDisk</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code>roles/ backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanAssociations. updateForComputeInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code>roles/ backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanAssociations. updateForFilestoreInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlanRevisions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlanRevisions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr.backupPlans.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.backupPlans.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr.backupPlans.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code>roles/ netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr.backupPlans.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code>roles/ netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr.backupPlans.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlans. useForAlloydbCluster</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlans. useForCloudSqlInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlans. useForComputeDisk</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupPlans. useForComputeInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupPlans. useForFilestoreInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. backupVaults. associate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.backupVaults.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. backupVaults. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.backupVaults.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. backupVaults. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.backupVaults.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code>roles/ netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code>roles/ backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr.backupVaults.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code>roles/ netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultLister">Backup and DR Backup Vault Lister</a> ( <code>roles/ backupdr.backupvaultLister</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code>roles/ backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. backupVaults. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. backupVaults. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.backupVaults.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. bindingMatchingResources. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.bvbackups.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. bvbackups. fetchForCloudSqlInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. bvbackups. fetchForComputeDisk</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. bvbackups. fetchForComputeInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.bvbackups.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code>roles/ backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr.bvbackups.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code>roles/ backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.bvbackups.restore</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr.bvbackups.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. bvbackups. useReadOnlyForAlloydbCluster</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. bvbackups. useReadOnlyForCloudSqlInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. bvbackups. useReadOnlyForFilestoreInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. bvdataSources. abandonBackup</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. bvdataSources. fetchAccessToken</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. bvdataSources. finalizeBackup</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.bvdataSources.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code>roles/ backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. bvdataSources. initiateBackup</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.bvdataSources.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code>roles/ backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr.bvdataSources.remove</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. bvdataSources. setInternalStatus</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr.bvdataSources.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. bvdataSources. useReadOnlyForAlloydbCluster</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. bvdataSources. useReadOnlyForCloudSqlInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. compute. restoreFromBackupVault</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. dataSourceReferences. fetchForAlloydbCluster</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. dataSourceReferences. fetchForCloudSqlInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. dataSourceReferences. fetchForFilestoreInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code>roles/ file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. dataSourceReferences. getForAlloydbCluster</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. dataSourceReferences. getForCloudSqlInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. dataSourceReferences. getForFilestoreInstance</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.viewer">Cloud Filestore Viewer</a> ( <code>roles/ file.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr. dataSourceReferences. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code>roles/ netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupConfigViewer">Backup and DR Backup Config Viewer</a> ( <code>roles/ backupdr.backupConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. access</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. accessSensitiveData</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. assignBackupPlans</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. backupAccess</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. createConnection</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.computeEngineOperator">Backup and DR Compute Engine Operator</a> ( <code>roles/ backupdr.computeEngineOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.managementServerAccessor">Backup and DR Management Server Accessor</a> ( <code>roles/ backupdr.managementServerAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. createDynamicProtection</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. deleteDynamicProtection</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr.managementServers.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. getDynamicProtection</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. listDynamicProtection</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. manageApplications</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. manageBackupPlans</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. manageBackupServers</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. manageBackups</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. manageClones</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. manageExpiration</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. manageHosts</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. manageInternalACL</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. manageJobs</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. manageLiveClones</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. manageMigrations</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. manageMirroring</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. manageMounts</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. manageRestores</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. manageSensitiveData</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. manageStorage</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. manageSystem</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. manageWorkflows</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. refreshWorkflows</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. runWorkflows</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. testFailOvers</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. viewBackupPlans</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. viewBackupServers</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. viewReports</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. viewStorage</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. managementServers. viewSystem</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. managementServers. viewWorkflows</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code>roles/ netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code>roles/ backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code>roles/ backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>backupdr.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAccessor">Backup and DR Backup Vault Accessor</a> ( <code>roles/ backupdr.backupvaultAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultAdmin">Backup and DR Backup Vault Admin</a> ( <code>roles/ backupdr.backupvaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupvaultViewer">Backup and DR Backup Vault Viewer</a> ( <code>roles/ backupdr.backupvaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr. resourceBackupConfigs. fetch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupConfigViewer">Backup and DR Backup Config Viewer</a> ( <code>roles/ backupdr.backupConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. resourceBackupConfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupConfigViewer">Backup and DR Backup Config Viewer</a> ( <code>roles/ backupdr.backupConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr. resourceBackupConfigs. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupConfigViewer">Backup and DR Backup Config Viewer</a> ( <code>roles/ backupdr.backupConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr. serviceConfig. initialize</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.editor">Cloud Filestore Editor</a> ( <code>roles/ file.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code>roles/ netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code>roles/ alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>backupdr.trial.end</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>backupdr.trial.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>backupdr.trial.subscribe</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
