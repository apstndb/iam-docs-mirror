---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/alloydb
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb
title: AlloyDB for PostgreSQL roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for AlloyDB for PostgreSQL. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## AlloyDB for PostgreSQL roles

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
<td><h4 id="alloydb.admin" class="role-title add-link" data-text="AlloyDB Admin" tabindex="-1">AlloyDB Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p>Full access to AlloyDB all resources.</p></td>
<td><p><code dir="ltr" translate="no">alloydb.*</code></p>
<ul>
<li><code dir="ltr" translate="no">alloydb.backups.create</code></li>
<li><code dir="ltr" translate="no">alloydb.  backups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">alloydb.backups.delete</code></li>
<li><code dir="ltr" translate="no">alloydb.  backups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">alloydb.backups.get</code></li>
<li><code dir="ltr" translate="no">alloydb.backups.list</code></li>
<li><code dir="ltr" translate="no">alloydb.  backups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">alloydb.  backups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">alloydb.backups.update</code></li>
<li><code dir="ltr" translate="no">alloydb.clusters.create</code></li>
<li><code dir="ltr" translate="no">alloydb.  clusters.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">alloydb.clusters.delete</code></li>
<li><code dir="ltr" translate="no">alloydb.  clusters.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">alloydb.clusters.export</code></li>
<li><code dir="ltr" translate="no">alloydb.  clusters.  generateClientCertificate</code></li>
<li><code dir="ltr" translate="no">alloydb.clusters.get</code></li>
<li><code dir="ltr" translate="no">alloydb.clusters.import</code></li>
<li><code dir="ltr" translate="no">alloydb.clusters.list</code></li>
<li><code dir="ltr" translate="no">alloydb.  clusters.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">alloydb.  clusters.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">alloydb.clusters.promote</code></li>
<li><code dir="ltr" translate="no">alloydb.clusters.switchover</code></li>
<li><code dir="ltr" translate="no">alloydb.clusters.update</code></li>
<li><code dir="ltr" translate="no">alloydb.clusters.upgrade</code></li>
<li><code dir="ltr" translate="no">alloydb.databases.create</code></li>
<li><code dir="ltr" translate="no">alloydb.databases.get</code></li>
<li><code dir="ltr" translate="no">alloydb.databases.list</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.connect</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.create</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.delete</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.executeSql</code></li>
<li><code dir="ltr" translate="no">alloydb.  instances.  executeSqlReadOnly</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.failover</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.get</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.injectFault</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.list</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.restart</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.update</code></li>
<li><code dir="ltr" translate="no">alloydb.locations.get</code></li>
<li><code dir="ltr" translate="no">alloydb.locations.list</code></li>
<li><code dir="ltr" translate="no">alloydb.operations.cancel</code></li>
<li><code dir="ltr" translate="no">alloydb.operations.delete</code></li>
<li><code dir="ltr" translate="no">alloydb.operations.get</code></li>
<li><code dir="ltr" translate="no">alloydb.operations.list</code></li>
<li><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  get</code></li>
<li><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  list</code></li>
<li><code dir="ltr" translate="no">alloydb.users.create</code></li>
<li><code dir="ltr" translate="no">alloydb.users.delete</code></li>
<li><code dir="ltr" translate="no">alloydb.users.get</code></li>
<li><code dir="ltr" translate="no">alloydb.users.list</code></li>
<li><code dir="ltr" translate="no">alloydb.users.login</code></li>
<li><code dir="ltr" translate="no">alloydb.users.update</code></li>
</ul>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.locations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  serviceConfig.  initialize</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  entitlements.  get</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
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
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.editor" class="role-title add-link" data-text="AlloyDB Editor" tabindex="-1">AlloyDB Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p>Editor role for AlloyDB</p></td>
<td><p><code dir="ltr" translate="no">alloydb.backups.create</code></p>
<p><code dir="ltr" translate="no">alloydb.backups.delete</code></p>
<p><code dir="ltr" translate="no">alloydb.backups.get</code></p>
<p><code dir="ltr" translate="no">alloydb.backups.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">alloydb.backups.update</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.create</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.delete</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.export</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  generateClientCertificate</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.get</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.import</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.promote</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.switchover</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.update</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.upgrade</code></p>
<p><code dir="ltr" translate="no">alloydb.databases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">alloydb.databases.create</code></li>
<li><code dir="ltr" translate="no">alloydb.databases.get</code></li>
<li><code dir="ltr" translate="no">alloydb.databases.list</code></li>
</ul>
<p><code dir="ltr" translate="no">alloydb.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">alloydb.instances.connect</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.create</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.delete</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.executeSql</code></li>
<li><code dir="ltr" translate="no">alloydb.  instances.  executeSqlReadOnly</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.failover</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.get</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.injectFault</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.list</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.restart</code></li>
<li><code dir="ltr" translate="no">alloydb.instances.update</code></li>
</ul>
<p><code dir="ltr" translate="no">alloydb.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">alloydb.locations.get</code></li>
<li><code dir="ltr" translate="no">alloydb.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">alloydb.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">alloydb.operations.cancel</code></li>
<li><code dir="ltr" translate="no">alloydb.operations.delete</code></li>
<li><code dir="ltr" translate="no">alloydb.operations.get</code></li>
<li><code dir="ltr" translate="no">alloydb.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  get</code></li>
<li><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">alloydb.users.*</code></p>
<ul>
<li><code dir="ltr" translate="no">alloydb.users.create</code></li>
<li><code dir="ltr" translate="no">alloydb.users.delete</code></li>
<li><code dir="ltr" translate="no">alloydb.users.get</code></li>
<li><code dir="ltr" translate="no">alloydb.users.list</code></li>
<li><code dir="ltr" translate="no">alloydb.users.login</code></li>
<li><code dir="ltr" translate="no">alloydb.users.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudaicompanion.  entitlements.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.viewer" class="role-title add-link" data-text="AlloyDB Viewer" tabindex="-1">AlloyDB Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p>Read-only access to AlloyDB all resources.</p></td>
<td><p><code dir="ltr" translate="no">alloydb.backups.get</code></p>
<p><code dir="ltr" translate="no">alloydb.backups.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.export</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.get</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">alloydb.databases.get</code></p>
<p><code dir="ltr" translate="no">alloydb.databases.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  instances.  executeSqlReadOnly</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.get</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.list</code></p>
<p><code dir="ltr" translate="no">alloydb.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">alloydb.locations.get</code></li>
<li><code dir="ltr" translate="no">alloydb.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">alloydb.operations.get</code></p>
<p><code dir="ltr" translate="no">alloydb.operations.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  get</code></li>
<li><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">alloydb.users.get</code></p>
<p><code dir="ltr" translate="no">alloydb.users.list</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  entitlements.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.backupDrAdmin" class="role-title add-link" data-text="AlloyDB Admin for BackupDR" tabindex="-1">AlloyDB Admin for BackupDR</h4>
<p>( <code dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p>Full access to AlloyDB all clusters resources for BackupDR</p></td>
<td><p><code dir="ltr" translate="no">alloydb.clusters.create</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.get</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.list</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.create</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.get</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.list</code></p>
<p><code dir="ltr" translate="no">alloydb.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForAlloydbCluster</code></p>
<p><code dir="ltr" translate="no">backupdr.locations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  serviceConfig.  initialize</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.client" class="role-title add-link" data-text="AlloyDB Client" tabindex="-1">AlloyDB Client</h4>
<p>( <code dir="ltr" translate="no">roles/  alloydb.client</code> )</p>
<p>Connectivity access to AlloyDB instances.</p></td>
<td><p><code dir="ltr" translate="no">alloydb.  clusters.  generateClientCertificate</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.get</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.connect</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.get</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.databaseUser" class="role-title add-link" data-text="AlloyDB Database User" tabindex="-1">AlloyDB Database User</h4>
<p>( <code dir="ltr" translate="no">roles/  alloydb.databaseUser</code> )</p>
<p>Role allowing access to login as a database user.</p></td>
<td><p><code dir="ltr" translate="no">alloydb.clusters.get</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.executeSql</code></p>
<p><code dir="ltr" translate="no">alloydb.  instances.  executeSqlReadOnly</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.get</code></p>
<p><code dir="ltr" translate="no">alloydb.users.login</code></p>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></p>
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
<td><h4 id="alloydb.serviceAgent" class="role-title add-link" data-text="AlloyDB Service Agent" tabindex="-1">AlloyDB Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  alloydb.serviceAgent</code> )</p>
<p>Gives the AlloyDB service account permission to manage customer resources</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">alloydb.clusters.list</code></p></td>
</tr>
</tbody>
</table>

## AlloyDB for PostgreSQL permissions

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
<td><h4 id="alloydb.backups.create" class="permission-name add-link" data-text="alloydb.backups.create" tabindex="-1"><code dir="ltr" translate="no">alloydb.backups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.backups.createTagBinding" class="permission-name add-link" data-text="alloydb.backups.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">alloydb.  backups.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.backups.delete" class="permission-name add-link" data-text="alloydb.backups.delete" tabindex="-1"><code dir="ltr" translate="no">alloydb.backups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.backups.deleteTagBinding" class="permission-name add-link" data-text="alloydb.backups.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">alloydb.  backups.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.backups.get" class="permission-name add-link" data-text="alloydb.backups.get" tabindex="-1"><code dir="ltr" translate="no">alloydb.backups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.backups.list" class="permission-name add-link" data-text="alloydb.backups.list" tabindex="-1"><code dir="ltr" translate="no">alloydb.backups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.backups.listEffectiveTags" class="permission-name add-link" data-text="alloydb.backups.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">alloydb.  backups.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.backups.listTagBindings" class="permission-name add-link" data-text="alloydb.backups.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">alloydb.  backups.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.backups.update" class="permission-name add-link" data-text="alloydb.backups.update" tabindex="-1"><code dir="ltr" translate="no">alloydb.backups.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.clusters.create" class="permission-name add-link" data-text="alloydb.clusters.create" tabindex="-1"><code dir="ltr" translate="no">alloydb.clusters.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.clusters.createTagBinding" class="permission-name add-link" data-text="alloydb.clusters.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">alloydb.  clusters.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.clusters.delete" class="permission-name add-link" data-text="alloydb.clusters.delete" tabindex="-1"><code dir="ltr" translate="no">alloydb.clusters.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.clusters.deleteTagBinding" class="permission-name add-link" data-text="alloydb.clusters.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">alloydb.  clusters.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.clusters.export" class="permission-name add-link" data-text="alloydb.clusters.export" tabindex="-1"><code dir="ltr" translate="no">alloydb.clusters.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.clusters.generateClientCertificate" class="permission-name add-link" data-text="alloydb.clusters.generateClientCertificate" tabindex="-1"><code dir="ltr" translate="no">alloydb.  clusters.  generateClientCertificate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.client">AlloyDB Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.clusters.get" class="permission-name add-link" data-text="alloydb.clusters.get" tabindex="-1"><code dir="ltr" translate="no">alloydb.clusters.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.client">AlloyDB Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.databaseUser">AlloyDB Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.clusters.import" class="permission-name add-link" data-text="alloydb.clusters.import" tabindex="-1"><code dir="ltr" translate="no">alloydb.clusters.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.clusters.list" class="permission-name add-link" data-text="alloydb.clusters.list" tabindex="-1"><code dir="ltr" translate="no">alloydb.clusters.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.serviceAgent">AlloyDB Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.clusters.listEffectiveTags" class="permission-name add-link" data-text="alloydb.clusters.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">alloydb.  clusters.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.clusters.listTagBindings" class="permission-name add-link" data-text="alloydb.clusters.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">alloydb.  clusters.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.clusters.promote" class="permission-name add-link" data-text="alloydb.clusters.promote" tabindex="-1"><code dir="ltr" translate="no">alloydb.clusters.promote</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.clusters.switchover" class="permission-name add-link" data-text="alloydb.clusters.switchover" tabindex="-1"><code dir="ltr" translate="no">alloydb.clusters.switchover</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.clusters.update" class="permission-name add-link" data-text="alloydb.clusters.update" tabindex="-1"><code dir="ltr" translate="no">alloydb.clusters.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.clusters.upgrade" class="permission-name add-link" data-text="alloydb.clusters.upgrade" tabindex="-1"><code dir="ltr" translate="no">alloydb.clusters.upgrade</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.databases.create" class="permission-name add-link" data-text="alloydb.databases.create" tabindex="-1"><code dir="ltr" translate="no">alloydb.databases.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.databases.get" class="permission-name add-link" data-text="alloydb.databases.get" tabindex="-1"><code dir="ltr" translate="no">alloydb.databases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.databases.list" class="permission-name add-link" data-text="alloydb.databases.list" tabindex="-1"><code dir="ltr" translate="no">alloydb.databases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.instances.connect" class="permission-name add-link" data-text="alloydb.instances.connect" tabindex="-1"><code dir="ltr" translate="no">alloydb.instances.connect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.client">AlloyDB Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.instances.create" class="permission-name add-link" data-text="alloydb.instances.create" tabindex="-1"><code dir="ltr" translate="no">alloydb.instances.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.instances.delete" class="permission-name add-link" data-text="alloydb.instances.delete" tabindex="-1"><code dir="ltr" translate="no">alloydb.instances.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.instances.executeSql" class="permission-name add-link" data-text="alloydb.instances.executeSql" tabindex="-1"><code dir="ltr" translate="no">alloydb.instances.executeSql</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.databaseUser">AlloyDB Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.instances.executeSqlReadOnly" class="permission-name add-link" data-text="alloydb.instances.executeSqlReadOnly" tabindex="-1"><code dir="ltr" translate="no">alloydb.  instances.  executeSqlReadOnly</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.databaseUser">AlloyDB Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.instances.failover" class="permission-name add-link" data-text="alloydb.instances.failover" tabindex="-1"><code dir="ltr" translate="no">alloydb.instances.failover</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.instances.get" class="permission-name add-link" data-text="alloydb.instances.get" tabindex="-1"><code dir="ltr" translate="no">alloydb.instances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.client">AlloyDB Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.databaseUser">AlloyDB Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.instances.injectFault" class="permission-name add-link" data-text="alloydb.instances.injectFault" tabindex="-1"><code dir="ltr" translate="no">alloydb.instances.injectFault</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.instances.list" class="permission-name add-link" data-text="alloydb.instances.list" tabindex="-1"><code dir="ltr" translate="no">alloydb.instances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.instances.restart" class="permission-name add-link" data-text="alloydb.instances.restart" tabindex="-1"><code dir="ltr" translate="no">alloydb.instances.restart</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.instances.update" class="permission-name add-link" data-text="alloydb.instances.update" tabindex="-1"><code dir="ltr" translate="no">alloydb.instances.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.locations.get" class="permission-name add-link" data-text="alloydb.locations.get" tabindex="-1"><code dir="ltr" translate="no">alloydb.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.locations.list" class="permission-name add-link" data-text="alloydb.locations.list" tabindex="-1"><code dir="ltr" translate="no">alloydb.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.operations.cancel" class="permission-name add-link" data-text="alloydb.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">alloydb.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.operations.delete" class="permission-name add-link" data-text="alloydb.operations.delete" tabindex="-1"><code dir="ltr" translate="no">alloydb.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.operations.get" class="permission-name add-link" data-text="alloydb.operations.get" tabindex="-1"><code dir="ltr" translate="no">alloydb.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.backupDrAdmin">AlloyDB Admin for BackupDR</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.backupDrAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.alloydbOperator">Backup and DR AlloyDB Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.alloydbOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.operations.list" class="permission-name add-link" data-text="alloydb.operations.list" tabindex="-1"><code dir="ltr" translate="no">alloydb.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.supportedDatabaseFlags.get" class="permission-name add-link" data-text="alloydb.supportedDatabaseFlags.get" tabindex="-1"><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.supportedDatabaseFlags.list" class="permission-name add-link" data-text="alloydb.supportedDatabaseFlags.list" tabindex="-1"><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.users.create" class="permission-name add-link" data-text="alloydb.users.create" tabindex="-1"><code dir="ltr" translate="no">alloydb.users.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.users.delete" class="permission-name add-link" data-text="alloydb.users.delete" tabindex="-1"><code dir="ltr" translate="no">alloydb.users.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.users.get" class="permission-name add-link" data-text="alloydb.users.get" tabindex="-1"><code dir="ltr" translate="no">alloydb.users.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.users.list" class="permission-name add-link" data-text="alloydb.users.list" tabindex="-1"><code dir="ltr" translate="no">alloydb.users.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="alloydb.users.login" class="permission-name add-link" data-text="alloydb.users.login" tabindex="-1"><code dir="ltr" translate="no">alloydb.users.login</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.databaseUser">AlloyDB Database User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="alloydb.users.update" class="permission-name add-link" data-text="alloydb.users.update" tabindex="-1"><code dir="ltr" translate="no">alloydb.users.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
</tbody>
</table>
