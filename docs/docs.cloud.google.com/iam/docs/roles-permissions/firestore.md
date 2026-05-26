---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/firestore
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/firestore
title: Firestore roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firestore. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firestore roles

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
<td><h4 id="datastore.admin" class="role-title add-link" data-text="Cloud Datastore Admin" tabindex="-1">Cloud Datastore Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p>Admin role for Cloud Datastore</p></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></p>
<p><code dir="ltr" translate="no">datastore.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  create</code></li>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  delete</code></li>
<li><code dir="ltr" translate="no">datastore.backupSchedules.get</code></li>
<li><code dir="ltr" translate="no">datastore.backupSchedules.list</code></li>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  update</code></li>
<li><code dir="ltr" translate="no">datastore.backups.delete</code></li>
<li><code dir="ltr" translate="no">datastore.backups.get</code></li>
<li><code dir="ltr" translate="no">datastore.backups.list</code></li>
<li><code dir="ltr" translate="no">datastore.  backups.  restoreDatabase</code></li>
<li><code dir="ltr" translate="no">datastore.databases.bulkDelete</code></li>
<li><code dir="ltr" translate="no">datastore.databases.clone</code></li>
<li><code dir="ltr" translate="no">datastore.databases.create</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datastore.databases.delete</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datastore.databases.export</code></li>
<li><code dir="ltr" translate="no">datastore.databases.get</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></li>
<li><code dir="ltr" translate="no">datastore.databases.import</code></li>
<li><code dir="ltr" translate="no">datastore.databases.list</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">datastore.databases.update</code></li>
<li><code dir="ltr" translate="no">datastore.entities.allocateIds</code></li>
<li><code dir="ltr" translate="no">datastore.entities.create</code></li>
<li><code dir="ltr" translate="no">datastore.entities.delete</code></li>
<li><code dir="ltr" translate="no">datastore.entities.get</code></li>
<li><code dir="ltr" translate="no">datastore.entities.list</code></li>
<li><code dir="ltr" translate="no">datastore.entities.update</code></li>
<li><code dir="ltr" translate="no">datastore.insights.get</code></li>
<li><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  get</code></li>
<li><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  list</code></li>
<li><code dir="ltr" translate="no">datastore.locations.get</code></li>
<li><code dir="ltr" translate="no">datastore.locations.list</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.list</code></li>
<li><code dir="ltr" translate="no">datastore.operations.cancel</code></li>
<li><code dir="ltr" translate="no">datastore.operations.delete</code></li>
<li><code dir="ltr" translate="no">datastore.operations.get</code></li>
<li><code dir="ltr" translate="no">datastore.operations.list</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.create</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.delete</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.get</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.list</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.update</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.get</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.list</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.create</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.delete</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.get</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.list</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.editor" class="role-title add-link" data-text="Cloud Datastore Editor" tabindex="-1">Cloud Datastore Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p>Editor role for Cloud Datastore</p></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></p>
<p><code dir="ltr" translate="no">datastore.backupSchedules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  create</code></li>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  delete</code></li>
<li><code dir="ltr" translate="no">datastore.backupSchedules.get</code></li>
<li><code dir="ltr" translate="no">datastore.backupSchedules.list</code></li>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.backups.delete</code></p>
<p><code dir="ltr" translate="no">datastore.backups.get</code></p>
<p><code dir="ltr" translate="no">datastore.backups.list</code></p>
<p><code dir="ltr" translate="no">datastore.databases.get</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastore.databases.update</code></p>
<p><code dir="ltr" translate="no">datastore.entities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.entities.allocateIds</code></li>
<li><code dir="ltr" translate="no">datastore.entities.create</code></li>
<li><code dir="ltr" translate="no">datastore.entities.delete</code></li>
<li><code dir="ltr" translate="no">datastore.entities.get</code></li>
<li><code dir="ltr" translate="no">datastore.entities.list</code></li>
<li><code dir="ltr" translate="no">datastore.entities.update</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.insights.get</code></p>
<p><code dir="ltr" translate="no">datastore.keyVisualizerScans.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  get</code></li>
<li><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.operations.get</code></p>
<p><code dir="ltr" translate="no">datastore.operations.list</code></p>
<p><code dir="ltr" translate="no">datastore.schemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.schemas.create</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.delete</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.get</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.list</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.update</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.statistics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.statistics.get</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.userCreds.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.userCreds.create</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.delete</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.get</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.list</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.owner" class="role-title add-link" data-text="Cloud Datastore Owner" tabindex="-1">Cloud Datastore Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p>Provides full access to Datastore resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  create</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  delete</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  list</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  studioQueries.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  create</code></li>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  delete</code></li>
<li><code dir="ltr" translate="no">datastore.backupSchedules.get</code></li>
<li><code dir="ltr" translate="no">datastore.backupSchedules.list</code></li>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  update</code></li>
<li><code dir="ltr" translate="no">datastore.backups.delete</code></li>
<li><code dir="ltr" translate="no">datastore.backups.get</code></li>
<li><code dir="ltr" translate="no">datastore.backups.list</code></li>
<li><code dir="ltr" translate="no">datastore.  backups.  restoreDatabase</code></li>
<li><code dir="ltr" translate="no">datastore.databases.bulkDelete</code></li>
<li><code dir="ltr" translate="no">datastore.databases.clone</code></li>
<li><code dir="ltr" translate="no">datastore.databases.create</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datastore.databases.delete</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datastore.databases.export</code></li>
<li><code dir="ltr" translate="no">datastore.databases.get</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></li>
<li><code dir="ltr" translate="no">datastore.databases.import</code></li>
<li><code dir="ltr" translate="no">datastore.databases.list</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datastore.  databases.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">datastore.databases.update</code></li>
<li><code dir="ltr" translate="no">datastore.entities.allocateIds</code></li>
<li><code dir="ltr" translate="no">datastore.entities.create</code></li>
<li><code dir="ltr" translate="no">datastore.entities.delete</code></li>
<li><code dir="ltr" translate="no">datastore.entities.get</code></li>
<li><code dir="ltr" translate="no">datastore.entities.list</code></li>
<li><code dir="ltr" translate="no">datastore.entities.update</code></li>
<li><code dir="ltr" translate="no">datastore.insights.get</code></li>
<li><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  get</code></li>
<li><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  list</code></li>
<li><code dir="ltr" translate="no">datastore.locations.get</code></li>
<li><code dir="ltr" translate="no">datastore.locations.list</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.list</code></li>
<li><code dir="ltr" translate="no">datastore.operations.cancel</code></li>
<li><code dir="ltr" translate="no">datastore.operations.delete</code></li>
<li><code dir="ltr" translate="no">datastore.operations.get</code></li>
<li><code dir="ltr" translate="no">datastore.operations.list</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.create</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.delete</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.get</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.list</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.update</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.get</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.list</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.create</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.delete</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.get</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.list</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.user" class="role-title add-link" data-text="Cloud Datastore User" tabindex="-1">Cloud Datastore User</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p>Provides read/write access to data in a Datastore database.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  create</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  delete</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  update</code></p>
<p><code dir="ltr" translate="no">datastore.databases.get</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.entities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.entities.allocateIds</code></li>
<li><code dir="ltr" translate="no">datastore.entities.create</code></li>
<li><code dir="ltr" translate="no">datastore.entities.delete</code></li>
<li><code dir="ltr" translate="no">datastore.entities.get</code></li>
<li><code dir="ltr" translate="no">datastore.entities.list</code></li>
<li><code dir="ltr" translate="no">datastore.entities.update</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.schemas.list</code></p>
<p><code dir="ltr" translate="no">datastore.statistics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.statistics.get</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.viewer" class="role-title add-link" data-text="Cloud Datastore Viewer" tabindex="-1">Cloud Datastore Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p>Provides read access to Datastore resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></p>
<p><code dir="ltr" translate="no">datastore.databases.get</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.entities.get</code></p>
<p><code dir="ltr" translate="no">datastore.entities.list</code></p>
<p><code dir="ltr" translate="no">datastore.insights.get</code></p>
<p><code dir="ltr" translate="no">datastore.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.schemas.get</code></p>
<p><code dir="ltr" translate="no">datastore.schemas.list</code></p>
<p><code dir="ltr" translate="no">datastore.statistics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.statistics.get</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.backupSchedulesAdmin" class="role-title add-link" data-text="Cloud Datastore Backup Schedules Admin" tabindex="-1">Cloud Datastore Backup Schedules Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.backupSchedulesAdmin</code> )</p>
<p>Manage backup schedules in Cloud Datastore.</p></td>
<td><p><code dir="ltr" translate="no">datastore.backupSchedules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  create</code></li>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  delete</code></li>
<li><code dir="ltr" translate="no">datastore.backupSchedules.get</code></li>
<li><code dir="ltr" translate="no">datastore.backupSchedules.list</code></li>
<li><code dir="ltr" translate="no">datastore.  backupSchedules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.backupSchedulesViewer" class="role-title add-link" data-text="Cloud Datastore Backup Schedules Viewer" tabindex="-1">Cloud Datastore Backup Schedules Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.backupSchedulesViewer</code> )</p>
<p>Read access to backup schedules in Cloud Datastore.</p></td>
<td><p><code dir="ltr" translate="no">datastore.backupSchedules.get</code></p>
<p><code dir="ltr" translate="no">datastore.backupSchedules.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.backupsAdmin" class="role-title add-link" data-text="Cloud Datastore Backups Admin" tabindex="-1">Cloud Datastore Backups Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.backupsAdmin</code> )</p>
<p>Read/Write access to metadata about backups in Cloud Datastore but restore is not allowed.</p></td>
<td><p><code dir="ltr" translate="no">datastore.backups.delete</code></p>
<p><code dir="ltr" translate="no">datastore.backups.get</code></p>
<p><code dir="ltr" translate="no">datastore.backups.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.backupsViewer" class="role-title add-link" data-text="Cloud Datastore Backups Viewer" tabindex="-1">Cloud Datastore Backups Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.backupsViewer</code> )</p>
<p>Read access to metadata about backups in Cloud Datastore.</p></td>
<td><p><code dir="ltr" translate="no">datastore.backups.get</code></p>
<p><code dir="ltr" translate="no">datastore.backups.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.bulkAdmin" class="role-title add-link" data-text="Cloud Datastore Bulk Admin" tabindex="-1">Cloud Datastore Bulk Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.bulkAdmin</code> )</p>
<p>Full access to manage bulk operations.</p></td>
<td><p><code dir="ltr" translate="no">datastore.databases.bulkDelete</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.operations.cancel</code></p>
<p><code dir="ltr" translate="no">datastore.operations.get</code></p>
<p><code dir="ltr" translate="no">datastore.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.cloneAdmin" class="role-title add-link" data-text="Cloud Datastore Clone Admin" tabindex="-1">Cloud Datastore Clone Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.cloneAdmin</code> )</p>
<p>Clone Cloud Datastore Databases.</p></td>
<td><p><code dir="ltr" translate="no">datastore.databases.clone</code></p>
<p><code dir="ltr" translate="no">datastore.databases.create</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.operations.get</code></p>
<p><code dir="ltr" translate="no">datastore.operations.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.importExportAdmin" class="role-title add-link" data-text="Cloud Datastore Import Export Admin" tabindex="-1">Cloud Datastore Import Export Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.importExportAdmin</code> )</p>
<p>Provides full access to manage imports and exports.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">datastore.databases.export</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.import</code></p>
<p><code dir="ltr" translate="no">datastore.operations.cancel</code></p>
<p><code dir="ltr" translate="no">datastore.operations.get</code></p>
<p><code dir="ltr" translate="no">datastore.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.indexAdmin" class="role-title add-link" data-text="Cloud Datastore Index Admin" tabindex="-1">Cloud Datastore Index Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.indexAdmin</code> )</p>
<p>Provides full access to manage index definitions.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.operations.get</code></p>
<p><code dir="ltr" translate="no">datastore.operations.list</code></p>
<p><code dir="ltr" translate="no">datastore.schemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.schemas.create</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.delete</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.get</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.list</code></li>
<li><code dir="ltr" translate="no">datastore.schemas.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.keyVisualizerViewer" class="role-title add-link" data-text="Cloud Datastore Key Visualizer Viewer" tabindex="-1">Cloud Datastore Key Visualizer Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.keyVisualizerViewer</code> )</p>
<p>Full access to Key Visualizer scans.</p></td>
<td><p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.keyVisualizerScans.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  get</code></li>
<li><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.restoreAdmin" class="role-title add-link" data-text="Cloud Datastore Restore Admin" tabindex="-1">Cloud Datastore Restore Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.restoreAdmin</code> )</p>
<p>Restore into Cloud Datastore Databases from Cloud Datastore Backups.</p></td>
<td><p><code dir="ltr" translate="no">datastore.backups.get</code></p>
<p><code dir="ltr" translate="no">datastore.backups.list</code></p>
<p><code dir="ltr" translate="no">datastore.  backups.  restoreDatabase</code></p>
<p><code dir="ltr" translate="no">datastore.databases.create</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.operations.get</code></p>
<p><code dir="ltr" translate="no">datastore.operations.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.userCredsAdmin" class="role-title add-link" data-text="Cloud Datastore User Creds Admin" tabindex="-1">Cloud Datastore User Creds Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.userCredsAdmin</code> )</p>
<p>Manage user creds in Cloud Datastore.</p></td>
<td><p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.userCreds.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.userCreds.create</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.delete</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.get</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.list</code></li>
<li><code dir="ltr" translate="no">datastore.userCreds.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.userCredsViewer" class="role-title add-link" data-text="Cloud Datastore User Creds Viewer" tabindex="-1">Cloud Datastore User Creds Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  datastore.userCredsViewer</code> )</p>
<p>Read access to user creds in Cloud Datastore.</p></td>
<td><p><code dir="ltr" translate="no">datastore.userCreds.get</code></p>
<p><code dir="ltr" translate="no">datastore.userCreds.list</code></p></td>
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
<td><h4 id="firestore.serviceAgent" class="role-title add-link" data-text="Firestore Service Agent" tabindex="-1">Firestore Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  firestore.serviceAgent</code> )</p>
<p>Gives Firestore service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Firestore permissions

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
<td><h4 id="datastore.backupSchedules.create" class="permission-name add-link" data-text="datastore.backupSchedules.create" tabindex="-1"><code dir="ltr" translate="no">datastore.  backupSchedules.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupSchedulesAdmin">Cloud Datastore Backup Schedules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupSchedulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.backupSchedules.delete" class="permission-name add-link" data-text="datastore.backupSchedules.delete" tabindex="-1"><code dir="ltr" translate="no">datastore.  backupSchedules.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupSchedulesAdmin">Cloud Datastore Backup Schedules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupSchedulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.backupSchedules.get" class="permission-name add-link" data-text="datastore.backupSchedules.get" tabindex="-1"><code dir="ltr" translate="no">datastore.backupSchedules.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupSchedulesAdmin">Cloud Datastore Backup Schedules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupSchedulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupSchedulesViewer">Cloud Datastore Backup Schedules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupSchedulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.backupSchedules.list" class="permission-name add-link" data-text="datastore.backupSchedules.list" tabindex="-1"><code dir="ltr" translate="no">datastore.backupSchedules.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupSchedulesAdmin">Cloud Datastore Backup Schedules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupSchedulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupSchedulesViewer">Cloud Datastore Backup Schedules Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupSchedulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.backupSchedules.update" class="permission-name add-link" data-text="datastore.backupSchedules.update" tabindex="-1"><code dir="ltr" translate="no">datastore.  backupSchedules.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupSchedulesAdmin">Cloud Datastore Backup Schedules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupSchedulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.backups.delete" class="permission-name add-link" data-text="datastore.backups.delete" tabindex="-1"><code dir="ltr" translate="no">datastore.backups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupsAdmin">Cloud Datastore Backups Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.backups.get" class="permission-name add-link" data-text="datastore.backups.get" tabindex="-1"><code dir="ltr" translate="no">datastore.backups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupsAdmin">Cloud Datastore Backups Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupsViewer">Cloud Datastore Backups Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.restoreAdmin">Cloud Datastore Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.backups.list" class="permission-name add-link" data-text="datastore.backups.list" tabindex="-1"><code dir="ltr" translate="no">datastore.backups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupsAdmin">Cloud Datastore Backups Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupsViewer">Cloud Datastore Backups Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.restoreAdmin">Cloud Datastore Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.backups.restoreDatabase" class="permission-name add-link" data-text="datastore.backups.restoreDatabase" tabindex="-1"><code dir="ltr" translate="no">datastore.  backups.  restoreDatabase</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.restoreAdmin">Cloud Datastore Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.databases.bulkDelete" class="permission-name add-link" data-text="datastore.databases.bulkDelete" tabindex="-1"><code dir="ltr" translate="no">datastore.databases.bulkDelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.bulkAdmin">Cloud Datastore Bulk Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.bulkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.databases.clone" class="permission-name add-link" data-text="datastore.databases.clone" tabindex="-1"><code dir="ltr" translate="no">datastore.databases.clone</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.cloneAdmin">Cloud Datastore Clone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.cloneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.databases.create" class="permission-name add-link" data-text="datastore.databases.create" tabindex="-1"><code dir="ltr" translate="no">datastore.databases.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.cloneAdmin">Cloud Datastore Clone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.cloneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.restoreAdmin">Cloud Datastore Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.databases.createTagBinding" class="permission-name add-link" data-text="datastore.databases.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">datastore.  databases.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.databases.delete" class="permission-name add-link" data-text="datastore.databases.delete" tabindex="-1"><code dir="ltr" translate="no">datastore.databases.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.databases.deleteTagBinding" class="permission-name add-link" data-text="datastore.databases.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">datastore.  databases.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.databases.export" class="permission-name add-link" data-text="datastore.databases.export" tabindex="-1"><code dir="ltr" translate="no">datastore.databases.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.importExportAdmin">Cloud Datastore Import Export Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.importExportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.databases.get" class="permission-name add-link" data-text="datastore.databases.get" tabindex="-1"><code dir="ltr" translate="no">datastore.databases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datastore.databases.getMetadata" class="permission-name add-link" data-text="datastore.databases.getMetadata" tabindex="-1"><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupSchedulesAdmin">Cloud Datastore Backup Schedules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupSchedulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.bulkAdmin">Cloud Datastore Bulk Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.bulkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.cloneAdmin">Cloud Datastore Clone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.cloneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.importExportAdmin">Cloud Datastore Import Export Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.importExportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.keyVisualizerViewer">Cloud Datastore Key Visualizer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.keyVisualizerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.restoreAdmin">Cloud Datastore Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.userCredsAdmin">Cloud Datastore User Creds Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.userCredsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.databases.import" class="permission-name add-link" data-text="datastore.databases.import" tabindex="-1"><code dir="ltr" translate="no">datastore.databases.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.importExportAdmin">Cloud Datastore Import Export Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.importExportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.databases.list" class="permission-name add-link" data-text="datastore.databases.list" tabindex="-1"><code dir="ltr" translate="no">datastore.databases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.backupSchedulesAdmin">Cloud Datastore Backup Schedules Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.backupSchedulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.cloneAdmin">Cloud Datastore Clone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.cloneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.restoreAdmin">Cloud Datastore Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.userCredsAdmin">Cloud Datastore User Creds Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.userCredsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.databases.listEffectiveTags" class="permission-name add-link" data-text="datastore.databases.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">datastore.  databases.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.databases.listTagBindings" class="permission-name add-link" data-text="datastore.databases.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">datastore.  databases.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.databases.update" class="permission-name add-link" data-text="datastore.databases.update" tabindex="-1"><code dir="ltr" translate="no">datastore.databases.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datastore.entities.allocateIds" class="permission-name add-link" data-text="datastore.entities.allocateIds" tabindex="-1"><code dir="ltr" translate="no">datastore.entities.allocateIds</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.entities.create" class="permission-name add-link" data-text="datastore.entities.create" tabindex="-1"><code dir="ltr" translate="no">datastore.entities.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datastore.entities.delete" class="permission-name add-link" data-text="datastore.entities.delete" tabindex="-1"><code dir="ltr" translate="no">datastore.entities.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.entities.get" class="permission-name add-link" data-text="datastore.entities.get" tabindex="-1"><code dir="ltr" translate="no">datastore.entities.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.firestoreServiceAgent">Firebase Rules Firestore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.firestoreServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datastore.entities.list" class="permission-name add-link" data-text="datastore.entities.list" tabindex="-1"><code dir="ltr" translate="no">datastore.entities.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.entities.update" class="permission-name add-link" data-text="datastore.entities.update" tabindex="-1"><code dir="ltr" translate="no">datastore.entities.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datastore.insights.get" class="permission-name add-link" data-text="datastore.insights.get" tabindex="-1"><code dir="ltr" translate="no">datastore.insights.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.keyVisualizerScans.get" class="permission-name add-link" data-text="datastore.keyVisualizerScans.get" tabindex="-1"><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.keyVisualizerViewer">Cloud Datastore Key Visualizer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.keyVisualizerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.keyVisualizerScans.list" class="permission-name add-link" data-text="datastore.keyVisualizerScans.list" tabindex="-1"><code dir="ltr" translate="no">datastore.  keyVisualizerScans.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.keyVisualizerViewer">Cloud Datastore Key Visualizer Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.keyVisualizerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.locations.get" class="permission-name add-link" data-text="datastore.locations.get" tabindex="-1"><code dir="ltr" translate="no">datastore.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datastore.locations.list" class="permission-name add-link" data-text="datastore.locations.list" tabindex="-1"><code dir="ltr" translate="no">datastore.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.namespaces.get" class="permission-name add-link" data-text="datastore.namespaces.get" tabindex="-1"><code dir="ltr" translate="no">datastore.namespaces.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datastore.namespaces.list" class="permission-name add-link" data-text="datastore.namespaces.list" tabindex="-1"><code dir="ltr" translate="no">datastore.namespaces.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.operations.cancel" class="permission-name add-link" data-text="datastore.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">datastore.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.bulkAdmin">Cloud Datastore Bulk Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.bulkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.importExportAdmin">Cloud Datastore Import Export Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.importExportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.operations.delete" class="permission-name add-link" data-text="datastore.operations.delete" tabindex="-1"><code dir="ltr" translate="no">datastore.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.operations.get" class="permission-name add-link" data-text="datastore.operations.get" tabindex="-1"><code dir="ltr" translate="no">datastore.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.bulkAdmin">Cloud Datastore Bulk Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.bulkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.cloneAdmin">Cloud Datastore Clone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.cloneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.importExportAdmin">Cloud Datastore Import Export Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.importExportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.restoreAdmin">Cloud Datastore Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datastore.operations.list" class="permission-name add-link" data-text="datastore.operations.list" tabindex="-1"><code dir="ltr" translate="no">datastore.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.bulkAdmin">Cloud Datastore Bulk Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.bulkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.cloneAdmin">Cloud Datastore Clone Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.cloneAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.importExportAdmin">Cloud Datastore Import Export Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.importExportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.restoreAdmin">Cloud Datastore Restore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.schemas.create" class="permission-name add-link" data-text="datastore.schemas.create" tabindex="-1"><code dir="ltr" translate="no">datastore.schemas.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.schemas.delete" class="permission-name add-link" data-text="datastore.schemas.delete" tabindex="-1"><code dir="ltr" translate="no">datastore.schemas.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.schemas.get" class="permission-name add-link" data-text="datastore.schemas.get" tabindex="-1"><code dir="ltr" translate="no">datastore.schemas.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datastore.schemas.list" class="permission-name add-link" data-text="datastore.schemas.list" tabindex="-1"><code dir="ltr" translate="no">datastore.schemas.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.schemas.update" class="permission-name add-link" data-text="datastore.schemas.update" tabindex="-1"><code dir="ltr" translate="no">datastore.schemas.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.statistics.get" class="permission-name add-link" data-text="datastore.statistics.get" tabindex="-1"><code dir="ltr" translate="no">datastore.statistics.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.statistics.list" class="permission-name add-link" data-text="datastore.statistics.list" tabindex="-1"><code dir="ltr" translate="no">datastore.statistics.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAgent">App Engine Standard Environment Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="datastore.userCreds.create" class="permission-name add-link" data-text="datastore.userCreds.create" tabindex="-1"><code dir="ltr" translate="no">datastore.userCreds.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.userCredsAdmin">Cloud Datastore User Creds Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.userCredsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.userCreds.delete" class="permission-name add-link" data-text="datastore.userCreds.delete" tabindex="-1"><code dir="ltr" translate="no">datastore.userCreds.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.userCredsAdmin">Cloud Datastore User Creds Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.userCredsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.userCreds.get" class="permission-name add-link" data-text="datastore.userCreds.get" tabindex="-1"><code dir="ltr" translate="no">datastore.userCreds.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.userCredsAdmin">Cloud Datastore User Creds Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.userCredsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.userCredsViewer">Cloud Datastore User Creds Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.userCredsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastore.userCreds.list" class="permission-name add-link" data-text="datastore.userCreds.list" tabindex="-1"><code dir="ltr" translate="no">datastore.userCreds.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.userCredsAdmin">Cloud Datastore User Creds Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.userCredsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.userCredsViewer">Cloud Datastore User Creds Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.userCredsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastore.userCreds.update" class="permission-name add-link" data-text="datastore.userCreds.update" tabindex="-1"><code dir="ltr" translate="no">datastore.userCreds.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.userCredsAdmin">Cloud Datastore User Creds Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastore.userCredsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
</tbody>
</table>
