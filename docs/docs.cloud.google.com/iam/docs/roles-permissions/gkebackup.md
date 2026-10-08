---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/gkebackup
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup
title: Backup for GKE roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Backup for GKE. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Backup for GKE roles

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
<td>Backup for GKE Admin
<p>( <code>roles/ gkebackup.admin</code> )</p>
<p>Full access to all Backup for GKE resources.</p></td>
<td><p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>gkebackup.*</code></p>
<ul>
<li><code>gkebackup. backupChannels. create</code></li>
<li><code>gkebackup. backupChannels. delete</code></li>
<li><code>gkebackup.backupChannels.get</code></li>
<li><code>gkebackup.backupChannels.list</code></li>
<li><code>gkebackup. backupChannels. update</code></li>
<li><code>gkebackup. backupPlanBindings. get</code></li>
<li><code>gkebackup. backupPlanBindings. list</code></li>
<li><code>gkebackup.backupPlans.create</code></li>
<li><code>gkebackup.backupPlans.delete</code></li>
<li><code>gkebackup.backupPlans.get</code></li>
<li><code>gkebackup. backupPlans. getIamPolicy</code></li>
<li><code>gkebackup.backupPlans.list</code></li>
<li><code>gkebackup. backupPlans. setIamPolicy</code></li>
<li><code>gkebackup.backupPlans.update</code></li>
<li><code>gkebackup.backups.create</code></li>
<li><code>gkebackup.backups.delete</code></li>
<li><code>gkebackup.backups.get</code></li>
<li><code>gkebackup. backups. getBackupIndex</code></li>
<li><code>gkebackup.backups.list</code></li>
<li><code>gkebackup.backups.update</code></li>
<li><code>gkebackup.locations.get</code></li>
<li><code>gkebackup.locations.list</code></li>
<li><code>gkebackup.operations.cancel</code></li>
<li><code>gkebackup.operations.delete</code></li>
<li><code>gkebackup.operations.get</code></li>
<li><code>gkebackup.operations.list</code></li>
<li><code>gkebackup. restoreChannels. create</code></li>
<li><code>gkebackup. restoreChannels. delete</code></li>
<li><code>gkebackup.restoreChannels.get</code></li>
<li><code>gkebackup.restoreChannels.list</code></li>
<li><code>gkebackup. restoreChannels. update</code></li>
<li><code>gkebackup. restorePlanBindings. get</code></li>
<li><code>gkebackup. restorePlanBindings. list</code></li>
<li><code>gkebackup.restorePlans.create</code></li>
<li><code>gkebackup.restorePlans.delete</code></li>
<li><code>gkebackup.restorePlans.get</code></li>
<li><code>gkebackup. restorePlans. getIamPolicy</code></li>
<li><code>gkebackup.restorePlans.list</code></li>
<li><code>gkebackup. restorePlans. setIamPolicy</code></li>
<li><code>gkebackup.restorePlans.update</code></li>
<li><code>gkebackup.restores.create</code></li>
<li><code>gkebackup.restores.delete</code></li>
<li><code>gkebackup.restores.get</code></li>
<li><code>gkebackup.restores.list</code></li>
<li><code>gkebackup.restores.update</code></li>
<li><code>gkebackup.volumeBackups.get</code></li>
<li><code>gkebackup.volumeBackups.list</code></li>
<li><code>gkebackup.volumeRestores.get</code></li>
<li><code>gkebackup.volumeRestores.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Backup for GKE Editor
<p>( <code>roles/ gkebackup.editor</code> )</p>
<p>Editor role for Backup for GKE</p></td>
<td><p><code>gkebackup.backupChannels.*</code></p>
<ul>
<li><code>gkebackup. backupChannels. create</code></li>
<li><code>gkebackup. backupChannels. delete</code></li>
<li><code>gkebackup.backupChannels.get</code></li>
<li><code>gkebackup.backupChannels.list</code></li>
<li><code>gkebackup. backupChannels. update</code></li>
</ul>
<p><code>gkebackup.backupPlanBindings.*</code></p>
<ul>
<li><code>gkebackup. backupPlanBindings. get</code></li>
<li><code>gkebackup. backupPlanBindings. list</code></li>
</ul>
<p><code>gkebackup.backupPlans.create</code></p>
<p><code>gkebackup.backupPlans.delete</code></p>
<p><code>gkebackup.backupPlans.get</code></p>
<p><code>gkebackup. backupPlans. getIamPolicy</code></p>
<p><code>gkebackup.backupPlans.list</code></p>
<p><code>gkebackup.backupPlans.update</code></p>
<p><code>gkebackup.backups.*</code></p>
<ul>
<li><code>gkebackup.backups.create</code></li>
<li><code>gkebackup.backups.delete</code></li>
<li><code>gkebackup.backups.get</code></li>
<li><code>gkebackup. backups. getBackupIndex</code></li>
<li><code>gkebackup.backups.list</code></li>
<li><code>gkebackup.backups.update</code></li>
</ul>
<p><code>gkebackup.locations.*</code></p>
<ul>
<li><code>gkebackup.locations.get</code></li>
<li><code>gkebackup.locations.list</code></li>
</ul>
<p><code>gkebackup.operations.*</code></p>
<ul>
<li><code>gkebackup.operations.cancel</code></li>
<li><code>gkebackup.operations.delete</code></li>
<li><code>gkebackup.operations.get</code></li>
<li><code>gkebackup.operations.list</code></li>
</ul>
<p><code>gkebackup.restoreChannels.*</code></p>
<ul>
<li><code>gkebackup. restoreChannels. create</code></li>
<li><code>gkebackup. restoreChannels. delete</code></li>
<li><code>gkebackup.restoreChannels.get</code></li>
<li><code>gkebackup.restoreChannels.list</code></li>
<li><code>gkebackup. restoreChannels. update</code></li>
</ul>
<p><code>gkebackup. restorePlanBindings.*</code></p>
<ul>
<li><code>gkebackup. restorePlanBindings. get</code></li>
<li><code>gkebackup. restorePlanBindings. list</code></li>
</ul>
<p><code>gkebackup.restorePlans.create</code></p>
<p><code>gkebackup.restorePlans.delete</code></p>
<p><code>gkebackup.restorePlans.get</code></p>
<p><code>gkebackup. restorePlans. getIamPolicy</code></p>
<p><code>gkebackup.restorePlans.list</code></p>
<p><code>gkebackup.restorePlans.update</code></p>
<p><code>gkebackup.restores.*</code></p>
<ul>
<li><code>gkebackup.restores.create</code></li>
<li><code>gkebackup.restores.delete</code></li>
<li><code>gkebackup.restores.get</code></li>
<li><code>gkebackup.restores.list</code></li>
<li><code>gkebackup.restores.update</code></li>
</ul>
<p><code>gkebackup.volumeBackups.*</code></p>
<ul>
<li><code>gkebackup.volumeBackups.get</code></li>
<li><code>gkebackup.volumeBackups.list</code></li>
</ul>
<p><code>gkebackup.volumeRestores.*</code></p>
<ul>
<li><code>gkebackup.volumeRestores.get</code></li>
<li><code>gkebackup.volumeRestores.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Backup for GKE Viewer
<p>( <code>roles/ gkebackup.viewer</code> )</p>
<p>Read-only access to all Backup for GKE resources.</p></td>
<td><p><code>gkebackup.backupChannels.get</code></p>
<p><code>gkebackup.backupChannels.list</code></p>
<p><code>gkebackup.backupPlanBindings.*</code></p>
<ul>
<li><code>gkebackup. backupPlanBindings. get</code></li>
<li><code>gkebackup. backupPlanBindings. list</code></li>
</ul>
<p><code>gkebackup.backupPlans.get</code></p>
<p><code>gkebackup. backupPlans. getIamPolicy</code></p>
<p><code>gkebackup.backupPlans.list</code></p>
<p><code>gkebackup.backups.get</code></p>
<p><code>gkebackup. backups. getBackupIndex</code></p>
<p><code>gkebackup.backups.list</code></p>
<p><code>gkebackup.locations.*</code></p>
<ul>
<li><code>gkebackup.locations.get</code></li>
<li><code>gkebackup.locations.list</code></li>
</ul>
<p><code>gkebackup.operations.get</code></p>
<p><code>gkebackup.operations.list</code></p>
<p><code>gkebackup.restoreChannels.get</code></p>
<p><code>gkebackup.restoreChannels.list</code></p>
<p><code>gkebackup. restorePlanBindings.*</code></p>
<ul>
<li><code>gkebackup. restorePlanBindings. get</code></li>
<li><code>gkebackup. restorePlanBindings. list</code></li>
</ul>
<p><code>gkebackup.restorePlans.get</code></p>
<p><code>gkebackup. restorePlans. getIamPolicy</code></p>
<p><code>gkebackup.restorePlans.list</code></p>
<p><code>gkebackup.restores.get</code></p>
<p><code>gkebackup.restores.list</code></p>
<p><code>gkebackup.volumeBackups.*</code></p>
<ul>
<li><code>gkebackup.volumeBackups.get</code></li>
<li><code>gkebackup.volumeBackups.list</code></li>
</ul>
<p><code>gkebackup.volumeRestores.*</code></p>
<ul>
<li><code>gkebackup.volumeRestores.get</code></li>
<li><code>gkebackup.volumeRestores.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Backup for GKE Backup Admin
<p>( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p>Allows administrators to manage all BackupPlan and Backup resources.</p></td>
<td><p><code>gkebackup.backupChannels.get</code></p>
<p><code>gkebackup.backupChannels.list</code></p>
<p><code>gkebackup.backupPlanBindings.*</code></p>
<ul>
<li><code>gkebackup. backupPlanBindings. get</code></li>
<li><code>gkebackup. backupPlanBindings. list</code></li>
</ul>
<p><code>gkebackup.backupPlans.*</code></p>
<ul>
<li><code>gkebackup.backupPlans.create</code></li>
<li><code>gkebackup.backupPlans.delete</code></li>
<li><code>gkebackup.backupPlans.get</code></li>
<li><code>gkebackup. backupPlans. getIamPolicy</code></li>
<li><code>gkebackup.backupPlans.list</code></li>
<li><code>gkebackup. backupPlans. setIamPolicy</code></li>
<li><code>gkebackup.backupPlans.update</code></li>
</ul>
<p><code>gkebackup.backups.*</code></p>
<ul>
<li><code>gkebackup.backups.create</code></li>
<li><code>gkebackup.backups.delete</code></li>
<li><code>gkebackup.backups.get</code></li>
<li><code>gkebackup. backups. getBackupIndex</code></li>
<li><code>gkebackup.backups.list</code></li>
<li><code>gkebackup.backups.update</code></li>
</ul>
<p><code>gkebackup.locations.*</code></p>
<ul>
<li><code>gkebackup.locations.get</code></li>
<li><code>gkebackup.locations.list</code></li>
</ul>
<p><code>gkebackup.operations.get</code></p>
<p><code>gkebackup.operations.list</code></p>
<p><code>gkebackup.restoreChannels.*</code></p>
<ul>
<li><code>gkebackup. restoreChannels. create</code></li>
<li><code>gkebackup. restoreChannels. delete</code></li>
<li><code>gkebackup.restoreChannels.get</code></li>
<li><code>gkebackup.restoreChannels.list</code></li>
<li><code>gkebackup. restoreChannels. update</code></li>
</ul>
<p><code>gkebackup. restorePlanBindings.*</code></p>
<ul>
<li><code>gkebackup. restorePlanBindings. get</code></li>
<li><code>gkebackup. restorePlanBindings. list</code></li>
</ul>
<p><code>gkebackup.volumeBackups.*</code></p>
<ul>
<li><code>gkebackup.volumeBackups.get</code></li>
<li><code>gkebackup.volumeBackups.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Backup for GKE Delegated Backup Admin
<p>( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p>
<p>Allows administrators to manage Backup resources for specific BackupPlans</p></td>
<td><p><code>gkebackup.backupChannels.get</code></p>
<p><code>gkebackup.backupChannels.list</code></p>
<p><code>gkebackup.backupPlanBindings.*</code></p>
<ul>
<li><code>gkebackup. backupPlanBindings. get</code></li>
<li><code>gkebackup. backupPlanBindings. list</code></li>
</ul>
<p><code>gkebackup.backupPlans.get</code></p>
<p><code>gkebackup.backups.*</code></p>
<ul>
<li><code>gkebackup.backups.create</code></li>
<li><code>gkebackup.backups.delete</code></li>
<li><code>gkebackup.backups.get</code></li>
<li><code>gkebackup. backups. getBackupIndex</code></li>
<li><code>gkebackup.backups.list</code></li>
<li><code>gkebackup.backups.update</code></li>
</ul>
<p><code>gkebackup.volumeBackups.*</code></p>
<ul>
<li><code>gkebackup.volumeBackups.get</code></li>
<li><code>gkebackup.volumeBackups.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Backup for GKE Delegated Restore Admin
<p>( <code>roles/ gkebackup.delegatedRestoreAdmin</code> )</p>
<p>Allows administrators to manage Restore resources for specific RestorePlans</p></td>
<td><p><code>gkebackup.restorePlans.get</code></p>
<p><code>gkebackup.restores.*</code></p>
<ul>
<li><code>gkebackup.restores.create</code></li>
<li><code>gkebackup.restores.delete</code></li>
<li><code>gkebackup.restores.get</code></li>
<li><code>gkebackup.restores.list</code></li>
<li><code>gkebackup.restores.update</code></li>
</ul>
<p><code>gkebackup.volumeRestores.*</code></p>
<ul>
<li><code>gkebackup.volumeRestores.get</code></li>
<li><code>gkebackup.volumeRestores.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Backup for GKE Restore Admin
<p>( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p>Allows administrators to manage all RestorePlan and Restore resources.</p></td>
<td><p><code>gkebackup.backupPlans.get</code></p>
<p><code>gkebackup.backupPlans.list</code></p>
<p><code>gkebackup.backups.get</code></p>
<p><code>gkebackup. backups. getBackupIndex</code></p>
<p><code>gkebackup.backups.list</code></p>
<p><code>gkebackup.locations.*</code></p>
<ul>
<li><code>gkebackup.locations.get</code></li>
<li><code>gkebackup.locations.list</code></li>
</ul>
<p><code>gkebackup.operations.get</code></p>
<p><code>gkebackup.operations.list</code></p>
<p><code>gkebackup.restoreChannels.get</code></p>
<p><code>gkebackup.restoreChannels.list</code></p>
<p><code>gkebackup. restorePlanBindings.*</code></p>
<ul>
<li><code>gkebackup. restorePlanBindings. get</code></li>
<li><code>gkebackup. restorePlanBindings. list</code></li>
</ul>
<p><code>gkebackup.restorePlans.*</code></p>
<ul>
<li><code>gkebackup.restorePlans.create</code></li>
<li><code>gkebackup.restorePlans.delete</code></li>
<li><code>gkebackup.restorePlans.get</code></li>
<li><code>gkebackup. restorePlans. getIamPolicy</code></li>
<li><code>gkebackup.restorePlans.list</code></li>
<li><code>gkebackup. restorePlans. setIamPolicy</code></li>
<li><code>gkebackup.restorePlans.update</code></li>
</ul>
<p><code>gkebackup.restores.*</code></p>
<ul>
<li><code>gkebackup.restores.create</code></li>
<li><code>gkebackup.restores.delete</code></li>
<li><code>gkebackup.restores.get</code></li>
<li><code>gkebackup.restores.list</code></li>
<li><code>gkebackup.restores.update</code></li>
</ul>
<p><code>gkebackup.volumeBackups.*</code></p>
<ul>
<li><code>gkebackup.volumeBackups.get</code></li>
<li><code>gkebackup.volumeBackups.list</code></li>
</ul>
<p><code>gkebackup.volumeRestores.*</code></p>
<ul>
<li><code>gkebackup.volumeRestores.get</code></li>
<li><code>gkebackup.volumeRestores.list</code></li>
</ul>
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
<td>Backup for GKE Cross Project Service Agent
<p>( <code>roles/ gkebackup.crossProjectServiceAgent</code> )</p>
<p>Grants permissions to execute Backup for GKE resources across projects.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td></td>
</tr>
<tr class="even">
<td>Backup for GKE Service Agent
<p>( <code>roles/ gkebackup.serviceAgent</code> )</p>
<p>Grants the Backup for GKE Service Account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>compute.disks.create</code></p>
<p><code>compute.disks.createSnapshot</code></p>
<p><code>compute.disks.get</code></p>
<p><code>compute.disks.list</code></p>
<p><code>compute.disks.setLabels</code></p>
<p><code>compute.disks.useReadOnly</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.snapshots.delete</code></p>
<p><code>compute.snapshots.get</code></p>
<p><code>compute.storagePools.use</code></p>
<p><code>compute.zoneOperations.get</code></p>
<p><code>container.apiServices.*</code></p>
<ul>
<li><code>container.apiServices.create</code></li>
<li><code>container.apiServices.delete</code></li>
<li><code>container.apiServices.get</code></li>
<li><code>container. apiServices. getStatus</code></li>
<li><code>container.apiServices.list</code></li>
<li><code>container.apiServices.update</code></li>
<li><code>container. apiServices. updateStatus</code></li>
</ul>
<p><code>container.auditSinks.*</code></p>
<ul>
<li><code>container.auditSinks.create</code></li>
<li><code>container.auditSinks.delete</code></li>
<li><code>container.auditSinks.get</code></li>
<li><code>container.auditSinks.list</code></li>
<li><code>container.auditSinks.update</code></li>
</ul>
<p><code>container.backendConfigs.*</code></p>
<ul>
<li><code>container. backendConfigs. create</code></li>
<li><code>container. backendConfigs. delete</code></li>
<li><code>container.backendConfigs.get</code></li>
<li><code>container.backendConfigs.list</code></li>
<li><code>container. backendConfigs. update</code></li>
</ul>
<p><code>container.bindings.*</code></p>
<ul>
<li><code>container.bindings.create</code></li>
<li><code>container.bindings.delete</code></li>
<li><code>container.bindings.get</code></li>
<li><code>container.bindings.list</code></li>
<li><code>container.bindings.update</code></li>
</ul>
<p><code>container. certificateSigningRequests. create</code></p>
<p><code>container. certificateSigningRequests. delete</code></p>
<p><code>container. certificateSigningRequests. get</code></p>
<p><code>container. certificateSigningRequests. list</code></p>
<p><code>container. certificateSigningRequests. update</code></p>
<p><code>container. certificateSigningRequests. updateStatus</code></p>
<p><code>container. clusterRoleBindings. get</code></p>
<p><code>container. clusterRoleBindings. list</code></p>
<p><code>container.clusterRoles.get</code></p>
<p><code>container.clusterRoles.list</code></p>
<p><code>container.clusters.connect</code></p>
<p><code>container.clusters.get</code></p>
<p><code>container.clusters.list</code></p>
<p><code>container.clusters.update</code></p>
<p><code>container.componentStatuses.*</code></p>
<ul>
<li><code>container. componentStatuses. get</code></li>
<li><code>container. componentStatuses. list</code></li>
</ul>
<p><code>container.configMaps.*</code></p>
<ul>
<li><code>container.configMaps.create</code></li>
<li><code>container.configMaps.delete</code></li>
<li><code>container.configMaps.get</code></li>
<li><code>container.configMaps.list</code></li>
<li><code>container.configMaps.update</code></li>
</ul>
<p><code>container. controllerRevisions. get</code></p>
<p><code>container. controllerRevisions. list</code></p>
<p><code>container.cronJobs.*</code></p>
<ul>
<li><code>container.cronJobs.create</code></li>
<li><code>container.cronJobs.delete</code></li>
<li><code>container.cronJobs.get</code></li>
<li><code>container.cronJobs.getStatus</code></li>
<li><code>container.cronJobs.list</code></li>
<li><code>container.cronJobs.update</code></li>
<li><code>container. cronJobs. updateStatus</code></li>
</ul>
<p><code>container.csiDrivers.*</code></p>
<ul>
<li><code>container.csiDrivers.create</code></li>
<li><code>container.csiDrivers.delete</code></li>
<li><code>container.csiDrivers.get</code></li>
<li><code>container.csiDrivers.list</code></li>
<li><code>container.csiDrivers.update</code></li>
</ul>
<p><code>container.csiNodeInfos.*</code></p>
<ul>
<li><code>container.csiNodeInfos.create</code></li>
<li><code>container.csiNodeInfos.delete</code></li>
<li><code>container.csiNodeInfos.get</code></li>
<li><code>container.csiNodeInfos.list</code></li>
<li><code>container.csiNodeInfos.update</code></li>
</ul>
<p><code>container.csiNodes.*</code></p>
<ul>
<li><code>container.csiNodes.create</code></li>
<li><code>container.csiNodes.delete</code></li>
<li><code>container.csiNodes.get</code></li>
<li><code>container.csiNodes.list</code></li>
<li><code>container.csiNodes.update</code></li>
</ul>
<p><code>container. customResourceDefinitions.*</code></p>
<ul>
<li><code>container. customResourceDefinitions. create</code></li>
<li><code>container. customResourceDefinitions. delete</code></li>
<li><code>container. customResourceDefinitions. get</code></li>
<li><code>container. customResourceDefinitions. getStatus</code></li>
<li><code>container. customResourceDefinitions. list</code></li>
<li><code>container. customResourceDefinitions. update</code></li>
<li><code>container. customResourceDefinitions. updateStatus</code></li>
</ul>
<p><code>container.daemonSets.*</code></p>
<ul>
<li><code>container.daemonSets.create</code></li>
<li><code>container.daemonSets.delete</code></li>
<li><code>container.daemonSets.get</code></li>
<li><code>container.daemonSets.getStatus</code></li>
<li><code>container.daemonSets.list</code></li>
<li><code>container.daemonSets.update</code></li>
<li><code>container. daemonSets. updateStatus</code></li>
</ul>
<p><code>container.deployments.*</code></p>
<ul>
<li><code>container.deployments.create</code></li>
<li><code>container.deployments.delete</code></li>
<li><code>container.deployments.get</code></li>
<li><code>container.deployments.getScale</code></li>
<li><code>container. deployments. getStatus</code></li>
<li><code>container.deployments.list</code></li>
<li><code>container.deployments.rollback</code></li>
<li><code>container.deployments.update</code></li>
<li><code>container. deployments. updateScale</code></li>
<li><code>container. deployments. updateStatus</code></li>
</ul>
<p><code>container.endpointSlices.*</code></p>
<ul>
<li><code>container. endpointSlices. create</code></li>
<li><code>container. endpointSlices. delete</code></li>
<li><code>container.endpointSlices.get</code></li>
<li><code>container.endpointSlices.list</code></li>
<li><code>container. endpointSlices. update</code></li>
</ul>
<p><code>container.endpoints.*</code></p>
<ul>
<li><code>container.endpoints.create</code></li>
<li><code>container.endpoints.delete</code></li>
<li><code>container.endpoints.get</code></li>
<li><code>container.endpoints.list</code></li>
<li><code>container.endpoints.update</code></li>
</ul>
<p><code>container.events.*</code></p>
<ul>
<li><code>container.events.create</code></li>
<li><code>container.events.delete</code></li>
<li><code>container.events.get</code></li>
<li><code>container.events.list</code></li>
<li><code>container.events.update</code></li>
</ul>
<p><code>container.frontendConfigs.*</code></p>
<ul>
<li><code>container. frontendConfigs. create</code></li>
<li><code>container. frontendConfigs. delete</code></li>
<li><code>container.frontendConfigs.get</code></li>
<li><code>container.frontendConfigs.list</code></li>
<li><code>container. frontendConfigs. update</code></li>
</ul>
<p><code>container. horizontalPodAutoscalers.*</code></p>
<ul>
<li><code>container. horizontalPodAutoscalers. create</code></li>
<li><code>container. horizontalPodAutoscalers. delete</code></li>
<li><code>container. horizontalPodAutoscalers. get</code></li>
<li><code>container. horizontalPodAutoscalers. getStatus</code></li>
<li><code>container. horizontalPodAutoscalers. list</code></li>
<li><code>container. horizontalPodAutoscalers. update</code></li>
<li><code>container. horizontalPodAutoscalers. updateStatus</code></li>
</ul>
<p><code>container.ingresses.*</code></p>
<ul>
<li><code>container.ingresses.create</code></li>
<li><code>container.ingresses.delete</code></li>
<li><code>container.ingresses.get</code></li>
<li><code>container.ingresses.getStatus</code></li>
<li><code>container.ingresses.list</code></li>
<li><code>container.ingresses.update</code></li>
<li><code>container. ingresses. updateStatus</code></li>
</ul>
<p><code>container. initializerConfigurations.*</code></p>
<ul>
<li><code>container. initializerConfigurations. create</code></li>
<li><code>container. initializerConfigurations. delete</code></li>
<li><code>container. initializerConfigurations. get</code></li>
<li><code>container. initializerConfigurations. list</code></li>
<li><code>container. initializerConfigurations. update</code></li>
</ul>
<p><code>container.jobs.*</code></p>
<ul>
<li><code>container.jobs.create</code></li>
<li><code>container.jobs.delete</code></li>
<li><code>container.jobs.get</code></li>
<li><code>container.jobs.getStatus</code></li>
<li><code>container.jobs.list</code></li>
<li><code>container.jobs.update</code></li>
<li><code>container.jobs.updateStatus</code></li>
</ul>
<p><code>container.leases.*</code></p>
<ul>
<li><code>container.leases.create</code></li>
<li><code>container.leases.delete</code></li>
<li><code>container.leases.get</code></li>
<li><code>container.leases.list</code></li>
<li><code>container.leases.update</code></li>
</ul>
<p><code>container.limitRanges.*</code></p>
<ul>
<li><code>container.limitRanges.create</code></li>
<li><code>container.limitRanges.delete</code></li>
<li><code>container.limitRanges.get</code></li>
<li><code>container.limitRanges.list</code></li>
<li><code>container.limitRanges.update</code></li>
</ul>
<p><code>container. localSubjectAccessReviews.*</code></p>
<ul>
<li><code>container. localSubjectAccessReviews. create</code></li>
<li><code>container. localSubjectAccessReviews. list</code></li>
</ul>
<p><code>container. managedCertificates.*</code></p>
<ul>
<li><code>container. managedCertificates. create</code></li>
<li><code>container. managedCertificates. delete</code></li>
<li><code>container. managedCertificates. get</code></li>
<li><code>container. managedCertificates. list</code></li>
<li><code>container. managedCertificates. update</code></li>
</ul>
<p><code>container. mutatingWebhookConfigurations. get</code></p>
<p><code>container. mutatingWebhookConfigurations. list</code></p>
<p><code>container.namespaces.*</code></p>
<ul>
<li><code>container.namespaces.create</code></li>
<li><code>container.namespaces.delete</code></li>
<li><code>container.namespaces.finalize</code></li>
<li><code>container.namespaces.get</code></li>
<li><code>container.namespaces.getStatus</code></li>
<li><code>container.namespaces.list</code></li>
<li><code>container.namespaces.update</code></li>
<li><code>container. namespaces. updateStatus</code></li>
</ul>
<p><code>container.networkPolicies.*</code></p>
<ul>
<li><code>container. networkPolicies. create</code></li>
<li><code>container. networkPolicies. delete</code></li>
<li><code>container.networkPolicies.get</code></li>
<li><code>container.networkPolicies.list</code></li>
<li><code>container. networkPolicies. update</code></li>
</ul>
<p><code>container.nodes.*</code></p>
<ul>
<li><code>container.nodes.create</code></li>
<li><code>container.nodes.delete</code></li>
<li><code>container.nodes.get</code></li>
<li><code>container.nodes.getStatus</code></li>
<li><code>container.nodes.list</code></li>
<li><code>container.nodes.proxy</code></li>
<li><code>container.nodes.update</code></li>
<li><code>container.nodes.updateStatus</code></li>
</ul>
<p><code>container.operations.*</code></p>
<ul>
<li><code>container.operations.get</code></li>
<li><code>container.operations.list</code></li>
</ul>
<p><code>container. persistentVolumeClaims.*</code></p>
<ul>
<li><code>container. persistentVolumeClaims. create</code></li>
<li><code>container. persistentVolumeClaims. delete</code></li>
<li><code>container. persistentVolumeClaims. get</code></li>
<li><code>container. persistentVolumeClaims. getStatus</code></li>
<li><code>container. persistentVolumeClaims. list</code></li>
<li><code>container. persistentVolumeClaims. update</code></li>
<li><code>container. persistentVolumeClaims. updateStatus</code></li>
</ul>
<p><code>container.persistentVolumes.*</code></p>
<ul>
<li><code>container. persistentVolumes. create</code></li>
<li><code>container. persistentVolumes. delete</code></li>
<li><code>container. persistentVolumes. get</code></li>
<li><code>container. persistentVolumes. getStatus</code></li>
<li><code>container. persistentVolumes. list</code></li>
<li><code>container. persistentVolumes. update</code></li>
<li><code>container. persistentVolumes. updateStatus</code></li>
</ul>
<p><code>container.petSets.*</code></p>
<ul>
<li><code>container.petSets.create</code></li>
<li><code>container.petSets.delete</code></li>
<li><code>container.petSets.get</code></li>
<li><code>container.petSets.list</code></li>
<li><code>container.petSets.update</code></li>
<li><code>container.petSets.updateStatus</code></li>
</ul>
<p><code>container. podDisruptionBudgets.*</code></p>
<ul>
<li><code>container. podDisruptionBudgets. create</code></li>
<li><code>container. podDisruptionBudgets. delete</code></li>
<li><code>container. podDisruptionBudgets. get</code></li>
<li><code>container. podDisruptionBudgets. getStatus</code></li>
<li><code>container. podDisruptionBudgets. list</code></li>
<li><code>container. podDisruptionBudgets. update</code></li>
<li><code>container. podDisruptionBudgets. updateStatus</code></li>
</ul>
<p><code>container.podPresets.*</code></p>
<ul>
<li><code>container.podPresets.create</code></li>
<li><code>container.podPresets.delete</code></li>
<li><code>container.podPresets.get</code></li>
<li><code>container.podPresets.list</code></li>
<li><code>container.podPresets.update</code></li>
</ul>
<p><code>container. podSecurityPolicies. get</code></p>
<p><code>container. podSecurityPolicies. list</code></p>
<p><code>container.podTemplates.*</code></p>
<ul>
<li><code>container.podTemplates.create</code></li>
<li><code>container.podTemplates.delete</code></li>
<li><code>container.podTemplates.get</code></li>
<li><code>container.podTemplates.list</code></li>
<li><code>container.podTemplates.update</code></li>
</ul>
<p><code>container.pods.*</code></p>
<ul>
<li><code>container.pods.attach</code></li>
<li><code>container.pods.create</code></li>
<li><code>container.pods.delete</code></li>
<li><code>container.pods.evict</code></li>
<li><code>container.pods.exec</code></li>
<li><code>container.pods.get</code></li>
<li><code>container.pods.getLogs</code></li>
<li><code>container.pods.getStatus</code></li>
<li><code>container.pods.initialize</code></li>
<li><code>container.pods.list</code></li>
<li><code>container.pods.portForward</code></li>
<li><code>container.pods.proxy</code></li>
<li><code>container.pods.update</code></li>
<li><code>container.pods.updateStatus</code></li>
</ul>
<p><code>container.priorityClasses.*</code></p>
<ul>
<li><code>container. priorityClasses. create</code></li>
<li><code>container. priorityClasses. delete</code></li>
<li><code>container.priorityClasses.get</code></li>
<li><code>container.priorityClasses.list</code></li>
<li><code>container. priorityClasses. update</code></li>
</ul>
<p><code>container.replicaSets.*</code></p>
<ul>
<li><code>container.replicaSets.create</code></li>
<li><code>container.replicaSets.delete</code></li>
<li><code>container.replicaSets.get</code></li>
<li><code>container.replicaSets.getScale</code></li>
<li><code>container. replicaSets. getStatus</code></li>
<li><code>container.replicaSets.list</code></li>
<li><code>container.replicaSets.update</code></li>
<li><code>container. replicaSets. updateScale</code></li>
<li><code>container. replicaSets. updateStatus</code></li>
</ul>
<p><code>container. replicationControllers.*</code></p>
<ul>
<li><code>container. replicationControllers. create</code></li>
<li><code>container. replicationControllers. delete</code></li>
<li><code>container. replicationControllers. get</code></li>
<li><code>container. replicationControllers. getScale</code></li>
<li><code>container. replicationControllers. getStatus</code></li>
<li><code>container. replicationControllers. list</code></li>
<li><code>container. replicationControllers. update</code></li>
<li><code>container. replicationControllers. updateScale</code></li>
<li><code>container. replicationControllers. updateStatus</code></li>
</ul>
<p><code>container.resourceQuotas.*</code></p>
<ul>
<li><code>container. resourceQuotas. create</code></li>
<li><code>container. resourceQuotas. delete</code></li>
<li><code>container.resourceQuotas.get</code></li>
<li><code>container. resourceQuotas. getStatus</code></li>
<li><code>container.resourceQuotas.list</code></li>
<li><code>container. resourceQuotas. update</code></li>
<li><code>container. resourceQuotas. updateStatus</code></li>
</ul>
<p><code>container.roleBindings.get</code></p>
<p><code>container.roleBindings.list</code></p>
<p><code>container.roles.get</code></p>
<p><code>container.roles.list</code></p>
<p><code>container.runtimeClasses.*</code></p>
<ul>
<li><code>container. runtimeClasses. create</code></li>
<li><code>container. runtimeClasses. delete</code></li>
<li><code>container.runtimeClasses.get</code></li>
<li><code>container.runtimeClasses.list</code></li>
<li><code>container. runtimeClasses. update</code></li>
</ul>
<p><code>container.scheduledJobs.*</code></p>
<ul>
<li><code>container.scheduledJobs.create</code></li>
<li><code>container.scheduledJobs.delete</code></li>
<li><code>container.scheduledJobs.get</code></li>
<li><code>container.scheduledJobs.list</code></li>
<li><code>container.scheduledJobs.update</code></li>
<li><code>container. scheduledJobs. updateStatus</code></li>
</ul>
<p><code>container.secrets.*</code></p>
<ul>
<li><code>container.secrets.create</code></li>
<li><code>container.secrets.delete</code></li>
<li><code>container.secrets.get</code></li>
<li><code>container.secrets.list</code></li>
<li><code>container.secrets.update</code></li>
</ul>
<p><code>container. selfSubjectAccessReviews.*</code></p>
<ul>
<li><code>container. selfSubjectAccessReviews. create</code></li>
<li><code>container. selfSubjectAccessReviews. list</code></li>
</ul>
<p><code>container. selfSubjectRulesReviews. create</code></p>
<p><code>container.serviceAccounts.*</code></p>
<ul>
<li><code>container. serviceAccounts. create</code></li>
<li><code>container. serviceAccounts. createToken</code></li>
<li><code>container. serviceAccounts. delete</code></li>
<li><code>container.serviceAccounts.get</code></li>
<li><code>container.serviceAccounts.list</code></li>
<li><code>container. serviceAccounts. update</code></li>
</ul>
<p><code>container.services.*</code></p>
<ul>
<li><code>container.services.create</code></li>
<li><code>container.services.delete</code></li>
<li><code>container.services.get</code></li>
<li><code>container.services.getStatus</code></li>
<li><code>container.services.list</code></li>
<li><code>container.services.proxy</code></li>
<li><code>container.services.update</code></li>
<li><code>container. services. updateStatus</code></li>
</ul>
<p><code>container.statefulSets.*</code></p>
<ul>
<li><code>container.statefulSets.create</code></li>
<li><code>container.statefulSets.delete</code></li>
<li><code>container.statefulSets.get</code></li>
<li><code>container. statefulSets. getScale</code></li>
<li><code>container. statefulSets. getStatus</code></li>
<li><code>container.statefulSets.list</code></li>
<li><code>container.statefulSets.update</code></li>
<li><code>container. statefulSets. updateScale</code></li>
<li><code>container. statefulSets. updateStatus</code></li>
</ul>
<p><code>container.storageClasses.*</code></p>
<ul>
<li><code>container. storageClasses. create</code></li>
<li><code>container. storageClasses. delete</code></li>
<li><code>container.storageClasses.get</code></li>
<li><code>container.storageClasses.list</code></li>
<li><code>container. storageClasses. update</code></li>
</ul>
<p><code>container.storageStates.*</code></p>
<ul>
<li><code>container.storageStates.create</code></li>
<li><code>container.storageStates.delete</code></li>
<li><code>container.storageStates.get</code></li>
<li><code>container. storageStates. getStatus</code></li>
<li><code>container.storageStates.list</code></li>
<li><code>container.storageStates.update</code></li>
<li><code>container. storageStates. updateStatus</code></li>
</ul>
<p><code>container. storageVersionMigrations.*</code></p>
<ul>
<li><code>container. storageVersionMigrations. create</code></li>
<li><code>container. storageVersionMigrations. delete</code></li>
<li><code>container. storageVersionMigrations. get</code></li>
<li><code>container. storageVersionMigrations. getStatus</code></li>
<li><code>container. storageVersionMigrations. list</code></li>
<li><code>container. storageVersionMigrations. update</code></li>
<li><code>container. storageVersionMigrations. updateStatus</code></li>
</ul>
<p><code>container. subjectAccessReviews.*</code></p>
<ul>
<li><code>container. subjectAccessReviews. create</code></li>
<li><code>container. subjectAccessReviews. list</code></li>
</ul>
<p><code>container.thirdPartyObjects.*</code></p>
<ul>
<li><code>container. thirdPartyObjects. create</code></li>
<li><code>container. thirdPartyObjects. delete</code></li>
<li><code>container. thirdPartyObjects. get</code></li>
<li><code>container. thirdPartyObjects. list</code></li>
<li><code>container. thirdPartyObjects. update</code></li>
</ul>
<p><code>container. thirdPartyResources.*</code></p>
<ul>
<li><code>container. thirdPartyResources. create</code></li>
<li><code>container. thirdPartyResources. delete</code></li>
<li><code>container. thirdPartyResources. get</code></li>
<li><code>container. thirdPartyResources. list</code></li>
<li><code>container. thirdPartyResources. update</code></li>
</ul>
<p><code>container.tokenReviews.create</code></p>
<p><code>container.updateInfos.*</code></p>
<ul>
<li><code>container.updateInfos.create</code></li>
<li><code>container.updateInfos.delete</code></li>
<li><code>container.updateInfos.get</code></li>
<li><code>container.updateInfos.list</code></li>
<li><code>container.updateInfos.update</code></li>
</ul>
<p><code>container. validatingWebhookConfigurations. get</code></p>
<p><code>container. validatingWebhookConfigurations. list</code></p>
<p><code>container.volumeAttachments.*</code></p>
<ul>
<li><code>container. volumeAttachments. create</code></li>
<li><code>container. volumeAttachments. delete</code></li>
<li><code>container. volumeAttachments. get</code></li>
<li><code>container. volumeAttachments. getStatus</code></li>
<li><code>container. volumeAttachments. list</code></li>
<li><code>container. volumeAttachments. update</code></li>
<li><code>container. volumeAttachments. updateStatus</code></li>
</ul>
<p><code>container. volumeSnapshotClasses.*</code></p>
<ul>
<li><code>container. volumeSnapshotClasses. create</code></li>
<li><code>container. volumeSnapshotClasses. delete</code></li>
<li><code>container. volumeSnapshotClasses. get</code></li>
<li><code>container. volumeSnapshotClasses. list</code></li>
<li><code>container. volumeSnapshotClasses. update</code></li>
</ul>
<p><code>container. volumeSnapshotContents.*</code></p>
<ul>
<li><code>container. volumeSnapshotContents. create</code></li>
<li><code>container. volumeSnapshotContents. delete</code></li>
<li><code>container. volumeSnapshotContents. get</code></li>
<li><code>container. volumeSnapshotContents. getStatus</code></li>
<li><code>container. volumeSnapshotContents. list</code></li>
<li><code>container. volumeSnapshotContents. update</code></li>
<li><code>container. volumeSnapshotContents. updateStatus</code></li>
</ul>
<p><code>container.volumeSnapshots.*</code></p>
<ul>
<li><code>container. volumeSnapshots. create</code></li>
<li><code>container. volumeSnapshots. delete</code></li>
<li><code>container.volumeSnapshots.get</code></li>
<li><code>container. volumeSnapshots. getStatus</code></li>
<li><code>container.volumeSnapshots.list</code></li>
<li><code>container. volumeSnapshots. update</code></li>
<li><code>container. volumeSnapshots. updateStatus</code></li>
</ul>
<p><code>gkebackup.operations.get</code></p>
<p><code>recommender. containerDiagnosisInsights.*</code></p>
<ul>
<li><code>recommender. containerDiagnosisInsights. get</code></li>
<li><code>recommender. containerDiagnosisInsights. list</code></li>
<li><code>recommender. containerDiagnosisInsights. update</code></li>
</ul>
<p><code>recommender. containerDiagnosisRecommendations.*</code></p>
<ul>
<li><code>recommender. containerDiagnosisRecommendations. get</code></li>
<li><code>recommender. containerDiagnosisRecommendations. list</code></li>
<li><code>recommender. containerDiagnosisRecommendations. update</code></li>
</ul>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>recommender. networkAnalyzerGkeConnectivityInsights.*</code></p>
<ul>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. get</code></li>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. list</code></li>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. update</code></li>
</ul>
<p><code>recommender. networkAnalyzerGkeIpAddressInsights.*</code></p>
<ul>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. get</code></li>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. list</code></li>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager. projects. updateLiens</code></p></td>
</tr>
</tbody>
</table>

## Backup for GKE permissions

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
<td><code>gkebackup. backupChannels. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup. backupChannels. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.backupChannels.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.backupChannels.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup. backupChannels. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup. backupPlanBindings. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup. backupPlanBindings. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.backupPlans.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.backupPlans.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.backupPlans.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup. backupPlans. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.backupPlans.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup. backupPlans. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.backupPlans.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.backups.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.backups.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.backups.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup. backups. getBackupIndex</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.backups.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.backups.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.serviceAgent">Backup for GKE Service Agent</a> ( <code>roles/ gkebackup.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>gkebackup.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup. restoreChannels. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup. restoreChannels. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.restoreChannels.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.restoreChannels.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup. restoreChannels. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup. restorePlanBindings. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup. restorePlanBindings. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.restorePlans.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.restorePlans.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.restorePlans.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code>roles/ gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup. restorePlans. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.restorePlans.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup. restorePlans. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.restorePlans.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.restores.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code>roles/ gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.restores.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code>roles/ gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.restores.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code>roles/ gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.restores.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code>roles/ gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.restores.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code>roles/ gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.volumeBackups.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.volumeBackups.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code>roles/ gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkebackup.volumeRestores.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code>roles/ gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkebackup.volumeRestores.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Backup for GKE Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code>roles/ gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
