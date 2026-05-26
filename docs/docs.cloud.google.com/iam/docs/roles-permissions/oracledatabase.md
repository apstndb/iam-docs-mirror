---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase
title: Oracle Database@Google Cloud roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Oracle Database@Google Cloud. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Oracle Database@Google Cloud roles

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
<td><h4 id="oracledatabase.admin" class="role-title add-link" data-text="Oracle Database@Google Cloud admin" tabindex="-1">Oracle Database@Google Cloud admin</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p>Grants full access to manage all Oracle Database resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseCharacterSets.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  failover</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  generateWallet</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  restart</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  restore</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  start</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  stop</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  switchover</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDbVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  update</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  databaseCharacterSets.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.databases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.databases.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.databases.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.dbNodes.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbServers.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemInitialStorageSizes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbSystems.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  dbSystems.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  dbSystems.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.dbSystems.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.dbSystems.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.dbVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  test</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionTypes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentEnvironments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentTypes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  start</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  stop</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  minorVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbNetworks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.odbNetworks.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  odbSubnets.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  odbSubnets.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.odbSubnets.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.odbSubnets.use</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  systemVersions.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.viewer" class="role-title add-link" data-text="Oracle Database@Google Cloud viewer" tabindex="-1">Oracle Database@Google Cloud viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p>Grants view access to all Oracle Database resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseCharacterSets.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDbVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  databaseCharacterSets.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.databases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.databases.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.databases.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.dbNodes.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbServers.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbSystems.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbSystems.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  minorVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbNetworks.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  pluggableDatabases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  pluggableDatabases.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  pluggableDatabases.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.autonomousDatabaseAdmin" class="role-title add-link" data-text="Oracle Database@Google Cloud Autonomous Database Admin" tabindex="-1">Oracle Database@Google Cloud Autonomous Database Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p>Grants full access to manage all Autonomous Database resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseCharacterSets.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  failover</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  generateWallet</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  restart</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  restore</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  start</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  stop</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  switchover</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDbVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.autonomousDatabaseViewer" class="role-title add-link" data-text="Oracle Database@Google Cloud Autonomous Database Viewer" tabindex="-1">Oracle Database@Google Cloud Autonomous Database Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p>
<p>Grants read access to see all Autonomous Database resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseCharacterSets.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  autonomousDbVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.cloudExadataInfrastructureAdmin" class="role-title add-link" data-text="Oracle Database@Google Cloud Exadata Infrastructure Admin" tabindex="-1">Oracle Database@Google Cloud Exadata Infrastructure Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p>Grants full access to manage all Exadata Infrastructure resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  create</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  delete</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  update</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbServers.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.cloudExadataInfrastructureUser" class="role-title add-link" data-text="Oracle Database@Google Cloud Exadata Infrastructure User" tabindex="-1">Oracle Database@Google Cloud Exadata Infrastructure User</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p>Grants user access to use all Exadata Infrastructure resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbServers.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.cloudExadataInfrastructureViewer" class="role-title add-link" data-text="Oracle Database@Google Cloud Exadata Infrastructure Viewer" tabindex="-1">Oracle Database@Google Cloud Exadata Infrastructure Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p>Grants read access to see all Exadata Infrastructure resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbServers.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.cloudVmClusterAdmin" class="role-title add-link" data-text="Oracle Database@Google Cloud VM Cluster Admin" tabindex="-1">Oracle Database@Google Cloud VM Cluster Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p>Grants full access to manage all VM Cluster resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.dbNodes.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbServers.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  minorVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  systemVersions.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.cloudVmClusterViewer" class="role-title add-link" data-text="Oracle Database@Google Cloud VM Cluster Viewer" tabindex="-1">Oracle Database@Google Cloud VM Cluster Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterViewer</code> )</p>
<p>Grants read access to see all VM Cluster resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbNodes.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.databaseViewer" class="role-title add-link" data-text="Oracle Database@Google Cloud Container Database Viewer" tabindex="-1">Oracle Database@Google Cloud Container Database Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.databaseViewer</code> )</p>
<p>Grants read access to see all Container Database resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.databases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.databases.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.databases.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  pluggableDatabases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  pluggableDatabases.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  pluggableDatabases.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.dbSystemAdmin" class="role-title add-link" data-text="Oracle Database@Google Cloud DB System Admin" tabindex="-1">Oracle Database@Google Cloud DB System Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p>Grants full access to manage all DB System resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  databaseCharacterSets.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.databases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.databases.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.databases.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemInitialStorageSizes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbSystems.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  dbSystems.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  dbSystems.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.dbSystems.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.dbSystems.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.dbVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.dbSystemViewer" class="role-title add-link" data-text="Oracle Database@Google Cloud DB System Viewer" tabindex="-1">Oracle Database@Google Cloud DB System Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p>
<p>Grants read access to see all DB System resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  databaseCharacterSets.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.databases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.databases.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.databases.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbSystems.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.dbSystems.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.exadbVmClusterAdmin" class="role-title add-link" data-text="Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin" tabindex="-1">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p>Grants full access to manage all Exadata Database Service on Exascale Infrastructure VM Cluster resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.dbNodes.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  minorVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.exadbVmClusterViewer" class="role-title add-link" data-text="Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer" tabindex="-1">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p>
<p>Grants read access to see all Exadata Database Service on Exascale Infrastructure VM Cluster resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.dbNodes.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  minorVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.exascaleDbStorageVaultAdmin" class="role-title add-link" data-text="Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin" tabindex="-1">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p>Grants full access to manage all Exadata Database Service on Exascale Infrastructure Storage Vault resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.dbNodes.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  create</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  delete</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  minorVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.exascaleDbStorageVaultUser" class="role-title add-link" data-text="Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User" tabindex="-1">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p>Grants permissions to use Exadata Database Service on Exascale Infrastructure Storage Vault resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.dbNodes.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  minorVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.exascaleDbStorageVaultViewer" class="role-title add-link" data-text="Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer" tabindex="-1">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p>Grants read access to see all Exadata Database Service on Exascale Infrastructure Storage Vault resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.dbNodes.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  minorVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateConnectionAdmin" class="role-title add-link" data-text="Oracle Database@Google Cloud GoldenGate Connection Admin" tabindex="-1">Oracle Database@Google Cloud GoldenGate Connection Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p>Grants full access to manage all GoldenGate Connection resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionTypes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  create</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  delete</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateConnectionAssignmentAdmin" class="role-title add-link" data-text="Oracle Database@Google Cloud GoldenGate Connection Assignment Admin" tabindex="-1">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p>Grants full access to manage all GoldenGate Connection Assignment resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  test</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateConnectionAssignmentViewer" class="role-title add-link" data-text="Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer" tabindex="-1">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p>Grants read access to see all GoldenGate Connection Assignment resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateConnectionViewer" class="role-title add-link" data-text="Oracle Database@Google Cloud GoldenGate Connection Viewer" tabindex="-1">Oracle Database@Google Cloud GoldenGate Connection Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionViewer</code> )</p>
<p>Grants read access to see all GoldenGate Connection resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateConnectionsUser" class="role-title add-link" data-text="Oracle Database@Google GoldenGate Connections User" tabindex="-1">Oracle Database@Google GoldenGate Connections User</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionsUser</code> )</p>
<p>Grants use access to GoldenGate Connections resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateDeploymentAdmin" class="role-title add-link" data-text="Oracle Database@Google Cloud GoldenGate Deployment Admin" tabindex="-1">Oracle Database@Google Cloud GoldenGate Deployment Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p>Grants full access to manage all GoldenGate Deployment resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentEnvironments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentTypes.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentVersions.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  create</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  delete</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  start</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  stop</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateDeploymentViewer" class="role-title add-link" data-text="Oracle Database@Google Cloud GoldenGate Deployment Viewer" tabindex="-1">Oracle Database@Google Cloud GoldenGate Deployment Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p>Grants read access to see all GoldenGate Deployment resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateDeploymentsUser" class="role-title add-link" data-text="Oracle Database@Google GoldenGate Deployments User" tabindex="-1">Oracle Database@Google GoldenGate Deployments User</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p>Grants use access to GoldenGate Deployments resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.networkAdmin" class="role-title add-link" data-text="Oracle Database@Google Network Admin" tabindex="-1">Oracle Database@Google Network Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p>Grants full access to manage all ODB Network and ODB Subnet resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.odbNetworks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.odbNetworks.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  odbSubnets.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  odbSubnets.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.odbSubnets.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.odbSubnets.use</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.odbNetworkAdmin" class="role-title add-link" data-text="Oracle Database@Google ODB Network Admin" tabindex="-1">Oracle Database@Google ODB Network Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p>
<p>Grants full access to manage all ODB Network resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.odbNetworks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.odbNetworks.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.odbNetworkViewer" class="role-title add-link" data-text="Oracle Database@Google ODB Network Viewer" tabindex="-1">Oracle Database@Google ODB Network Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.odbNetworkViewer</code> )</p>
<p>Grants read access to see all ODB Network resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.odbNetworks.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.odbSubnetAdmin" class="role-title add-link" data-text="Oracle Database@Google ODB Subnet Admin" tabindex="-1">Oracle Database@Google ODB Subnet Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p>
<p>Grants full access to manage all ODB Subnet resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  odbSubnets.  create</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  odbSubnets.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.odbSubnets.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></li>
<li><code dir="ltr" translate="no">oracledatabase.odbSubnets.use</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.odbSubnetUser" class="role-title add-link" data-text="Oracle Database@Google ODB Subnet User" tabindex="-1">Oracle Database@Google ODB Subnet User</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.odbSubnetUser</code> )</p>
<p>Grants use access to ODB Subnet resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.odbSubnetViewer" class="role-title add-link" data-text="Oracle Database@Google ODB Subnet Viewer" tabindex="-1">Oracle Database@Google ODB Subnet Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.odbSubnetViewer</code> )</p>
<p>Grants read access to see all ODB Subnet resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.pluggableDatabaseViewer" class="role-title add-link" data-text="Oracle Database@Google Cloud Pluggable Database Viewer" tabindex="-1">Oracle Database@Google Cloud Pluggable Database Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  oracledatabase.pluggableDatabaseViewer</code> )</p>
<p>Grants read access to see all Pluggable Database resources.</p></td>
<td><p><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.locations.get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  pluggableDatabases.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oracledatabase.  pluggableDatabases.  get</code></li>
<li><code dir="ltr" translate="no">oracledatabase.  pluggableDatabases.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Oracle Database@Google Cloud permissions

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
<td><h4 id="oracledatabase.autonomousDatabaseBackups.create" class="permission-name add-link" data-text="oracledatabase.autonomousDatabaseBackups.create" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.autonomousDatabaseBackups.delete" class="permission-name add-link" data-text="oracledatabase.autonomousDatabaseBackups.delete" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.autonomousDatabaseBackups.get" class="permission-name add-link" data-text="oracledatabase.autonomousDatabaseBackups.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.autonomousDatabaseBackups.list" class="permission-name add-link" data-text="oracledatabase.autonomousDatabaseBackups.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseBackups.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.autonomousDatabaseCharacterSets.list" class="permission-name add-link" data-text="oracledatabase.autonomousDatabaseCharacterSets.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabaseCharacterSets.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.autonomousDatabases.create" class="permission-name add-link" data-text="oracledatabase.autonomousDatabases.create" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.autonomousDatabases.delete" class="permission-name add-link" data-text="oracledatabase.autonomousDatabases.delete" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.autonomousDatabases.failover" class="permission-name add-link" data-text="oracledatabase.autonomousDatabases.failover" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  failover</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.autonomousDatabases.generateWallet" class="permission-name add-link" data-text="oracledatabase.autonomousDatabases.generateWallet" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  generateWallet</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.autonomousDatabases.get" class="permission-name add-link" data-text="oracledatabase.autonomousDatabases.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.autonomousDatabases.list" class="permission-name add-link" data-text="oracledatabase.autonomousDatabases.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.autonomousDatabases.restart" class="permission-name add-link" data-text="oracledatabase.autonomousDatabases.restart" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  restart</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.autonomousDatabases.restore" class="permission-name add-link" data-text="oracledatabase.autonomousDatabases.restore" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  restore</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.autonomousDatabases.start" class="permission-name add-link" data-text="oracledatabase.autonomousDatabases.start" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  start</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.autonomousDatabases.stop" class="permission-name add-link" data-text="oracledatabase.autonomousDatabases.stop" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  stop</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.autonomousDatabases.switchover" class="permission-name add-link" data-text="oracledatabase.autonomousDatabases.switchover" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  switchover</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.autonomousDatabases.update" class="permission-name add-link" data-text="oracledatabase.autonomousDatabases.update" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDatabases.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.autonomousDbVersions.list" class="permission-name add-link" data-text="oracledatabase.autonomousDbVersions.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  autonomousDbVersions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.cloudExadataInfrastructures.create" class="permission-name add-link" data-text="oracledatabase.cloudExadataInfrastructures.create" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.cloudExadataInfrastructures.delete" class="permission-name add-link" data-text="oracledatabase.cloudExadataInfrastructures.delete" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.cloudExadataInfrastructures.get" class="permission-name add-link" data-text="oracledatabase.cloudExadataInfrastructures.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.cloudExadataInfrastructures.list" class="permission-name add-link" data-text="oracledatabase.cloudExadataInfrastructures.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.cloudExadataInfrastructures.update" class="permission-name add-link" data-text="oracledatabase.cloudExadataInfrastructures.update" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.cloudExadataInfrastructures.use" class="permission-name add-link" data-text="oracledatabase.cloudExadataInfrastructures.use" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  cloudExadataInfrastructures.  use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.cloudVmClusters.create" class="permission-name add-link" data-text="oracledatabase.cloudVmClusters.create" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.cloudVmClusters.delete" class="permission-name add-link" data-text="oracledatabase.cloudVmClusters.delete" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.cloudVmClusters.get" class="permission-name add-link" data-text="oracledatabase.cloudVmClusters.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.cloudVmClusters.list" class="permission-name add-link" data-text="oracledatabase.cloudVmClusters.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.cloudVmClusters.update" class="permission-name add-link" data-text="oracledatabase.cloudVmClusters.update" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  cloudVmClusters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.databaseCharacterSets.list" class="permission-name add-link" data-text="oracledatabase.databaseCharacterSets.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  databaseCharacterSets.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.databases.get" class="permission-name add-link" data-text="oracledatabase.databases.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.databases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.databases.list" class="permission-name add-link" data-text="oracledatabase.databases.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.databases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.dbNodes.list" class="permission-name add-link" data-text="oracledatabase.dbNodes.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.dbNodes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.dbServers.list" class="permission-name add-link" data-text="oracledatabase.dbServers.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.dbServers.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.dbSystemInitialStorageSizes.list" class="permission-name add-link" data-text="oracledatabase.dbSystemInitialStorageSizes.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  dbSystemInitialStorageSizes.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.dbSystemShapes.list" class="permission-name add-link" data-text="oracledatabase.dbSystemShapes.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  dbSystemShapes.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.dbSystems.create" class="permission-name add-link" data-text="oracledatabase.dbSystems.create" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  dbSystems.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.dbSystems.delete" class="permission-name add-link" data-text="oracledatabase.dbSystems.delete" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  dbSystems.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.dbSystems.get" class="permission-name add-link" data-text="oracledatabase.dbSystems.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.dbSystems.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.dbSystems.list" class="permission-name add-link" data-text="oracledatabase.dbSystems.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.dbSystems.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.dbVersions.list" class="permission-name add-link" data-text="oracledatabase.dbVersions.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.dbVersions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.entitlements.list" class="permission-name add-link" data-text="oracledatabase.entitlements.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  entitlements.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.pluggableDatabaseViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.exadbVmClusters.create" class="permission-name add-link" data-text="oracledatabase.exadbVmClusters.create" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.exadbVmClusters.delete" class="permission-name add-link" data-text="oracledatabase.exadbVmClusters.delete" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.exadbVmClusters.get" class="permission-name add-link" data-text="oracledatabase.exadbVmClusters.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.exadbVmClusters.list" class="permission-name add-link" data-text="oracledatabase.exadbVmClusters.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.exadbVmClusters.update" class="permission-name add-link" data-text="oracledatabase.exadbVmClusters.update" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  exadbVmClusters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.exascaleDbStorageVaults.create" class="permission-name add-link" data-text="oracledatabase.exascaleDbStorageVaults.create" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.exascaleDbStorageVaults.delete" class="permission-name add-link" data-text="oracledatabase.exascaleDbStorageVaults.delete" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.exascaleDbStorageVaults.get" class="permission-name add-link" data-text="oracledatabase.exascaleDbStorageVaults.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.exascaleDbStorageVaults.list" class="permission-name add-link" data-text="oracledatabase.exascaleDbStorageVaults.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.exascaleDbStorageVaults.use" class="permission-name add-link" data-text="oracledatabase.exascaleDbStorageVaults.use" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  exascaleDbStorageVaults.  use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.giVersions.list" class="permission-name add-link" data-text="oracledatabase.giVersions.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.giVersions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateConnectionAssignments.create" class="permission-name add-link" data-text="oracledatabase.goldenGateConnectionAssignments.create" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateConnectionAssignments.delete" class="permission-name add-link" data-text="oracledatabase.goldenGateConnectionAssignments.delete" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateConnectionAssignments.get" class="permission-name add-link" data-text="oracledatabase.goldenGateConnectionAssignments.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateConnectionAssignments.list" class="permission-name add-link" data-text="oracledatabase.goldenGateConnectionAssignments.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateConnectionAssignments.test" class="permission-name add-link" data-text="oracledatabase.goldenGateConnectionAssignments.test" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionAssignments.  test</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateConnectionTypes.list" class="permission-name add-link" data-text="oracledatabase.goldenGateConnectionTypes.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateConnectionTypes.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateConnections.create" class="permission-name add-link" data-text="oracledatabase.goldenGateConnections.create" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateConnections.delete" class="permission-name add-link" data-text="oracledatabase.goldenGateConnections.delete" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateConnections.get" class="permission-name add-link" data-text="oracledatabase.goldenGateConnections.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionsUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateConnections.list" class="permission-name add-link" data-text="oracledatabase.goldenGateConnections.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionsUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateConnections.use" class="permission-name add-link" data-text="oracledatabase.goldenGateConnections.use" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateConnections.  use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionsUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateDeploymentEnvironments.list" class="permission-name add-link" data-text="oracledatabase.goldenGateDeploymentEnvironments.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentEnvironments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateDeploymentTypes.list" class="permission-name add-link" data-text="oracledatabase.goldenGateDeploymentTypes.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentTypes.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateDeploymentVersions.list" class="permission-name add-link" data-text="oracledatabase.goldenGateDeploymentVersions.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateDeploymentVersions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateDeployments.create" class="permission-name add-link" data-text="oracledatabase.goldenGateDeployments.create" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateDeployments.delete" class="permission-name add-link" data-text="oracledatabase.goldenGateDeployments.delete" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateDeployments.get" class="permission-name add-link" data-text="oracledatabase.goldenGateDeployments.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentsUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateDeployments.list" class="permission-name add-link" data-text="oracledatabase.goldenGateDeployments.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentsUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateDeployments.start" class="permission-name add-link" data-text="oracledatabase.goldenGateDeployments.start" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  start</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.goldenGateDeployments.stop" class="permission-name add-link" data-text="oracledatabase.goldenGateDeployments.stop" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  stop</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.goldenGateDeployments.use" class="permission-name add-link" data-text="oracledatabase.goldenGateDeployments.use" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  goldenGateDeployments.  use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentsUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.locations.get" class="permission-name add-link" data-text="oracledatabase.locations.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.pluggableDatabaseViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.locations.list" class="permission-name add-link" data-text="oracledatabase.locations.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.pluggableDatabaseViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.minorVersions.list" class="permission-name add-link" data-text="oracledatabase.minorVersions.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  minorVersions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.odbNetworks.create" class="permission-name add-link" data-text="oracledatabase.odbNetworks.create" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.odbNetworks.delete" class="permission-name add-link" data-text="oracledatabase.odbNetworks.delete" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.odbNetworks.get" class="permission-name add-link" data-text="oracledatabase.odbNetworks.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.odbNetworks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.odbNetworks.list" class="permission-name add-link" data-text="oracledatabase.odbNetworks.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.odbSubnets.create" class="permission-name add-link" data-text="oracledatabase.odbSubnets.create" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  odbSubnets.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.odbSubnets.delete" class="permission-name add-link" data-text="oracledatabase.odbSubnets.delete" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  odbSubnets.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.odbSubnets.get" class="permission-name add-link" data-text="oracledatabase.odbSubnets.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.odbSubnets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.odbSubnets.list" class="permission-name add-link" data-text="oracledatabase.odbSubnets.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.odbSubnets.use" class="permission-name add-link" data-text="oracledatabase.odbSubnets.use" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.odbSubnets.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.operations.cancel" class="permission-name add-link" data-text="oracledatabase.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.operations.delete" class="permission-name add-link" data-text="oracledatabase.operations.delete" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.operations.get" class="permission-name add-link" data-text="oracledatabase.operations.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.pluggableDatabaseViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.operations.list" class="permission-name add-link" data-text="oracledatabase.operations.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.pluggableDatabaseViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.pluggableDatabases.get" class="permission-name add-link" data-text="oracledatabase.pluggableDatabases.get" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  pluggableDatabases.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.pluggableDatabaseViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oracledatabase.pluggableDatabases.list" class="permission-name add-link" data-text="oracledatabase.pluggableDatabases.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  pluggableDatabases.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.pluggableDatabaseViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oracledatabase.systemVersions.list" class="permission-name add-link" data-text="oracledatabase.systemVersions.list" tabindex="-1"><code dir="ltr" translate="no">oracledatabase.  systemVersions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oracledatabase.cloudVmClusterAdmin</code> )</p></td>
</tr>
</tbody>
</table>
