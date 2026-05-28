---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudsql
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql
title: Cloud SQL roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud SQL. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud SQL roles

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
<td><h4 id="cloudsql.admin" class="role-title add-link" data-text="Cloud SQL Admin" tabindex="-1">Cloud SQL Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p>Provides full control of Cloud SQL resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  fetchForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvbackups.  useReadOnlyForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  bvdataSources.  useReadOnlyForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  fetchForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  dataSourceReferences.  getForCloudSqlInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.locations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  serviceConfig.  initialize</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.companions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudaicompanion.  companions.  generateChat</code></li>
<li><code dir="ltr" translate="no">cloudaicompanion.  companions.  generateCode</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudaicompanion.  entitlements.  get</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  completeCode</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  generateCode</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">cloudsql.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudsql.backupRuns.create</code></li>
<li><code dir="ltr" translate="no">cloudsql.backupRuns.delete</code></li>
<li><code dir="ltr" translate="no">cloudsql.backupRuns.export</code></li>
<li><code dir="ltr" translate="no">cloudsql.backupRuns.get</code></li>
<li><code dir="ltr" translate="no">cloudsql.backupRuns.list</code></li>
<li><code dir="ltr" translate="no">cloudsql.backupRuns.update</code></li>
<li><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  create</code></li>
<li><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  delete</code></li>
<li><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  get</code></li>
<li><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  list</code></li>
<li><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  switchover</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.create</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.delete</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.get</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.list</code></li>
<li><code dir="ltr" translate="no">cloudsql.databases.update</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  addEntraIdCertificate</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.addServerCa</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  addServerCertificate</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.clone</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.connect</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.create</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  createBackupDrBackup</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.delete</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  demoteMaster</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.executeSql</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.export</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.failover</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.get</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  getDiskShrinkConfig</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.import</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.list</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  listEntraIdCertificates</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  listServerCas</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  listServerCertificates</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.login</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  manageEncryption</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.migrate</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  performDiskShrink</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  preCheckMajorVersionUpgrade</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  promoteReplica</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.reencrypt</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  resetReplicaSize</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  resetSslConfig</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.restart</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  restoreBackup</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  rotateEntraIdCertificate</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  rotateServerCa</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  rotateServerCertificate</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  startReplica</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.stopReplica</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.truncateLog</code></li>
<li><code dir="ltr" translate="no">cloudsql.instances.update</code></li>
<li><code dir="ltr" translate="no">cloudsql.  instances.  updateBackupDrConfig</code></li>
<li><code dir="ltr" translate="no">cloudsql.schemas.view</code></li>
<li><code dir="ltr" translate="no">cloudsql.sslCerts.create</code></li>
<li><code dir="ltr" translate="no">cloudsql.sslCerts.delete</code></li>
<li><code dir="ltr" translate="no">cloudsql.sslCerts.get</code></li>
<li><code dir="ltr" translate="no">cloudsql.sslCerts.list</code></li>
<li><code dir="ltr" translate="no">cloudsql.users.create</code></li>
<li><code dir="ltr" translate="no">cloudsql.users.delete</code></li>
<li><code dir="ltr" translate="no">cloudsql.users.get</code></li>
<li><code dir="ltr" translate="no">cloudsql.users.list</code></li>
<li><code dir="ltr" translate="no">cloudsql.users.update</code></li>
</ul>
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
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.client" class="role-title add-link" data-text="Cloud SQL Client" tabindex="-1">Cloud SQL Client</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsql.client</code> )</p>
<p>Provides connectivity access to Cloud SQL instances.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudsql.instances.connect</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.editor" class="role-title add-link" data-text="Cloud SQL Editor" tabindex="-1">Cloud SQL Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p>Provides full control of existing Cloud SQL instances excluding modifying users, SSL certificates or deleting resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudaicompanion.  entitlements.  get</code></p>
<p><code dir="ltr" translate="no">cloudsql.backupRuns.create</code></p>
<p><code dir="ltr" translate="no">cloudsql.backupRuns.export</code></p>
<p><code dir="ltr" translate="no">cloudsql.backupRuns.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.backupRuns.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.backupRuns.update</code></p>
<p><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  create</code></p>
<p><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  get</code></p>
<p><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  list</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.create</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.update</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  addEntraIdCertificate</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.addServerCa</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  addServerCertificate</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.connect</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.export</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.failover</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  getDiskShrinkConfig</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listEntraIdCertificates</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listServerCas</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listServerCertificates</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.migrate</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  performDiskShrink</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  preCheckMajorVersionUpgrade</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.reencrypt</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  resetReplicaSize</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.restart</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  rotateEntraIdCertificate</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  rotateServerCa</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  rotateServerCertificate</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.truncateLog</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.update</code></p>
<p><code dir="ltr" translate="no">cloudsql.schemas.view</code></p>
<p><code dir="ltr" translate="no">cloudsql.sslCerts.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.sslCerts.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instanceUser" class="role-title add-link" data-text="Cloud SQL Instance User" tabindex="-1">Cloud SQL Instance User</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsql.instanceUser</code> )</p>
<p>Role allowing access to a Cloud SQL instance</p></td>
<td><p><code dir="ltr" translate="no">cloudsql.instances.executeSql</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.login</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.viewer" class="role-title add-link" data-text="Cloud SQL Viewer" tabindex="-1">Cloud SQL Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p>Provides read-only access to Cloud SQL resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudaicompanion.  entitlements.  get</code></p>
<p><code dir="ltr" translate="no">cloudsql.backupRuns.export</code></p>
<p><code dir="ltr" translate="no">cloudsql.backupRuns.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.backupRuns.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  get</code></p>
<p><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  list</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.export</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  getDiskShrinkConfig</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listEntraIdCertificates</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listServerCas</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listServerCertificates</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  preCheckMajorVersionUpgrade</code></p>
<p><code dir="ltr" translate="no">cloudsql.sslCerts.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.sslCerts.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.schemaViewer" class="role-title add-link" data-text="Cloud SQL Schema Viewer" tabindex="-1">Cloud SQL Schema Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsql.schemaViewer</code> )</p>
<p>Role allowing access to the Cloud SQL instance schema on Dataplex</p></td>
<td><p><code dir="ltr" translate="no">cloudsql.schemas.view</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.studioUser" class="role-title add-link" data-text="Cloud SQL Studio User" tabindex="-1">Cloud SQL Studio User</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsql.studioUser</code> )</p>
<p>Role allowing access to Cloud SQL Studio</p></td>
<td><p><code dir="ltr" translate="no">cloudaicompanion.companions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudaicompanion.  companions.  generateChat</code></li>
<li><code dir="ltr" translate="no">cloudaicompanion.  companions.  generateCode</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  completeCode</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  generateCode</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.executeSql</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.login</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.list</code></p>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p></td>
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
<td><h4 id="cloudsql.serviceAgent" class="role-title add-link" data-text="Cloud SQL Service Agent" tabindex="-1">Cloud SQL Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudsql.serviceAgent</code> )</p>
<p>Grants Cloud SQL access to services and APIs in the user project</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudsql.instances.get</code></p></td>
</tr>
</tbody>
</table>

## Cloud SQL permissions

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
<td><h4 id="cloudsql.backupRuns.create" class="permission-name add-link" data-text="cloudsql.backupRuns.create" tabindex="-1"><code dir="ltr" translate="no">cloudsql.backupRuns.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.backupRuns.delete" class="permission-name add-link" data-text="cloudsql.backupRuns.delete" tabindex="-1"><code dir="ltr" translate="no">cloudsql.backupRuns.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
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
<td><h4 id="cloudsql.backupRuns.export" class="permission-name add-link" data-text="cloudsql.backupRuns.export" tabindex="-1"><code dir="ltr" translate="no">cloudsql.backupRuns.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudsql.backupRuns.get" class="permission-name add-link" data-text="cloudsql.backupRuns.get" tabindex="-1"><code dir="ltr" translate="no">cloudsql.backupRuns.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudsql.backupRuns.list" class="permission-name add-link" data-text="cloudsql.backupRuns.list" tabindex="-1"><code dir="ltr" translate="no">cloudsql.backupRuns.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudsql.backupRuns.update" class="permission-name add-link" data-text="cloudsql.backupRuns.update" tabindex="-1"><code dir="ltr" translate="no">cloudsql.backupRuns.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.blueGreenDeployments.create" class="permission-name add-link" data-text="cloudsql.blueGreenDeployments.create" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.blueGreenDeployments.delete" class="permission-name add-link" data-text="cloudsql.blueGreenDeployments.delete" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
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
<td><h4 id="cloudsql.blueGreenDeployments.get" class="permission-name add-link" data-text="cloudsql.blueGreenDeployments.get" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudsql.blueGreenDeployments.list" class="permission-name add-link" data-text="cloudsql.blueGreenDeployments.list" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudsql.blueGreenDeployments.switchover" class="permission-name add-link" data-text="cloudsql.blueGreenDeployments.switchover" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  blueGreenDeployments.  switchover</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
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
<td><h4 id="cloudsql.databases.create" class="permission-name add-link" data-text="cloudsql.databases.create" tabindex="-1"><code dir="ltr" translate="no">cloudsql.databases.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.serviceAgent">Firebase Data Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedataconnect.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.databases.delete" class="permission-name add-link" data-text="cloudsql.databases.delete" tabindex="-1"><code dir="ltr" translate="no">cloudsql.databases.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.databases.get" class="permission-name add-link" data-text="cloudsql.databases.get" tabindex="-1"><code dir="ltr" translate="no">cloudsql.databases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.serviceAgent">Firebase Data Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedataconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.databases.list" class="permission-name add-link" data-text="cloudsql.databases.list" tabindex="-1"><code dir="ltr" translate="no">cloudsql.databases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.studioUser">Cloud SQL Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.databases.update" class="permission-name add-link" data-text="cloudsql.databases.update" tabindex="-1"><code dir="ltr" translate="no">cloudsql.databases.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.instances.addEntraIdCertificate" class="permission-name add-link" data-text="cloudsql.instances.addEntraIdCertificate" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  addEntraIdCertificate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.addServerCa" class="permission-name add-link" data-text="cloudsql.instances.addServerCa" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.addServerCa</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.instances.addServerCertificate" class="permission-name add-link" data-text="cloudsql.instances.addServerCertificate" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  addServerCertificate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.clone" class="permission-name add-link" data-text="cloudsql.instances.clone" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.clone</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
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
<td><h4 id="cloudsql.instances.connect" class="permission-name add-link" data-text="cloudsql.instances.connect" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.connect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.client">Cloud SQL Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryconnection#bigqueryconnection.serviceAgent">BigQuery Connection Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigqueryconnection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.serviceAgent">Firebase Data Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedataconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.create" class="permission-name add-link" data-text="cloudsql.instances.create" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.instances.createBackupDrBackup" class="permission-name add-link" data-text="cloudsql.instances.createBackupDrBackup" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  createBackupDrBackup</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudSqlOperator">Backup and DR Cloud SQL Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.cloudSqlOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.createTagBinding" class="permission-name add-link" data-text="cloudsql.instances.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
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
<td><h4 id="cloudsql.instances.delete" class="permission-name add-link" data-text="cloudsql.instances.delete" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.deleteTagBinding" class="permission-name add-link" data-text="cloudsql.instances.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
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
<td><h4 id="cloudsql.instances.demoteMaster" class="permission-name add-link" data-text="cloudsql.instances.demoteMaster" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  demoteMaster</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.executeSql" class="permission-name add-link" data-text="cloudsql.instances.executeSql" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.executeSql</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.instanceUser">Cloud SQL Instance User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.instanceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.studioUser">Cloud SQL Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.instances.export" class="permission-name add-link" data-text="cloudsql.instances.export" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.failover" class="permission-name add-link" data-text="cloudsql.instances.failover" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.failover</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.instances.get" class="permission-name add-link" data-text="cloudsql.instances.get" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.client">Cloud SQL Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.instanceUser">Cloud SQL Instance User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.instanceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.cloudSqlOperator">Backup and DR Cloud SQL Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.cloudSqlOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.studioUser">Cloud SQL Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryconnection#bigqueryconnection.serviceAgent">BigQuery Connection Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigqueryconnection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.serviceAgent">Cloud SQL Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.serviceAgent">Firebase Data Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedataconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.serviceAgent">GCP Network Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.getDiskShrinkConfig" class="permission-name add-link" data-text="cloudsql.instances.getDiskShrinkConfig" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  getDiskShrinkConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudsql.instances.import" class="permission-name add-link" data-text="cloudsql.instances.import" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.list" class="permission-name add-link" data-text="cloudsql.instances.list" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.serviceAgent">GCP Network Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.instances.listEffectiveTags" class="permission-name add-link" data-text="cloudsql.instances.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudsql.instances.listEntraIdCertificates" class="permission-name add-link" data-text="cloudsql.instances.listEntraIdCertificates" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  listEntraIdCertificates</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudsql.instances.listServerCas" class="permission-name add-link" data-text="cloudsql.instances.listServerCas" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  listServerCas</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudsql.instances.listServerCertificates" class="permission-name add-link" data-text="cloudsql.instances.listServerCertificates" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  listServerCertificates</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudsql.instances.listTagBindings" class="permission-name add-link" data-text="cloudsql.instances.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudsql.instances.login" class="permission-name add-link" data-text="cloudsql.instances.login" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.login</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.instanceUser">Cloud SQL Instance User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.instanceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.studioUser">Cloud SQL Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.serviceAgent">Firebase Data Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedataconnect.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.instances.manageEncryption" class="permission-name add-link" data-text="cloudsql.instances.manageEncryption" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  manageEncryption</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
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
<td><h4 id="cloudsql.instances.migrate" class="permission-name add-link" data-text="cloudsql.instances.migrate" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.migrate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.instances.performDiskShrink" class="permission-name add-link" data-text="cloudsql.instances.performDiskShrink" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  performDiskShrink</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.preCheckMajorVersionUpgrade" class="permission-name add-link" data-text="cloudsql.instances.preCheckMajorVersionUpgrade" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  preCheckMajorVersionUpgrade</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudsql.instances.promoteReplica" class="permission-name add-link" data-text="cloudsql.instances.promoteReplica" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  promoteReplica</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.reencrypt" class="permission-name add-link" data-text="cloudsql.instances.reencrypt" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.reencrypt</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.instances.resetReplicaSize" class="permission-name add-link" data-text="cloudsql.instances.resetReplicaSize" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  resetReplicaSize</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.resetSslConfig" class="permission-name add-link" data-text="cloudsql.instances.resetSslConfig" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  resetSslConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
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
<td><h4 id="cloudsql.instances.restart" class="permission-name add-link" data-text="cloudsql.instances.restart" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.restart</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.restoreBackup" class="permission-name add-link" data-text="cloudsql.instances.restoreBackup" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  restoreBackup</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
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
<td><h4 id="cloudsql.instances.rotateEntraIdCertificate" class="permission-name add-link" data-text="cloudsql.instances.rotateEntraIdCertificate" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  rotateEntraIdCertificate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.rotateServerCa" class="permission-name add-link" data-text="cloudsql.instances.rotateServerCa" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  rotateServerCa</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.instances.rotateServerCertificate" class="permission-name add-link" data-text="cloudsql.instances.rotateServerCertificate" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  rotateServerCertificate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.startReplica" class="permission-name add-link" data-text="cloudsql.instances.startReplica" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  startReplica</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.instances.stopReplica" class="permission-name add-link" data-text="cloudsql.instances.stopReplica" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.stopReplica</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.truncateLog" class="permission-name add-link" data-text="cloudsql.instances.truncateLog" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.truncateLog</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.instances.update" class="permission-name add-link" data-text="cloudsql.instances.update" tabindex="-1"><code dir="ltr" translate="no">cloudsql.instances.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.instances.updateBackupDrConfig" class="permission-name add-link" data-text="cloudsql.instances.updateBackupDrConfig" tabindex="-1"><code dir="ltr" translate="no">cloudsql.  instances.  updateBackupDrConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
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
<td><h4 id="cloudsql.schemas.view" class="permission-name add-link" data-text="cloudsql.schemas.view" tabindex="-1"><code dir="ltr" translate="no">cloudsql.schemas.view</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.schemaViewer">Cloud SQL Schema Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.schemaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
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
<td><h4 id="cloudsql.sslCerts.create" class="permission-name add-link" data-text="cloudsql.sslCerts.create" tabindex="-1"><code dir="ltr" translate="no">cloudsql.sslCerts.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.sslCerts.delete" class="permission-name add-link" data-text="cloudsql.sslCerts.delete" tabindex="-1"><code dir="ltr" translate="no">cloudsql.sslCerts.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.sslCerts.get" class="permission-name add-link" data-text="cloudsql.sslCerts.get" tabindex="-1"><code dir="ltr" translate="no">cloudsql.sslCerts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.sslCerts.list" class="permission-name add-link" data-text="cloudsql.sslCerts.list" tabindex="-1"><code dir="ltr" translate="no">cloudsql.sslCerts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
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
<td><h4 id="cloudsql.users.create" class="permission-name add-link" data-text="cloudsql.users.create" tabindex="-1"><code dir="ltr" translate="no">cloudsql.users.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.serviceAgent">Firebase Data Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedataconnect.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.users.delete" class="permission-name add-link" data-text="cloudsql.users.delete" tabindex="-1"><code dir="ltr" translate="no">cloudsql.users.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.users.get" class="permission-name add-link" data-text="cloudsql.users.get" tabindex="-1"><code dir="ltr" translate="no">cloudsql.users.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.serviceAgent">Firebase Data Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedataconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudsql.users.list" class="permission-name add-link" data-text="cloudsql.users.list" tabindex="-1"><code dir="ltr" translate="no">cloudsql.users.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.studioUser">Cloud SQL Studio User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudsql.users.update" class="permission-name add-link" data-text="cloudsql.users.update" tabindex="-1"><code dir="ltr" translate="no">cloudsql.users.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
