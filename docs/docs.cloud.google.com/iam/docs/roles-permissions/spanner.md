---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/spanner
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/spanner
title: Spanner roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Spanner. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Spanner roles

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
<td><h4 id="spanner.admin" class="role-title add-link" data-text="Cloud Spanner Admin" tabindex="-1">Cloud Spanner Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p>Has complete access to all Spanner resources in a Google Cloud project. A principal with this role can:</p>
<ul>
<li>Grant and revoke permissions to other principals for all Spanner resources in the project.</li>
<li>Allocate and delete chargeable Spanner resources.</li>
<li>Issue get/list/modify operations on Cloud Spanner resources.</li>
<li>Read from and write to all Cloud Spanner databases in the project.</li>
<li>Fetch project metadata.</li>
</ul>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Instance</li>
<li>Database</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.timeSeries.create</code></li>
<li><code dir="ltr" translate="no">monitoring.timeSeries.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">spanner.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.  backupOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.backupOperations.get</code></li>
<li><code dir="ltr" translate="no">spanner.backupOperations.list</code></li>
<li><code dir="ltr" translate="no">spanner.backupSchedules.create</code></li>
<li><code dir="ltr" translate="no">spanner.backupSchedules.delete</code></li>
<li><code dir="ltr" translate="no">spanner.backupSchedules.get</code></li>
<li><code dir="ltr" translate="no">spanner.  backupSchedules.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">spanner.backupSchedules.list</code></li>
<li><code dir="ltr" translate="no">spanner.  backupSchedules.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">spanner.backupSchedules.update</code></li>
<li><code dir="ltr" translate="no">spanner.backups.copy</code></li>
<li><code dir="ltr" translate="no">spanner.backups.create</code></li>
<li><code dir="ltr" translate="no">spanner.backups.delete</code></li>
<li><code dir="ltr" translate="no">spanner.backups.get</code></li>
<li><code dir="ltr" translate="no">spanner.backups.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">spanner.backups.list</code></li>
<li><code dir="ltr" translate="no">spanner.  backups.  restoreDatabase</code></li>
<li><code dir="ltr" translate="no">spanner.backups.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">spanner.backups.update</code></li>
<li><code dir="ltr" translate="no">spanner.  databaseOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.databaseOperations.get</code></li>
<li><code dir="ltr" translate="no">spanner.  databaseOperations.  list</code></li>
<li><code dir="ltr" translate="no">spanner.databaseRoles.list</code></li>
<li><code dir="ltr" translate="no">spanner.databases.adapt</code></li>
<li><code dir="ltr" translate="no">spanner.  databases.  addSplitPoints</code></li>
<li><code dir="ltr" translate="no">spanner.  databases.  beginOrRollbackReadWriteTransaction</code></li>
<li><code dir="ltr" translate="no">spanner.  databases.  beginPartitionedDmlTransaction</code></li>
<li><code dir="ltr" translate="no">spanner.  databases.  beginReadOnlyTransaction</code></li>
<li><code dir="ltr" translate="no">spanner.databases.changequorum</code></li>
<li><code dir="ltr" translate="no">spanner.databases.create</code></li>
<li><code dir="ltr" translate="no">spanner.databases.createBackup</code></li>
<li><code dir="ltr" translate="no">spanner.databases.drop</code></li>
<li><code dir="ltr" translate="no">spanner.databases.get</code></li>
<li><code dir="ltr" translate="no">spanner.databases.getDdl</code></li>
<li><code dir="ltr" translate="no">spanner.databases.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">spanner.databases.list</code></li>
<li><code dir="ltr" translate="no">spanner.  databases.  partitionQuery</code></li>
<li><code dir="ltr" translate="no">spanner.  databases.  partitionRead</code></li>
<li><code dir="ltr" translate="no">spanner.databases.read</code></li>
<li><code dir="ltr" translate="no">spanner.  databases.  runGraphAlgorithms</code></li>
<li><code dir="ltr" translate="no">spanner.databases.select</code></li>
<li><code dir="ltr" translate="no">spanner.databases.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">spanner.databases.update</code></li>
<li><code dir="ltr" translate="no">spanner.databases.updateDdl</code></li>
<li><code dir="ltr" translate="no">spanner.databases.useDataBoost</code></li>
<li><code dir="ltr" translate="no">spanner.  databases.  useRoleBasedAccess</code></li>
<li><code dir="ltr" translate="no">spanner.databases.write</code></li>
<li><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  delete</code></li>
<li><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  get</code></li>
<li><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  list</code></li>
<li><code dir="ltr" translate="no">spanner.instanceConfigs.create</code></li>
<li><code dir="ltr" translate="no">spanner.instanceConfigs.delete</code></li>
<li><code dir="ltr" translate="no">spanner.instanceConfigs.get</code></li>
<li><code dir="ltr" translate="no">spanner.instanceConfigs.list</code></li>
<li><code dir="ltr" translate="no">spanner.instanceConfigs.update</code></li>
<li><code dir="ltr" translate="no">spanner.  instanceOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.  instanceOperations.  delete</code></li>
<li><code dir="ltr" translate="no">spanner.instanceOperations.get</code></li>
<li><code dir="ltr" translate="no">spanner.  instanceOperations.  list</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  delete</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  get</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  list</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitions.  create</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitions.  delete</code></li>
<li><code dir="ltr" translate="no">spanner.instancePartitions.get</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitions.  list</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitions.  update</code></li>
<li><code dir="ltr" translate="no">spanner.instances.create</code></li>
<li><code dir="ltr" translate="no">spanner.  instances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">spanner.instances.delete</code></li>
<li><code dir="ltr" translate="no">spanner.  instances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">spanner.instances.get</code></li>
<li><code dir="ltr" translate="no">spanner.instances.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">spanner.instances.list</code></li>
<li><code dir="ltr" translate="no">spanner.  instances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">spanner.  instances.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">spanner.instances.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">spanner.instances.update</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.create</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.delete</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.get</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.editor" class="role-title add-link" data-text="Cloud Spanner Editor" tabindex="-1">Cloud Spanner Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p>Editor role for Cloud Spanner</p></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">spanner.backupOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.  backupOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.backupOperations.get</code></li>
<li><code dir="ltr" translate="no">spanner.backupOperations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">spanner.backupSchedules.create</code></p>
<p><code dir="ltr" translate="no">spanner.backupSchedules.delete</code></p>
<p><code dir="ltr" translate="no">spanner.backupSchedules.get</code></p>
<p><code dir="ltr" translate="no">spanner.  backupSchedules.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.backupSchedules.list</code></p>
<p><code dir="ltr" translate="no">spanner.backupSchedules.update</code></p>
<p><code dir="ltr" translate="no">spanner.backups.copy</code></p>
<p><code dir="ltr" translate="no">spanner.backups.create</code></p>
<p><code dir="ltr" translate="no">spanner.backups.delete</code></p>
<p><code dir="ltr" translate="no">spanner.backups.get</code></p>
<p><code dir="ltr" translate="no">spanner.backups.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.backups.list</code></p>
<p><code dir="ltr" translate="no">spanner.  backups.  restoreDatabase</code></p>
<p><code dir="ltr" translate="no">spanner.backups.update</code></p>
<p><code dir="ltr" translate="no">spanner.databaseOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.  databaseOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.databaseOperations.get</code></li>
<li><code dir="ltr" translate="no">spanner.  databaseOperations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">spanner.databaseRoles.list</code></p>
<p><code dir="ltr" translate="no">spanner.databases.adapt</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  addSplitPoints</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginOrRollbackReadWriteTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginPartitionedDmlTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginReadOnlyTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.databases.changequorum</code></p>
<p><code dir="ltr" translate="no">spanner.databases.create</code></p>
<p><code dir="ltr" translate="no">spanner.databases.createBackup</code></p>
<p><code dir="ltr" translate="no">spanner.databases.drop</code></p>
<p><code dir="ltr" translate="no">spanner.databases.get</code></p>
<p><code dir="ltr" translate="no">spanner.databases.getDdl</code></p>
<p><code dir="ltr" translate="no">spanner.databases.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.databases.list</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionQuery</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionRead</code></p>
<p><code dir="ltr" translate="no">spanner.databases.read</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  runGraphAlgorithms</code></p>
<p><code dir="ltr" translate="no">spanner.databases.select</code></p>
<p><code dir="ltr" translate="no">spanner.databases.update</code></p>
<p><code dir="ltr" translate="no">spanner.databases.updateDdl</code></p>
<p><code dir="ltr" translate="no">spanner.databases.useDataBoost</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  useRoleBasedAccess</code></p>
<p><code dir="ltr" translate="no">spanner.databases.write</code></p>
<p><code dir="ltr" translate="no">spanner.  instanceConfigOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  delete</code></li>
<li><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  get</code></li>
<li><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">spanner.instanceConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.instanceConfigs.create</code></li>
<li><code dir="ltr" translate="no">spanner.instanceConfigs.delete</code></li>
<li><code dir="ltr" translate="no">spanner.instanceConfigs.get</code></li>
<li><code dir="ltr" translate="no">spanner.instanceConfigs.list</code></li>
<li><code dir="ltr" translate="no">spanner.instanceConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">spanner.instanceOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.  instanceOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.  instanceOperations.  delete</code></li>
<li><code dir="ltr" translate="no">spanner.instanceOperations.get</code></li>
<li><code dir="ltr" translate="no">spanner.  instanceOperations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">spanner.  instancePartitionOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  delete</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  get</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">spanner.instancePartitions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.  instancePartitions.  create</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitions.  delete</code></li>
<li><code dir="ltr" translate="no">spanner.instancePartitions.get</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitions.  list</code></li>
<li><code dir="ltr" translate="no">spanner.  instancePartitions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">spanner.instances.create</code></p>
<p><code dir="ltr" translate="no">spanner.instances.delete</code></p>
<p><code dir="ltr" translate="no">spanner.instances.get</code></p>
<p><code dir="ltr" translate="no">spanner.instances.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.instances.list</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">spanner.instances.update</code></p>
<p><code dir="ltr" translate="no">spanner.sessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.sessions.create</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.delete</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.get</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.viewer" class="role-title add-link" data-text="Cloud Spanner Viewer" tabindex="-1">Cloud Spanner Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.viewer</code> )</p>
<p>A principal with this role can:</p>
<ul>
<li>View all Spanner instances (but cannot modify instances).</li>
<li>View all Spanner databases (but cannot modify or read from databases).</li>
</ul>
<p>For example, you can combine this role with the <code dir="ltr" translate="no">roles/spanner.databaseUser</code> role to grant a user with access to a specific database, but only view access to other instances and databases.</p>
<p>This role is recommended at the Google Cloud project level for users interacting with Cloud Spanner resources in the Google Cloud console.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Instance</li>
<li>Database</li>
</ul></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">spanner.databases.get</code></p>
<p><code dir="ltr" translate="no">spanner.databases.list</code></p>
<p><code dir="ltr" translate="no">spanner.instanceConfigs.get</code></p>
<p><code dir="ltr" translate="no">spanner.instanceConfigs.list</code></p>
<p><code dir="ltr" translate="no">spanner.instancePartitions.get</code></p>
<p><code dir="ltr" translate="no">spanner.  instancePartitions.  list</code></p>
<p><code dir="ltr" translate="no">spanner.instances.get</code></p>
<p><code dir="ltr" translate="no">spanner.instances.list</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listTagBindings</code></p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.backupAdmin" class="role-title add-link" data-text="Cloud Spanner Backup Admin" tabindex="-1">Cloud Spanner Backup Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p>A principal with this role can:</p>
<ul>
<li>Create, view, update, and delete backups.</li>
<li>View and manage a backup's allow policy.</li>
</ul>
<p>This role cannot restore a database from a backup.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Instance</li>
<li>Database</li>
</ul></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">spanner.backupOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.  backupOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.backupOperations.get</code></li>
<li><code dir="ltr" translate="no">spanner.backupOperations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">spanner.backupSchedules.create</code></p>
<p><code dir="ltr" translate="no">spanner.backupSchedules.delete</code></p>
<p><code dir="ltr" translate="no">spanner.backupSchedules.get</code></p>
<p><code dir="ltr" translate="no">spanner.backupSchedules.list</code></p>
<p><code dir="ltr" translate="no">spanner.backupSchedules.update</code></p>
<p><code dir="ltr" translate="no">spanner.backups.copy</code></p>
<p><code dir="ltr" translate="no">spanner.backups.create</code></p>
<p><code dir="ltr" translate="no">spanner.backups.delete</code></p>
<p><code dir="ltr" translate="no">spanner.backups.get</code></p>
<p><code dir="ltr" translate="no">spanner.backups.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.backups.list</code></p>
<p><code dir="ltr" translate="no">spanner.backups.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.backups.update</code></p>
<p><code dir="ltr" translate="no">spanner.databases.createBackup</code></p>
<p><code dir="ltr" translate="no">spanner.databases.get</code></p>
<p><code dir="ltr" translate="no">spanner.databases.list</code></p>
<p><code dir="ltr" translate="no">spanner.instancePartitions.get</code></p>
<p><code dir="ltr" translate="no">spanner.  instancePartitions.  list</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">spanner.instances.get</code></p>
<p><code dir="ltr" translate="no">spanner.instances.list</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listTagBindings</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.backupWriter" class="role-title add-link" data-text="Cloud Spanner Backup Writer" tabindex="-1">Cloud Spanner Backup Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p>
<p>This role is intended to be used by scripts that automate backup creation. A principal with this role can create backups, but cannot update or delete them.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Instance</li>
<li>Database</li>
</ul></td>
<td><p><code dir="ltr" translate="no">spanner.backupOperations.get</code></p>
<p><code dir="ltr" translate="no">spanner.backupOperations.list</code></p>
<p><code dir="ltr" translate="no">spanner.backupSchedules.create</code></p>
<p><code dir="ltr" translate="no">spanner.backupSchedules.get</code></p>
<p><code dir="ltr" translate="no">spanner.backupSchedules.list</code></p>
<p><code dir="ltr" translate="no">spanner.backups.copy</code></p>
<p><code dir="ltr" translate="no">spanner.backups.create</code></p>
<p><code dir="ltr" translate="no">spanner.backups.get</code></p>
<p><code dir="ltr" translate="no">spanner.backups.list</code></p>
<p><code dir="ltr" translate="no">spanner.databases.createBackup</code></p>
<p><code dir="ltr" translate="no">spanner.databases.get</code></p>
<p><code dir="ltr" translate="no">spanner.databases.list</code></p>
<p><code dir="ltr" translate="no">spanner.instancePartitions.get</code></p>
<p><code dir="ltr" translate="no">spanner.instances.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databaseAdmin" class="role-title add-link" data-text="Cloud Spanner Database Admin" tabindex="-1">Cloud Spanner Database Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p>A principal with this role can:</p>
<ul>
<li>Get/list all Spanner instances in the project.</li>
<li>Create/list/drop databases in an instance.</li>
<li>Grant/revoke access to databases in the project.</li>
<li>Read from and write to all Cloud Spanner databases in the project.</li>
</ul>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Instance</li>
<li>Database</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.timeSeries.create</code></li>
<li><code dir="ltr" translate="no">monitoring.timeSeries.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">spanner.databaseOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.  databaseOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.databaseOperations.get</code></li>
<li><code dir="ltr" translate="no">spanner.  databaseOperations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">spanner.databaseRoles.list</code></p>
<p><code dir="ltr" translate="no">spanner.databases.adapt</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  addSplitPoints</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginOrRollbackReadWriteTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginPartitionedDmlTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginReadOnlyTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.databases.changequorum</code></p>
<p><code dir="ltr" translate="no">spanner.databases.create</code></p>
<p><code dir="ltr" translate="no">spanner.databases.drop</code></p>
<p><code dir="ltr" translate="no">spanner.databases.get</code></p>
<p><code dir="ltr" translate="no">spanner.databases.getDdl</code></p>
<p><code dir="ltr" translate="no">spanner.databases.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.databases.list</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionQuery</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionRead</code></p>
<p><code dir="ltr" translate="no">spanner.databases.read</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  runGraphAlgorithms</code></p>
<p><code dir="ltr" translate="no">spanner.databases.select</code></p>
<p><code dir="ltr" translate="no">spanner.databases.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.databases.update</code></p>
<p><code dir="ltr" translate="no">spanner.databases.updateDdl</code></p>
<p><code dir="ltr" translate="no">spanner.databases.useDataBoost</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  useRoleBasedAccess</code></p>
<p><code dir="ltr" translate="no">spanner.databases.write</code></p>
<p><code dir="ltr" translate="no">spanner.instancePartitions.get</code></p>
<p><code dir="ltr" translate="no">spanner.  instancePartitions.  list</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">spanner.instances.get</code></p>
<p><code dir="ltr" translate="no">spanner.instances.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">spanner.instances.list</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">spanner.sessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.sessions.create</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.delete</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.get</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databaseReader" class="role-title add-link" data-text="Cloud Spanner Database Reader" tabindex="-1">Cloud Spanner Database Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p>A principal with this role can:</p>
<ul>
<li>Read from the Spanner database.</li>
<li>Execute SQL queries on the database.</li>
<li>View schema for the database.</li>
</ul>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Instance</li>
<li>Database</li>
</ul></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginReadOnlyTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.databases.get</code></p>
<p><code dir="ltr" translate="no">spanner.databases.getDdl</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionQuery</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionRead</code></p>
<p><code dir="ltr" translate="no">spanner.databases.read</code></p>
<p><code dir="ltr" translate="no">spanner.databases.select</code></p>
<p><code dir="ltr" translate="no">spanner.instancePartitions.get</code></p>
<p><code dir="ltr" translate="no">spanner.instances.get</code></p>
<p><code dir="ltr" translate="no">spanner.sessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.sessions.create</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.delete</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.get</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databaseReaderWithDataBoost" class="role-title add-link" data-text="Cloud Spanner Database Reader with DataBoost" tabindex="-1">Cloud Spanner Database Reader with DataBoost</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p>Includes all permissions in the spanner.databaseReader role enabling access to read and/or query a Cloud Spanner database using instance resources, as well as the permission to access the database with Data Boost, a fully managed serverless service that provides independent compute resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Instance</li>
<li>Database</li>
</ul></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginReadOnlyTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.databases.get</code></p>
<p><code dir="ltr" translate="no">spanner.databases.getDdl</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionQuery</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionRead</code></p>
<p><code dir="ltr" translate="no">spanner.databases.read</code></p>
<p><code dir="ltr" translate="no">spanner.databases.select</code></p>
<p><code dir="ltr" translate="no">spanner.databases.useDataBoost</code></p>
<p><code dir="ltr" translate="no">spanner.instancePartitions.get</code></p>
<p><code dir="ltr" translate="no">spanner.instances.get</code></p>
<p><code dir="ltr" translate="no">spanner.sessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.sessions.create</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.delete</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.get</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databaseRoleUser" class="role-title add-link" data-text="Cloud Spanner Database Role User" tabindex="-1">Cloud Spanner Database Role User</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.databaseRoleUser</code> )</p>
<p>In conjunction with the IAM role Cloud Spanner Fine-grained Access User, grants permissions to individual Spanner database roles. Add a condition for each desired Spanner database role that includes the resource type of `spanner.googleapis.com/DatabaseRole` and the resource name ending with `/YOUR_SPANNER_DATABASE_ROLE`.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Instance</li>
<li>Database</li>
</ul></td>
<td></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databaseUser" class="role-title add-link" data-text="Cloud Spanner Database User" tabindex="-1">Cloud Spanner Database User</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p>A principal with this role can:</p>
<ul>
<li>Read from and write to the Spanner database.</li>
<li>Execute SQL queries on the database, including DML and Partitioned DML.</li>
<li>View and update schema for the database.</li>
</ul>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Instance</li>
<li>Database</li>
</ul></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">spanner.databaseOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.  databaseOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.databaseOperations.get</code></li>
<li><code dir="ltr" translate="no">spanner.  databaseOperations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">spanner.databases.adapt</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginOrRollbackReadWriteTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginPartitionedDmlTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginReadOnlyTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.databases.changequorum</code></p>
<p><code dir="ltr" translate="no">spanner.databases.get</code></p>
<p><code dir="ltr" translate="no">spanner.databases.getDdl</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionQuery</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionRead</code></p>
<p><code dir="ltr" translate="no">spanner.databases.read</code></p>
<p><code dir="ltr" translate="no">spanner.databases.select</code></p>
<p><code dir="ltr" translate="no">spanner.databases.updateDdl</code></p>
<p><code dir="ltr" translate="no">spanner.databases.write</code></p>
<p><code dir="ltr" translate="no">spanner.instancePartitions.get</code></p>
<p><code dir="ltr" translate="no">spanner.instances.get</code></p>
<p><code dir="ltr" translate="no">spanner.sessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.sessions.create</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.delete</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.get</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.fineGrainedAccessUser" class="role-title add-link" data-text="Cloud Spanner Fine-grained Access User" tabindex="-1">Cloud Spanner Fine-grained Access User</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.fineGrainedAccessUser</code> )</p>
<p>Grants permissions to use Spanner's fine-grained access control framework. To grant access to specific database roles, also add the `roles/spanner.databaseRoleUser` IAM role and its necessary conditions.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Instance</li>
<li>Database</li>
</ul></td>
<td><p><code dir="ltr" translate="no">spanner.databaseRoles.list</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  useRoleBasedAccess</code></p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.graphIntelligenceUser" class="role-title add-link" data-text="Cloud Spanner Database Graph Intelligence features user" tabindex="-1">Cloud Spanner Database Graph Intelligence features user</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p>Access to Graph Intelligence features.</p></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginReadOnlyTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.databases.get</code></p>
<p><code dir="ltr" translate="no">spanner.databases.getDdl</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionQuery</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionRead</code></p>
<p><code dir="ltr" translate="no">spanner.databases.read</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  runGraphAlgorithms</code></p>
<p><code dir="ltr" translate="no">spanner.databases.select</code></p>
<p><code dir="ltr" translate="no">spanner.databases.useDataBoost</code></p>
<p><code dir="ltr" translate="no">spanner.instancePartitions.get</code></p>
<p><code dir="ltr" translate="no">spanner.instances.get</code></p>
<p><code dir="ltr" translate="no">spanner.sessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.sessions.create</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.delete</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.get</code></li>
<li><code dir="ltr" translate="no">spanner.sessions.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.restoreAdmin" class="role-title add-link" data-text="Cloud Spanner Restore Admin" tabindex="-1">Cloud Spanner Restore Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p>A principal with this role can restore databases from backups.</p>
<p>If you need to restore a backup to a different instance, apply this role at the project level or to both instances. This role cannot create backups.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Instance</li>
<li>Database</li>
</ul></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">spanner.backups.get</code></p>
<p><code dir="ltr" translate="no">spanner.backups.list</code></p>
<p><code dir="ltr" translate="no">spanner.  backups.  restoreDatabase</code></p>
<p><code dir="ltr" translate="no">spanner.databaseOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">spanner.  databaseOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">spanner.databaseOperations.get</code></li>
<li><code dir="ltr" translate="no">spanner.  databaseOperations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">spanner.databases.create</code></p>
<p><code dir="ltr" translate="no">spanner.databases.get</code></p>
<p><code dir="ltr" translate="no">spanner.databases.list</code></p>
<p><code dir="ltr" translate="no">spanner.instancePartitions.get</code></p>
<p><code dir="ltr" translate="no">spanner.  instancePartitions.  list</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">spanner.instances.get</code></p>
<p><code dir="ltr" translate="no">spanner.instances.list</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listTagBindings</code></p></td>
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
<td><h4 id="spanner.serviceAgent" class="role-title add-link" data-text="Cloud Spanner API Service Agent" tabindex="-1">Cloud Spanner API Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</p>
<p>Cloud Spanner API Service Agent</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">aiplatform.endpoints.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.predict</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.list</code></p>
<p><code dir="ltr" translate="no">compute.disks.create</code></p>
<p><code dir="ltr" translate="no">compute.disks.createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.disks.use</code></p>
<p><code dir="ltr" translate="no">compute.instances.create</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.instances.delete</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.instances.setMetadata</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  setServiceAccount</code></p>
<p><code dir="ltr" translate="no">compute.networks.create</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.networks.useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.create</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">run.jobs.run</code></p>
<p><code dir="ltr" translate="no">run.routes.invoke</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginOrRollbackReadWriteTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginReadOnlyTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionQuery</code></p>
<p><code dir="ltr" translate="no">spanner.databases.select</code></p>
<p><code dir="ltr" translate="no">spanner.databases.useDataBoost</code></p>
<p><code dir="ltr" translate="no">spanner.databases.write</code></p>
<p><code dir="ltr" translate="no">spanner.sessions.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Spanner permissions

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
<td><h4 id="spanner.backupOperations.cancel" class="permission-name add-link" data-text="spanner.backupOperations.cancel" tabindex="-1"><code dir="ltr" translate="no">spanner.  backupOperations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.backupOperations.get" class="permission-name add-link" data-text="spanner.backupOperations.get" tabindex="-1"><code dir="ltr" translate="no">spanner.backupOperations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.backupOperations.list" class="permission-name add-link" data-text="spanner.backupOperations.list" tabindex="-1"><code dir="ltr" translate="no">spanner.backupOperations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.backupSchedules.create" class="permission-name add-link" data-text="spanner.backupSchedules.create" tabindex="-1"><code dir="ltr" translate="no">spanner.backupSchedules.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.backupSchedules.delete" class="permission-name add-link" data-text="spanner.backupSchedules.delete" tabindex="-1"><code dir="ltr" translate="no">spanner.backupSchedules.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.backupSchedules.get" class="permission-name add-link" data-text="spanner.backupSchedules.get" tabindex="-1"><code dir="ltr" translate="no">spanner.backupSchedules.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.backupSchedules.getIamPolicy" class="permission-name add-link" data-text="spanner.backupSchedules.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">spanner.  backupSchedules.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.backupSchedules.list" class="permission-name add-link" data-text="spanner.backupSchedules.list" tabindex="-1"><code dir="ltr" translate="no">spanner.backupSchedules.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.backupSchedules.setIamPolicy" class="permission-name add-link" data-text="spanner.backupSchedules.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">spanner.  backupSchedules.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.backupSchedules.update" class="permission-name add-link" data-text="spanner.backupSchedules.update" tabindex="-1"><code dir="ltr" translate="no">spanner.backupSchedules.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.backups.copy" class="permission-name add-link" data-text="spanner.backups.copy" tabindex="-1"><code dir="ltr" translate="no">spanner.backups.copy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.backups.create" class="permission-name add-link" data-text="spanner.backups.create" tabindex="-1"><code dir="ltr" translate="no">spanner.backups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.backups.delete" class="permission-name add-link" data-text="spanner.backups.delete" tabindex="-1"><code dir="ltr" translate="no">spanner.backups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.backups.get" class="permission-name add-link" data-text="spanner.backups.get" tabindex="-1"><code dir="ltr" translate="no">spanner.backups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.backups.getIamPolicy" class="permission-name add-link" data-text="spanner.backups.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">spanner.backups.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.backups.list" class="permission-name add-link" data-text="spanner.backups.list" tabindex="-1"><code dir="ltr" translate="no">spanner.backups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.backups.restoreDatabase" class="permission-name add-link" data-text="spanner.backups.restoreDatabase" tabindex="-1"><code dir="ltr" translate="no">spanner.  backups.  restoreDatabase</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.backups.setIamPolicy" class="permission-name add-link" data-text="spanner.backups.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">spanner.backups.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.backups.update" class="permission-name add-link" data-text="spanner.backups.update" tabindex="-1"><code dir="ltr" translate="no">spanner.backups.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databaseOperations.cancel" class="permission-name add-link" data-text="spanner.databaseOperations.cancel" tabindex="-1"><code dir="ltr" translate="no">spanner.  databaseOperations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databaseOperations.get" class="permission-name add-link" data-text="spanner.databaseOperations.get" tabindex="-1"><code dir="ltr" translate="no">spanner.databaseOperations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databaseOperations.list" class="permission-name add-link" data-text="spanner.databaseOperations.list" tabindex="-1"><code dir="ltr" translate="no">spanner.  databaseOperations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databaseRoles.list" class="permission-name add-link" data-text="spanner.databaseRoles.list" tabindex="-1"><code dir="ltr" translate="no">spanner.databaseRoles.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.fineGrainedAccessUser">Cloud Spanner Fine-grained Access User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.fineGrainedAccessUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databases.adapt" class="permission-name add-link" data-text="spanner.databases.adapt" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.adapt</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databases.addSplitPoints" class="permission-name add-link" data-text="spanner.databases.addSplitPoints" tabindex="-1"><code dir="ltr" translate="no">spanner.  databases.  addSplitPoints</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databases.beginOrRollbackReadWriteTransaction" class="permission-name add-link" data-text="spanner.databases.beginOrRollbackReadWriteTransaction" tabindex="-1"><code dir="ltr" translate="no">spanner.  databases.  beginOrRollbackReadWriteTransaction</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databases.beginPartitionedDmlTransaction" class="permission-name add-link" data-text="spanner.databases.beginPartitionedDmlTransaction" tabindex="-1"><code dir="ltr" translate="no">spanner.  databases.  beginPartitionedDmlTransaction</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databases.beginReadOnlyTransaction" class="permission-name add-link" data-text="spanner.databases.beginReadOnlyTransaction" tabindex="-1"><code dir="ltr" translate="no">spanner.  databases.  beginReadOnlyTransaction</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databases.changequorum" class="permission-name add-link" data-text="spanner.databases.changequorum" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.changequorum</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databases.create" class="permission-name add-link" data-text="spanner.databases.create" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databases.createBackup" class="permission-name add-link" data-text="spanner.databases.createBackup" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.createBackup</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databases.drop" class="permission-name add-link" data-text="spanner.databases.drop" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.drop</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databases.get" class="permission-name add-link" data-text="spanner.databases.get" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databases.getDdl" class="permission-name add-link" data-text="spanner.databases.getDdl" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.getDdl</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databases.getIamPolicy" class="permission-name add-link" data-text="spanner.databases.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databases.list" class="permission-name add-link" data-text="spanner.databases.list" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databases.partitionQuery" class="permission-name add-link" data-text="spanner.databases.partitionQuery" tabindex="-1"><code dir="ltr" translate="no">spanner.  databases.  partitionQuery</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databases.partitionRead" class="permission-name add-link" data-text="spanner.databases.partitionRead" tabindex="-1"><code dir="ltr" translate="no">spanner.  databases.  partitionRead</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databases.read" class="permission-name add-link" data-text="spanner.databases.read" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.read</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databases.runGraphAlgorithms" class="permission-name add-link" data-text="spanner.databases.runGraphAlgorithms" tabindex="-1"><code dir="ltr" translate="no">spanner.  databases.  runGraphAlgorithms</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databases.select" class="permission-name add-link" data-text="spanner.databases.select" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.select</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databases.setIamPolicy" class="permission-name add-link" data-text="spanner.databases.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databases.update" class="permission-name add-link" data-text="spanner.databases.update" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databases.updateDdl" class="permission-name add-link" data-text="spanner.databases.updateDdl" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.updateDdl</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databases.useDataBoost" class="permission-name add-link" data-text="spanner.databases.useDataBoost" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.useDataBoost</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.databases.useRoleBasedAccess" class="permission-name add-link" data-text="spanner.databases.useRoleBasedAccess" tabindex="-1"><code dir="ltr" translate="no">spanner.  databases.  useRoleBasedAccess</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.fineGrainedAccessUser">Cloud Spanner Fine-grained Access User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.fineGrainedAccessUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.databases.write" class="permission-name add-link" data-text="spanner.databases.write" tabindex="-1"><code dir="ltr" translate="no">spanner.databases.write</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instanceConfigOperations.cancel" class="permission-name add-link" data-text="spanner.instanceConfigOperations.cancel" tabindex="-1"><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instanceConfigOperations.delete" class="permission-name add-link" data-text="spanner.instanceConfigOperations.delete" tabindex="-1"><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instanceConfigOperations.get" class="permission-name add-link" data-text="spanner.instanceConfigOperations.get" tabindex="-1"><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instanceConfigOperations.list" class="permission-name add-link" data-text="spanner.instanceConfigOperations.list" tabindex="-1"><code dir="ltr" translate="no">spanner.  instanceConfigOperations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instanceConfigs.create" class="permission-name add-link" data-text="spanner.instanceConfigs.create" tabindex="-1"><code dir="ltr" translate="no">spanner.instanceConfigs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instanceConfigs.delete" class="permission-name add-link" data-text="spanner.instanceConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">spanner.instanceConfigs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instanceConfigs.get" class="permission-name add-link" data-text="spanner.instanceConfigs.get" tabindex="-1"><code dir="ltr" translate="no">spanner.instanceConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instanceConfigs.list" class="permission-name add-link" data-text="spanner.instanceConfigs.list" tabindex="-1"><code dir="ltr" translate="no">spanner.instanceConfigs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instanceConfigs.update" class="permission-name add-link" data-text="spanner.instanceConfigs.update" tabindex="-1"><code dir="ltr" translate="no">spanner.instanceConfigs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instanceOperations.cancel" class="permission-name add-link" data-text="spanner.instanceOperations.cancel" tabindex="-1"><code dir="ltr" translate="no">spanner.  instanceOperations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instanceOperations.delete" class="permission-name add-link" data-text="spanner.instanceOperations.delete" tabindex="-1"><code dir="ltr" translate="no">spanner.  instanceOperations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instanceOperations.get" class="permission-name add-link" data-text="spanner.instanceOperations.get" tabindex="-1"><code dir="ltr" translate="no">spanner.instanceOperations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instanceOperations.list" class="permission-name add-link" data-text="spanner.instanceOperations.list" tabindex="-1"><code dir="ltr" translate="no">spanner.  instanceOperations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instancePartitionOperations.cancel" class="permission-name add-link" data-text="spanner.instancePartitionOperations.cancel" tabindex="-1"><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instancePartitionOperations.delete" class="permission-name add-link" data-text="spanner.instancePartitionOperations.delete" tabindex="-1"><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instancePartitionOperations.get" class="permission-name add-link" data-text="spanner.instancePartitionOperations.get" tabindex="-1"><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instancePartitionOperations.list" class="permission-name add-link" data-text="spanner.instancePartitionOperations.list" tabindex="-1"><code dir="ltr" translate="no">spanner.  instancePartitionOperations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instancePartitions.create" class="permission-name add-link" data-text="spanner.instancePartitions.create" tabindex="-1"><code dir="ltr" translate="no">spanner.  instancePartitions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instancePartitions.delete" class="permission-name add-link" data-text="spanner.instancePartitions.delete" tabindex="-1"><code dir="ltr" translate="no">spanner.  instancePartitions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instancePartitions.get" class="permission-name add-link" data-text="spanner.instancePartitions.get" tabindex="-1"><code dir="ltr" translate="no">spanner.instancePartitions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instancePartitions.list" class="permission-name add-link" data-text="spanner.instancePartitions.list" tabindex="-1"><code dir="ltr" translate="no">spanner.  instancePartitions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instancePartitions.update" class="permission-name add-link" data-text="spanner.instancePartitions.update" tabindex="-1"><code dir="ltr" translate="no">spanner.  instancePartitions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instances.create" class="permission-name add-link" data-text="spanner.instances.create" tabindex="-1"><code dir="ltr" translate="no">spanner.instances.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instances.createTagBinding" class="permission-name add-link" data-text="spanner.instances.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">spanner.  instances.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instances.delete" class="permission-name add-link" data-text="spanner.instances.delete" tabindex="-1"><code dir="ltr" translate="no">spanner.instances.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instances.deleteTagBinding" class="permission-name add-link" data-text="spanner.instances.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">spanner.  instances.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instances.get" class="permission-name add-link" data-text="spanner.instances.get" tabindex="-1"><code dir="ltr" translate="no">spanner.instances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupWriter">Cloud Spanner Backup Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instances.getIamPolicy" class="permission-name add-link" data-text="spanner.instances.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">spanner.instances.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instances.list" class="permission-name add-link" data-text="spanner.instances.list" tabindex="-1"><code dir="ltr" translate="no">spanner.instances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instances.listEffectiveTags" class="permission-name add-link" data-text="spanner.instances.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">spanner.  instances.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instances.listTagBindings" class="permission-name add-link" data-text="spanner.instances.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">spanner.  instances.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.restoreAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.instances.setIamPolicy" class="permission-name add-link" data-text="spanner.instances.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">spanner.instances.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="spanner.instances.update" class="permission-name add-link" data-text="spanner.instances.update" tabindex="-1"><code dir="ltr" translate="no">spanner.instances.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.sessions.create" class="permission-name add-link" data-text="spanner.sessions.create" tabindex="-1"><code dir="ltr" translate="no">spanner.sessions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.serviceAgent">Cloud Spanner API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.sessions.delete" class="permission-name add-link" data-text="spanner.sessions.delete" tabindex="-1"><code dir="ltr" translate="no">spanner.sessions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="spanner.sessions.get" class="permission-name add-link" data-text="spanner.sessions.get" tabindex="-1"><code dir="ltr" translate="no">spanner.sessions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="spanner.sessions.list" class="permission-name add-link" data-text="spanner.sessions.list" tabindex="-1"><code dir="ltr" translate="no">spanner.sessions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code class="role-name" dir="ltr" translate="no">roles/  spanner.graphIntelligenceUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
