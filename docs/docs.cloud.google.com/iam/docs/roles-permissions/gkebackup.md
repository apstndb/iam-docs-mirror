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
<td><h4 id="gkebackup.admin" class="role-title add-link" data-text="Backup for GKE Admin" tabindex="-1">Backup for GKE Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p>Full access to all Backup for GKE resources.</p></td>
<td><p><code dir="ltr" translate="no">gkebackup.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.  backupChannels.  create</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupChannels.  delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.backupChannels.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.backupChannels.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupChannels.  update</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  list</code></li>
<li><code dir="ltr" translate="no">gkebackup.backupPlans.create</code></li>
<li><code dir="ltr" translate="no">gkebackup.backupPlans.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.backupPlans.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupPlans.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkebackup.backupPlans.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupPlans.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkebackup.backupPlans.update</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.create</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backups.  getBackupIndex</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.update</code></li>
<li><code dir="ltr" translate="no">gkebackup.locations.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.locations.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.operations.cancel</code></li>
<li><code dir="ltr" translate="no">gkebackup.operations.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.operations.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.operations.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restoreChannels.  create</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restoreChannels.  delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.restoreChannels.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.restoreChannels.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restoreChannels.  update</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  list</code></li>
<li><code dir="ltr" translate="no">gkebackup.restorePlans.create</code></li>
<li><code dir="ltr" translate="no">gkebackup.restorePlans.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.restorePlans.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restorePlans.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkebackup.restorePlans.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restorePlans.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkebackup.restorePlans.update</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.create</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.update</code></li>
<li><code dir="ltr" translate="no">gkebackup.volumeBackups.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.volumeBackups.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.volumeRestores.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.volumeRestores.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.editor" class="role-title add-link" data-text="Gkebackup Editor" tabindex="-1">Gkebackup Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p>Editor role for gkebackup</p></td>
<td><p><code dir="ltr" translate="no">gkebackup.backupChannels.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.  backupChannels.  create</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupChannels.  delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.backupChannels.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.backupChannels.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupChannels.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.backupPlanBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.backupPlans.create</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupPlans.delete</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.  backupPlans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupPlans.update</code></p>
<p><code dir="ltr" translate="no">gkebackup.backups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.backups.create</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backups.  getBackupIndex</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.locations.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.operations.cancel</code></li>
<li><code dir="ltr" translate="no">gkebackup.operations.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.operations.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.restoreChannels.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.  restoreChannels.  create</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restoreChannels.  delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.restoreChannels.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.restoreChannels.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restoreChannels.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.restorePlans.create</code></p>
<p><code dir="ltr" translate="no">gkebackup.restorePlans.delete</code></p>
<p><code dir="ltr" translate="no">gkebackup.restorePlans.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.  restorePlans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkebackup.restorePlans.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.restorePlans.update</code></p>
<p><code dir="ltr" translate="no">gkebackup.restores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.restores.create</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.volumeBackups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.volumeBackups.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.volumeBackups.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.volumeRestores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.volumeRestores.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.volumeRestores.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.viewer" class="role-title add-link" data-text="Backup for GKE Viewer" tabindex="-1">Backup for GKE Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p>Read-only access to all Backup for GKE resources.</p></td>
<td><p><code dir="ltr" translate="no">gkebackup.backupChannels.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupChannels.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupPlanBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.  backupPlans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.backups.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.  backups.  getBackupIndex</code></p>
<p><code dir="ltr" translate="no">gkebackup.backups.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.locations.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.operations.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.operations.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.restoreChannels.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.restoreChannels.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.restorePlans.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.  restorePlans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkebackup.restorePlans.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.restores.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.restores.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.volumeBackups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.volumeBackups.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.volumeBackups.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.volumeRestores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.volumeRestores.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.volumeRestores.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.backupAdmin" class="role-title add-link" data-text="Backup for GKE Backup Admin" tabindex="-1">Backup for GKE Backup Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p>Allows administrators to manage all BackupPlan and Backup resources.</p></td>
<td><p><code dir="ltr" translate="no">gkebackup.backupChannels.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupChannels.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupPlanBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.backupPlans.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.backupPlans.create</code></li>
<li><code dir="ltr" translate="no">gkebackup.backupPlans.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.backupPlans.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupPlans.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkebackup.backupPlans.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupPlans.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkebackup.backupPlans.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.backups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.backups.create</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backups.  getBackupIndex</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.locations.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.operations.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.operations.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.restoreChannels.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.  restoreChannels.  create</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restoreChannels.  delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.restoreChannels.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.restoreChannels.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restoreChannels.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.volumeBackups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.volumeBackups.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.volumeBackups.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.delegatedBackupAdmin" class="role-title add-link" data-text="Backup for GKE Delegated Backup Admin" tabindex="-1">Backup for GKE Delegated Backup Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p>
<p>Allows administrators to manage Backup resources for specific BackupPlans</p></td>
<td><p><code dir="ltr" translate="no">gkebackup.backupChannels.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupChannels.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupPlanBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.backups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.backups.create</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  backups.  getBackupIndex</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.backups.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.volumeBackups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.volumeBackups.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.volumeBackups.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.delegatedRestoreAdmin" class="role-title add-link" data-text="Backup for GKE Delegated Restore Admin" tabindex="-1">Backup for GKE Delegated Restore Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  gkebackup.delegatedRestoreAdmin</code> )</p>
<p>Allows administrators to manage Restore resources for specific RestorePlans</p></td>
<td><p><code dir="ltr" translate="no">gkebackup.restorePlans.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.restores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.restores.create</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.volumeRestores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.volumeRestores.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.volumeRestores.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.restoreAdmin" class="role-title add-link" data-text="Backup for GKE Restore Admin" tabindex="-1">Backup for GKE Restore Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p>Allows administrators to manage all RestorePlan and Restore resources.</p></td>
<td><p><code dir="ltr" translate="no">gkebackup.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.backups.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.  backups.  getBackupIndex</code></p>
<p><code dir="ltr" translate="no">gkebackup.backups.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.locations.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.operations.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.operations.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.restoreChannels.get</code></p>
<p><code dir="ltr" translate="no">gkebackup.restoreChannels.list</code></p>
<p><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.restorePlans.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.restorePlans.create</code></li>
<li><code dir="ltr" translate="no">gkebackup.restorePlans.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.restorePlans.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restorePlans.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkebackup.restorePlans.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.  restorePlans.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkebackup.restorePlans.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.restores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.restores.create</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.delete</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.list</code></li>
<li><code dir="ltr" translate="no">gkebackup.restores.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.volumeBackups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.volumeBackups.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.volumeBackups.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.volumeRestores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkebackup.volumeRestores.get</code></li>
<li><code dir="ltr" translate="no">gkebackup.volumeRestores.list</code></li>
</ul>
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
<td><h4 id="gkebackup.crossProjectServiceAgent" class="role-title add-link" data-text="Backup for GKE Cross Project Service Agent" tabindex="-1">Backup for GKE Cross Project Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  gkebackup.crossProjectServiceAgent</code> )</p>
<p>Grants permissions to execute Backup for GKE resources across projects.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.serviceAgent" class="role-title add-link" data-text="Backup for GKE Service Agent" tabindex="-1">Backup for GKE Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  gkebackup.serviceAgent</code> )</p>
<p>Grants the Backup for GKE Service Account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.disks.create</code></p>
<p><code dir="ltr" translate="no">compute.disks.createSnapshot</code></p>
<p><code dir="ltr" translate="no">compute.disks.get</code></p>
<p><code dir="ltr" translate="no">compute.disks.list</code></p>
<p><code dir="ltr" translate="no">compute.disks.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.disks.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.delete</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.get</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.use</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">container.apiServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.apiServices.create</code></li>
<li><code dir="ltr" translate="no">container.apiServices.delete</code></li>
<li><code dir="ltr" translate="no">container.apiServices.get</code></li>
<li><code dir="ltr" translate="no">container.  apiServices.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.apiServices.list</code></li>
<li><code dir="ltr" translate="no">container.apiServices.update</code></li>
<li><code dir="ltr" translate="no">container.  apiServices.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.auditSinks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.auditSinks.create</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.delete</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.get</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.list</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.backendConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  backendConfigs.  create</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.get</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.list</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.bindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.bindings.create</code></li>
<li><code dir="ltr" translate="no">container.bindings.delete</code></li>
<li><code dir="ltr" translate="no">container.bindings.get</code></li>
<li><code dir="ltr" translate="no">container.bindings.list</code></li>
<li><code dir="ltr" translate="no">container.bindings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  certificateSigningRequests.  create</code></p>
<p><code dir="ltr" translate="no">container.  certificateSigningRequests.  delete</code></p>
<p><code dir="ltr" translate="no">container.  certificateSigningRequests.  get</code></p>
<p><code dir="ltr" translate="no">container.  certificateSigningRequests.  list</code></p>
<p><code dir="ltr" translate="no">container.  certificateSigningRequests.  update</code></p>
<p><code dir="ltr" translate="no">container.  certificateSigningRequests.  updateStatus</code></p>
<p><code dir="ltr" translate="no">container.  clusterRoleBindings.  get</code></p>
<p><code dir="ltr" translate="no">container.  clusterRoleBindings.  list</code></p>
<p><code dir="ltr" translate="no">container.clusterRoles.get</code></p>
<p><code dir="ltr" translate="no">container.clusterRoles.list</code></p>
<p><code dir="ltr" translate="no">container.clusters.connect</code></p>
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">container.clusters.list</code></p>
<p><code dir="ltr" translate="no">container.clusters.update</code></p>
<p><code dir="ltr" translate="no">container.componentStatuses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  componentStatuses.  get</code></li>
<li><code dir="ltr" translate="no">container.  componentStatuses.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">container.configMaps.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.configMaps.create</code></li>
<li><code dir="ltr" translate="no">container.configMaps.delete</code></li>
<li><code dir="ltr" translate="no">container.configMaps.get</code></li>
<li><code dir="ltr" translate="no">container.configMaps.list</code></li>
<li><code dir="ltr" translate="no">container.configMaps.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  controllerRevisions.  get</code></p>
<p><code dir="ltr" translate="no">container.  controllerRevisions.  list</code></p>
<p><code dir="ltr" translate="no">container.cronJobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.cronJobs.create</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.delete</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.get</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.getStatus</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.list</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.update</code></li>
<li><code dir="ltr" translate="no">container.  cronJobs.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.csiDrivers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.csiDrivers.create</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.delete</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.get</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.list</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.csiNodeInfos.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.csiNodeInfos.create</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.delete</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.get</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.list</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.csiNodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.csiNodes.create</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.delete</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.get</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.list</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  create</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  delete</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  get</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  list</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  update</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.daemonSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.daemonSets.create</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.delete</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.get</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.getStatus</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.list</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.update</code></li>
<li><code dir="ltr" translate="no">container.  daemonSets.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.deployments.create</code></li>
<li><code dir="ltr" translate="no">container.deployments.delete</code></li>
<li><code dir="ltr" translate="no">container.deployments.get</code></li>
<li><code dir="ltr" translate="no">container.deployments.getScale</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.deployments.list</code></li>
<li><code dir="ltr" translate="no">container.deployments.rollback</code></li>
<li><code dir="ltr" translate="no">container.deployments.update</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.endpointSlices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  endpointSlices.  create</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  delete</code></li>
<li><code dir="ltr" translate="no">container.endpointSlices.get</code></li>
<li><code dir="ltr" translate="no">container.endpointSlices.list</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.endpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.endpoints.create</code></li>
<li><code dir="ltr" translate="no">container.endpoints.delete</code></li>
<li><code dir="ltr" translate="no">container.endpoints.get</code></li>
<li><code dir="ltr" translate="no">container.endpoints.list</code></li>
<li><code dir="ltr" translate="no">container.endpoints.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.events.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.events.create</code></li>
<li><code dir="ltr" translate="no">container.events.delete</code></li>
<li><code dir="ltr" translate="no">container.events.get</code></li>
<li><code dir="ltr" translate="no">container.events.list</code></li>
<li><code dir="ltr" translate="no">container.events.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.frontendConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  create</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">container.frontendConfigs.get</code></li>
<li><code dir="ltr" translate="no">container.frontendConfigs.list</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  create</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  delete</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  get</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  list</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  update</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.ingresses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.ingresses.create</code></li>
<li><code dir="ltr" translate="no">container.ingresses.delete</code></li>
<li><code dir="ltr" translate="no">container.ingresses.get</code></li>
<li><code dir="ltr" translate="no">container.ingresses.getStatus</code></li>
<li><code dir="ltr" translate="no">container.ingresses.list</code></li>
<li><code dir="ltr" translate="no">container.ingresses.update</code></li>
<li><code dir="ltr" translate="no">container.  ingresses.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  initializerConfigurations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.jobs.create</code></li>
<li><code dir="ltr" translate="no">container.jobs.delete</code></li>
<li><code dir="ltr" translate="no">container.jobs.get</code></li>
<li><code dir="ltr" translate="no">container.jobs.getStatus</code></li>
<li><code dir="ltr" translate="no">container.jobs.list</code></li>
<li><code dir="ltr" translate="no">container.jobs.update</code></li>
<li><code dir="ltr" translate="no">container.jobs.updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.leases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.leases.create</code></li>
<li><code dir="ltr" translate="no">container.leases.delete</code></li>
<li><code dir="ltr" translate="no">container.leases.get</code></li>
<li><code dir="ltr" translate="no">container.leases.list</code></li>
<li><code dir="ltr" translate="no">container.leases.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.limitRanges.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.limitRanges.create</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.delete</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.get</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.list</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  localSubjectAccessReviews.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  localSubjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  localSubjectAccessReviews.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  managedCertificates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  managedCertificates.  create</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  delete</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  get</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  list</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  get</code></p>
<p><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  list</code></p>
<p><code dir="ltr" translate="no">container.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.namespaces.create</code></li>
<li><code dir="ltr" translate="no">container.namespaces.delete</code></li>
<li><code dir="ltr" translate="no">container.namespaces.finalize</code></li>
<li><code dir="ltr" translate="no">container.namespaces.get</code></li>
<li><code dir="ltr" translate="no">container.namespaces.getStatus</code></li>
<li><code dir="ltr" translate="no">container.namespaces.list</code></li>
<li><code dir="ltr" translate="no">container.namespaces.update</code></li>
<li><code dir="ltr" translate="no">container.  namespaces.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.networkPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  networkPolicies.  create</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">container.networkPolicies.get</code></li>
<li><code dir="ltr" translate="no">container.networkPolicies.list</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.nodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.nodes.create</code></li>
<li><code dir="ltr" translate="no">container.nodes.delete</code></li>
<li><code dir="ltr" translate="no">container.nodes.get</code></li>
<li><code dir="ltr" translate="no">container.nodes.getStatus</code></li>
<li><code dir="ltr" translate="no">container.nodes.list</code></li>
<li><code dir="ltr" translate="no">container.nodes.proxy</code></li>
<li><code dir="ltr" translate="no">container.nodes.update</code></li>
<li><code dir="ltr" translate="no">container.nodes.updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.operations.get</code></li>
<li><code dir="ltr" translate="no">container.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  persistentVolumeClaims.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  create</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  delete</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  get</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  update</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.persistentVolumes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  create</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  delete</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  get</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  update</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.petSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.petSets.create</code></li>
<li><code dir="ltr" translate="no">container.petSets.delete</code></li>
<li><code dir="ltr" translate="no">container.petSets.get</code></li>
<li><code dir="ltr" translate="no">container.petSets.list</code></li>
<li><code dir="ltr" translate="no">container.petSets.update</code></li>
<li><code dir="ltr" translate="no">container.petSets.updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  podDisruptionBudgets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  create</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  delete</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  get</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  list</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  update</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.podPresets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.podPresets.create</code></li>
<li><code dir="ltr" translate="no">container.podPresets.delete</code></li>
<li><code dir="ltr" translate="no">container.podPresets.get</code></li>
<li><code dir="ltr" translate="no">container.podPresets.list</code></li>
<li><code dir="ltr" translate="no">container.podPresets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  podSecurityPolicies.  get</code></p>
<p><code dir="ltr" translate="no">container.  podSecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">container.podTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.podTemplates.create</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.delete</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.get</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.list</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.pods.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.pods.attach</code></li>
<li><code dir="ltr" translate="no">container.pods.create</code></li>
<li><code dir="ltr" translate="no">container.pods.delete</code></li>
<li><code dir="ltr" translate="no">container.pods.evict</code></li>
<li><code dir="ltr" translate="no">container.pods.exec</code></li>
<li><code dir="ltr" translate="no">container.pods.get</code></li>
<li><code dir="ltr" translate="no">container.pods.getLogs</code></li>
<li><code dir="ltr" translate="no">container.pods.getStatus</code></li>
<li><code dir="ltr" translate="no">container.pods.initialize</code></li>
<li><code dir="ltr" translate="no">container.pods.list</code></li>
<li><code dir="ltr" translate="no">container.pods.portForward</code></li>
<li><code dir="ltr" translate="no">container.pods.proxy</code></li>
<li><code dir="ltr" translate="no">container.pods.update</code></li>
<li><code dir="ltr" translate="no">container.pods.updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.priorityClasses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  priorityClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.priorityClasses.get</code></li>
<li><code dir="ltr" translate="no">container.priorityClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.replicaSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.replicaSets.create</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.delete</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.get</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.getScale</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.list</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.update</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  replicationControllers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  replicationControllers.  create</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  delete</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  get</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  getScale</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  list</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  update</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.resourceQuotas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  create</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  delete</code></li>
<li><code dir="ltr" translate="no">container.resourceQuotas.get</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.resourceQuotas.list</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  update</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.roleBindings.get</code></p>
<p><code dir="ltr" translate="no">container.roleBindings.list</code></p>
<p><code dir="ltr" translate="no">container.roles.get</code></p>
<p><code dir="ltr" translate="no">container.roles.list</code></p>
<p><code dir="ltr" translate="no">container.runtimeClasses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.runtimeClasses.get</code></li>
<li><code dir="ltr" translate="no">container.runtimeClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.scheduledJobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.scheduledJobs.create</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.delete</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.get</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.list</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.update</code></li>
<li><code dir="ltr" translate="no">container.  scheduledJobs.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.secrets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.secrets.create</code></li>
<li><code dir="ltr" translate="no">container.secrets.delete</code></li>
<li><code dir="ltr" translate="no">container.secrets.get</code></li>
<li><code dir="ltr" translate="no">container.secrets.list</code></li>
<li><code dir="ltr" translate="no">container.secrets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  selfSubjectAccessReviews.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  selfSubjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  selfSubjectAccessReviews.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  selfSubjectRulesReviews.  create</code></p>
<p><code dir="ltr" translate="no">container.serviceAccounts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  create</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  createToken</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  delete</code></li>
<li><code dir="ltr" translate="no">container.serviceAccounts.get</code></li>
<li><code dir="ltr" translate="no">container.serviceAccounts.list</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.services.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.services.create</code></li>
<li><code dir="ltr" translate="no">container.services.delete</code></li>
<li><code dir="ltr" translate="no">container.services.get</code></li>
<li><code dir="ltr" translate="no">container.services.getStatus</code></li>
<li><code dir="ltr" translate="no">container.services.list</code></li>
<li><code dir="ltr" translate="no">container.services.proxy</code></li>
<li><code dir="ltr" translate="no">container.services.update</code></li>
<li><code dir="ltr" translate="no">container.  services.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.statefulSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.statefulSets.create</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.delete</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.get</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  getScale</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.list</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.update</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.storageClasses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  storageClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.storageClasses.get</code></li>
<li><code dir="ltr" translate="no">container.storageClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.storageStates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.storageStates.create</code></li>
<li><code dir="ltr" translate="no">container.storageStates.delete</code></li>
<li><code dir="ltr" translate="no">container.storageStates.get</code></li>
<li><code dir="ltr" translate="no">container.  storageStates.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.storageStates.list</code></li>
<li><code dir="ltr" translate="no">container.storageStates.update</code></li>
<li><code dir="ltr" translate="no">container.  storageStates.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  storageVersionMigrations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  create</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  get</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  list</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  update</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  subjectAccessReviews.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  subjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  subjectAccessReviews.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">container.thirdPartyObjects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  thirdPartyResources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.tokenReviews.create</code></p>
<p><code dir="ltr" translate="no">container.updateInfos.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.updateInfos.create</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.delete</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.get</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.list</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  get</code></p>
<p><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  list</code></p>
<p><code dir="ltr" translate="no">container.volumeAttachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  volumeSnapshotClasses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  volumeSnapshotContents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.volumeSnapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  delete</code></li>
<li><code dir="ltr" translate="no">container.volumeSnapshots.get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.volumeSnapshots.list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">gkebackup.operations.get</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  updateLiens</code></p></td>
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
<td><h4 id="gkebackup.backupChannels.create" class="permission-name add-link" data-text="gkebackup.backupChannels.create" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  backupChannels.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.backupChannels.delete" class="permission-name add-link" data-text="gkebackup.backupChannels.delete" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  backupChannels.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.backupChannels.get" class="permission-name add-link" data-text="gkebackup.backupChannels.get" tabindex="-1"><code dir="ltr" translate="no">gkebackup.backupChannels.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.backupChannels.list" class="permission-name add-link" data-text="gkebackup.backupChannels.list" tabindex="-1"><code dir="ltr" translate="no">gkebackup.backupChannels.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.backupChannels.update" class="permission-name add-link" data-text="gkebackup.backupChannels.update" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  backupChannels.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.backupPlanBindings.get" class="permission-name add-link" data-text="gkebackup.backupPlanBindings.get" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.backupPlanBindings.list" class="permission-name add-link" data-text="gkebackup.backupPlanBindings.list" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  backupPlanBindings.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.backupPlans.create" class="permission-name add-link" data-text="gkebackup.backupPlans.create" tabindex="-1"><code dir="ltr" translate="no">gkebackup.backupPlans.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.backupPlans.delete" class="permission-name add-link" data-text="gkebackup.backupPlans.delete" tabindex="-1"><code dir="ltr" translate="no">gkebackup.backupPlans.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.backupPlans.get" class="permission-name add-link" data-text="gkebackup.backupPlans.get" tabindex="-1"><code dir="ltr" translate="no">gkebackup.backupPlans.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.backupPlans.getIamPolicy" class="permission-name add-link" data-text="gkebackup.backupPlans.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  backupPlans.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.backupPlans.list" class="permission-name add-link" data-text="gkebackup.backupPlans.list" tabindex="-1"><code dir="ltr" translate="no">gkebackup.backupPlans.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.backupPlans.setIamPolicy" class="permission-name add-link" data-text="gkebackup.backupPlans.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  backupPlans.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.backupPlans.update" class="permission-name add-link" data-text="gkebackup.backupPlans.update" tabindex="-1"><code dir="ltr" translate="no">gkebackup.backupPlans.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.backups.create" class="permission-name add-link" data-text="gkebackup.backups.create" tabindex="-1"><code dir="ltr" translate="no">gkebackup.backups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.backups.delete" class="permission-name add-link" data-text="gkebackup.backups.delete" tabindex="-1"><code dir="ltr" translate="no">gkebackup.backups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.backups.get" class="permission-name add-link" data-text="gkebackup.backups.get" tabindex="-1"><code dir="ltr" translate="no">gkebackup.backups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.backups.getBackupIndex" class="permission-name add-link" data-text="gkebackup.backups.getBackupIndex" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  backups.  getBackupIndex</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.backups.list" class="permission-name add-link" data-text="gkebackup.backups.list" tabindex="-1"><code dir="ltr" translate="no">gkebackup.backups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.backups.update" class="permission-name add-link" data-text="gkebackup.backups.update" tabindex="-1"><code dir="ltr" translate="no">gkebackup.backups.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.locations.get" class="permission-name add-link" data-text="gkebackup.locations.get" tabindex="-1"><code dir="ltr" translate="no">gkebackup.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.locations.list" class="permission-name add-link" data-text="gkebackup.locations.list" tabindex="-1"><code dir="ltr" translate="no">gkebackup.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.operations.cancel" class="permission-name add-link" data-text="gkebackup.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">gkebackup.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.operations.delete" class="permission-name add-link" data-text="gkebackup.operations.delete" tabindex="-1"><code dir="ltr" translate="no">gkebackup.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.operations.get" class="permission-name add-link" data-text="gkebackup.operations.get" tabindex="-1"><code dir="ltr" translate="no">gkebackup.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.serviceAgent">Backup for GKE Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.operations.list" class="permission-name add-link" data-text="gkebackup.operations.list" tabindex="-1"><code dir="ltr" translate="no">gkebackup.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.restoreChannels.create" class="permission-name add-link" data-text="gkebackup.restoreChannels.create" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  restoreChannels.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.restoreChannels.delete" class="permission-name add-link" data-text="gkebackup.restoreChannels.delete" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  restoreChannels.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.restoreChannels.get" class="permission-name add-link" data-text="gkebackup.restoreChannels.get" tabindex="-1"><code dir="ltr" translate="no">gkebackup.restoreChannels.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.restoreChannels.list" class="permission-name add-link" data-text="gkebackup.restoreChannels.list" tabindex="-1"><code dir="ltr" translate="no">gkebackup.restoreChannels.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.restoreChannels.update" class="permission-name add-link" data-text="gkebackup.restoreChannels.update" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  restoreChannels.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.restorePlanBindings.get" class="permission-name add-link" data-text="gkebackup.restorePlanBindings.get" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.restorePlanBindings.list" class="permission-name add-link" data-text="gkebackup.restorePlanBindings.list" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  restorePlanBindings.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.restorePlans.create" class="permission-name add-link" data-text="gkebackup.restorePlans.create" tabindex="-1"><code dir="ltr" translate="no">gkebackup.restorePlans.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.restorePlans.delete" class="permission-name add-link" data-text="gkebackup.restorePlans.delete" tabindex="-1"><code dir="ltr" translate="no">gkebackup.restorePlans.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.restorePlans.get" class="permission-name add-link" data-text="gkebackup.restorePlans.get" tabindex="-1"><code dir="ltr" translate="no">gkebackup.restorePlans.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.restorePlans.getIamPolicy" class="permission-name add-link" data-text="gkebackup.restorePlans.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  restorePlans.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.restorePlans.list" class="permission-name add-link" data-text="gkebackup.restorePlans.list" tabindex="-1"><code dir="ltr" translate="no">gkebackup.restorePlans.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.restorePlans.setIamPolicy" class="permission-name add-link" data-text="gkebackup.restorePlans.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">gkebackup.  restorePlans.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.restorePlans.update" class="permission-name add-link" data-text="gkebackup.restorePlans.update" tabindex="-1"><code dir="ltr" translate="no">gkebackup.restorePlans.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.restores.create" class="permission-name add-link" data-text="gkebackup.restores.create" tabindex="-1"><code dir="ltr" translate="no">gkebackup.restores.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.restores.delete" class="permission-name add-link" data-text="gkebackup.restores.delete" tabindex="-1"><code dir="ltr" translate="no">gkebackup.restores.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.restores.get" class="permission-name add-link" data-text="gkebackup.restores.get" tabindex="-1"><code dir="ltr" translate="no">gkebackup.restores.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.restores.list" class="permission-name add-link" data-text="gkebackup.restores.list" tabindex="-1"><code dir="ltr" translate="no">gkebackup.restores.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.restores.update" class="permission-name add-link" data-text="gkebackup.restores.update" tabindex="-1"><code dir="ltr" translate="no">gkebackup.restores.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.volumeBackups.get" class="permission-name add-link" data-text="gkebackup.volumeBackups.get" tabindex="-1"><code dir="ltr" translate="no">gkebackup.volumeBackups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.volumeBackups.list" class="permission-name add-link" data-text="gkebackup.volumeBackups.list" tabindex="-1"><code dir="ltr" translate="no">gkebackup.volumeBackups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedBackupAdmin">Backup for GKE Delegated Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedBackupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkebackup.volumeRestores.get" class="permission-name add-link" data-text="gkebackup.volumeRestores.get" tabindex="-1"><code dir="ltr" translate="no">gkebackup.volumeRestores.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkebackup.volumeRestores.list" class="permission-name add-link" data-text="gkebackup.volumeRestores.list" tabindex="-1"><code dir="ltr" translate="no">gkebackup.volumeRestores.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.delegatedRestoreAdmin">Backup for GKE Delegated Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.delegatedRestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
