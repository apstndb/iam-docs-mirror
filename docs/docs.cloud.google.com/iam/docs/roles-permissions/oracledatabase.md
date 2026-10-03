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
<td>Oracle Database@Google Cloud admin
<p>( <code>roles/ oracledatabase.admin</code> )</p>
<p>Grants full access to manage all Oracle Database resources.</p></td>
<td><p><code>oracledatabase. autonomousDatabaseBackups.*</code></p>
<ul>
<li><code>oracledatabase. autonomousDatabaseBackups. clone</code></li>
<li><code>oracledatabase. autonomousDatabaseBackups. create</code></li>
<li><code>oracledatabase. autonomousDatabaseBackups. delete</code></li>
<li><code>oracledatabase. autonomousDatabaseBackups. get</code></li>
<li><code>oracledatabase. autonomousDatabaseBackups. list</code></li>
</ul>
<p><code>oracledatabase. autonomousDatabaseCharacterSets. list</code></p>
<p><code>oracledatabase. autonomousDatabases.*</code></p>
<ul>
<li><code>oracledatabase. autonomousDatabases. clone</code></li>
<li><code>oracledatabase. autonomousDatabases. create</code></li>
<li><code>oracledatabase. autonomousDatabases. delete</code></li>
<li><code>oracledatabase. autonomousDatabases. failover</code></li>
<li><code>oracledatabase. autonomousDatabases. generateWallet</code></li>
<li><code>oracledatabase. autonomousDatabases. get</code></li>
<li><code>oracledatabase. autonomousDatabases. list</code></li>
<li><code>oracledatabase. autonomousDatabases. listRefreshableClones</code></li>
<li><code>oracledatabase. autonomousDatabases. refresh</code></li>
<li><code>oracledatabase. autonomousDatabases. restart</code></li>
<li><code>oracledatabase. autonomousDatabases. restore</code></li>
<li><code>oracledatabase. autonomousDatabases. start</code></li>
<li><code>oracledatabase. autonomousDatabases. stop</code></li>
<li><code>oracledatabase. autonomousDatabases. switchover</code></li>
<li><code>oracledatabase. autonomousDatabases. update</code></li>
</ul>
<p><code>oracledatabase. autonomousDbVersions. list</code></p>
<p><code>oracledatabase. cloudExadataInfrastructures.*</code></p>
<ul>
<li><code>oracledatabase. cloudExadataInfrastructures. create</code></li>
<li><code>oracledatabase. cloudExadataInfrastructures. delete</code></li>
<li><code>oracledatabase. cloudExadataInfrastructures. get</code></li>
<li><code>oracledatabase. cloudExadataInfrastructures. list</code></li>
<li><code>oracledatabase. cloudExadataInfrastructures. update</code></li>
<li><code>oracledatabase. cloudExadataInfrastructures. use</code></li>
</ul>
<p><code>oracledatabase. cloudVmClusters.*</code></p>
<ul>
<li><code>oracledatabase. cloudVmClusters. create</code></li>
<li><code>oracledatabase. cloudVmClusters. delete</code></li>
<li><code>oracledatabase. cloudVmClusters. get</code></li>
<li><code>oracledatabase. cloudVmClusters. list</code></li>
<li><code>oracledatabase. cloudVmClusters. update</code></li>
</ul>
<p><code>oracledatabase. databaseCharacterSets. list</code></p>
<p><code>oracledatabase.databases.*</code></p>
<ul>
<li><code>oracledatabase.databases.get</code></li>
<li><code>oracledatabase.databases.list</code></li>
</ul>
<p><code>oracledatabase.dbNodes.list</code></p>
<p><code>oracledatabase.dbServers.list</code></p>
<p><code>oracledatabase. dbSystemComputePerformances. list</code></p>
<p><code>oracledatabase. dbSystemInitialStorageSizes. list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase.dbSystems.*</code></p>
<ul>
<li><code>oracledatabase. dbSystems. create</code></li>
<li><code>oracledatabase. dbSystems. delete</code></li>
<li><code>oracledatabase.dbSystems.get</code></li>
<li><code>oracledatabase.dbSystems.list</code></li>
<li><code>oracledatabase. dbSystems. update</code></li>
</ul>
<p><code>oracledatabase.dbVersions.list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. exadbVmClusters.*</code></p>
<ul>
<li><code>oracledatabase. exadbVmClusters. create</code></li>
<li><code>oracledatabase. exadbVmClusters. delete</code></li>
<li><code>oracledatabase. exadbVmClusters. get</code></li>
<li><code>oracledatabase. exadbVmClusters. list</code></li>
<li><code>oracledatabase. exadbVmClusters. update</code></li>
</ul>
<p><code>oracledatabase. exascaleDbStorageVaults.*</code></p>
<ul>
<li><code>oracledatabase. exascaleDbStorageVaults. create</code></li>
<li><code>oracledatabase. exascaleDbStorageVaults. delete</code></li>
<li><code>oracledatabase. exascaleDbStorageVaults. get</code></li>
<li><code>oracledatabase. exascaleDbStorageVaults. list</code></li>
<li><code>oracledatabase. exascaleDbStorageVaults. update</code></li>
<li><code>oracledatabase. exascaleDbStorageVaults. use</code></li>
</ul>
<p><code>oracledatabase. flexComponents. list</code></p>
<p><code>oracledatabase.giVersions.list</code></p>
<p><code>oracledatabase. goldenGateConnectionAssignments.*</code></p>
<ul>
<li><code>oracledatabase. goldenGateConnectionAssignments. create</code></li>
<li><code>oracledatabase. goldenGateConnectionAssignments. delete</code></li>
<li><code>oracledatabase. goldenGateConnectionAssignments. get</code></li>
<li><code>oracledatabase. goldenGateConnectionAssignments. list</code></li>
<li><code>oracledatabase. goldenGateConnectionAssignments. test</code></li>
<li><code>oracledatabase. goldenGateConnectionAssignments. update</code></li>
</ul>
<p><code>oracledatabase. goldenGateConnectionTypes. list</code></p>
<p><code>oracledatabase. goldenGateConnections.*</code></p>
<ul>
<li><code>oracledatabase. goldenGateConnections. create</code></li>
<li><code>oracledatabase. goldenGateConnections. delete</code></li>
<li><code>oracledatabase. goldenGateConnections. get</code></li>
<li><code>oracledatabase. goldenGateConnections. list</code></li>
<li><code>oracledatabase. goldenGateConnections. update</code></li>
<li><code>oracledatabase. goldenGateConnections. use</code></li>
</ul>
<p><code>oracledatabase. goldenGateDeploymentEnvironments. list</code></p>
<p><code>oracledatabase. goldenGateDeploymentTypes. list</code></p>
<p><code>oracledatabase. goldenGateDeploymentVersions. list</code></p>
<p><code>oracledatabase. goldenGateDeployments.*</code></p>
<ul>
<li><code>oracledatabase. goldenGateDeployments. create</code></li>
<li><code>oracledatabase. goldenGateDeployments. delete</code></li>
<li><code>oracledatabase. goldenGateDeployments. get</code></li>
<li><code>oracledatabase. goldenGateDeployments. list</code></li>
<li><code>oracledatabase. goldenGateDeployments. start</code></li>
<li><code>oracledatabase. goldenGateDeployments. stop</code></li>
<li><code>oracledatabase. goldenGateDeployments. update</code></li>
<li><code>oracledatabase. goldenGateDeployments. use</code></li>
</ul>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase. minorVersions. list</code></p>
<p><code>oracledatabase.odbNetworks.*</code></p>
<ul>
<li><code>oracledatabase. odbNetworks. create</code></li>
<li><code>oracledatabase. odbNetworks. delete</code></li>
<li><code>oracledatabase.odbNetworks.get</code></li>
<li><code>oracledatabase. odbNetworks. list</code></li>
<li><code>oracledatabase. odbNetworks. update</code></li>
</ul>
<p><code>oracledatabase.odbSubnets.*</code></p>
<ul>
<li><code>oracledatabase. odbSubnets. create</code></li>
<li><code>oracledatabase. odbSubnets. delete</code></li>
<li><code>oracledatabase.odbSubnets.get</code></li>
<li><code>oracledatabase.odbSubnets.list</code></li>
<li><code>oracledatabase. odbSubnets. update</code></li>
<li><code>oracledatabase.odbSubnets.use</code></li>
</ul>
<p><code>oracledatabase.operations.*</code></p>
<ul>
<li><code>oracledatabase. operations. cancel</code></li>
<li><code>oracledatabase. operations. delete</code></li>
<li><code>oracledatabase.operations.get</code></li>
<li><code>oracledatabase.operations.list</code></li>
</ul>
<p><code>oracledatabase. systemVersions. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google Cloud viewer
<p>( <code>roles/ oracledatabase.viewer</code> )</p>
<p>Grants view access to all Oracle Database resources.</p></td>
<td><p><code>oracledatabase. autonomousDatabaseBackups. get</code></p>
<p><code>oracledatabase. autonomousDatabaseBackups. list</code></p>
<p><code>oracledatabase. autonomousDatabaseCharacterSets. list</code></p>
<p><code>oracledatabase. autonomousDatabases. get</code></p>
<p><code>oracledatabase. autonomousDatabases. list</code></p>
<p><code>oracledatabase. autonomousDatabases. listRefreshableClones</code></p>
<p><code>oracledatabase. autonomousDbVersions. list</code></p>
<p><code>oracledatabase. cloudExadataInfrastructures. get</code></p>
<p><code>oracledatabase. cloudExadataInfrastructures. list</code></p>
<p><code>oracledatabase. cloudVmClusters. get</code></p>
<p><code>oracledatabase. cloudVmClusters. list</code></p>
<p><code>oracledatabase. databaseCharacterSets. list</code></p>
<p><code>oracledatabase.databases.*</code></p>
<ul>
<li><code>oracledatabase.databases.get</code></li>
<li><code>oracledatabase.databases.list</code></li>
</ul>
<p><code>oracledatabase.dbNodes.list</code></p>
<p><code>oracledatabase.dbServers.list</code></p>
<p><code>oracledatabase. dbSystemComputePerformances. list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase.dbSystems.get</code></p>
<p><code>oracledatabase.dbSystems.list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. exadbVmClusters. get</code></p>
<p><code>oracledatabase. exadbVmClusters. list</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. get</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. list</code></p>
<p><code>oracledatabase. flexComponents. list</code></p>
<p><code>oracledatabase.giVersions.list</code></p>
<p><code>oracledatabase. goldenGateConnectionAssignments. get</code></p>
<p><code>oracledatabase. goldenGateConnectionAssignments. list</code></p>
<p><code>oracledatabase. goldenGateConnections. get</code></p>
<p><code>oracledatabase. goldenGateConnections. list</code></p>
<p><code>oracledatabase. goldenGateDeployments. get</code></p>
<p><code>oracledatabase. goldenGateDeployments. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase. minorVersions. list</code></p>
<p><code>oracledatabase.odbNetworks.get</code></p>
<p><code>oracledatabase. odbNetworks. list</code></p>
<p><code>oracledatabase.odbSubnets.get</code></p>
<p><code>oracledatabase.odbSubnets.list</code></p>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>oracledatabase. pluggableDatabases.*</code></p>
<ul>
<li><code>oracledatabase. pluggableDatabases. get</code></li>
<li><code>oracledatabase. pluggableDatabases. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google Cloud Autonomous Database Admin
<p>( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p>Grants full access to manage all Autonomous Database resources.</p></td>
<td><p><code>oracledatabase. autonomousDatabaseBackups.*</code></p>
<ul>
<li><code>oracledatabase. autonomousDatabaseBackups. clone</code></li>
<li><code>oracledatabase. autonomousDatabaseBackups. create</code></li>
<li><code>oracledatabase. autonomousDatabaseBackups. delete</code></li>
<li><code>oracledatabase. autonomousDatabaseBackups. get</code></li>
<li><code>oracledatabase. autonomousDatabaseBackups. list</code></li>
</ul>
<p><code>oracledatabase. autonomousDatabaseCharacterSets. list</code></p>
<p><code>oracledatabase. autonomousDatabases.*</code></p>
<ul>
<li><code>oracledatabase. autonomousDatabases. clone</code></li>
<li><code>oracledatabase. autonomousDatabases. create</code></li>
<li><code>oracledatabase. autonomousDatabases. delete</code></li>
<li><code>oracledatabase. autonomousDatabases. failover</code></li>
<li><code>oracledatabase. autonomousDatabases. generateWallet</code></li>
<li><code>oracledatabase. autonomousDatabases. get</code></li>
<li><code>oracledatabase. autonomousDatabases. list</code></li>
<li><code>oracledatabase. autonomousDatabases. listRefreshableClones</code></li>
<li><code>oracledatabase. autonomousDatabases. refresh</code></li>
<li><code>oracledatabase. autonomousDatabases. restart</code></li>
<li><code>oracledatabase. autonomousDatabases. restore</code></li>
<li><code>oracledatabase. autonomousDatabases. start</code></li>
<li><code>oracledatabase. autonomousDatabases. stop</code></li>
<li><code>oracledatabase. autonomousDatabases. switchover</code></li>
<li><code>oracledatabase. autonomousDatabases. update</code></li>
</ul>
<p><code>oracledatabase. autonomousDbVersions. list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.odbSubnets.get</code></p>
<p><code>oracledatabase.odbSubnets.list</code></p>
<p><code>oracledatabase.odbSubnets.use</code></p>
<p><code>oracledatabase.operations.*</code></p>
<ul>
<li><code>oracledatabase. operations. cancel</code></li>
<li><code>oracledatabase. operations. delete</code></li>
<li><code>oracledatabase.operations.get</code></li>
<li><code>oracledatabase.operations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google Cloud Autonomous Database Viewer
<p>( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p>Grants read access to see all Autonomous Database resources.</p></td>
<td><p><code>oracledatabase. autonomousDatabaseBackups. get</code></p>
<p><code>oracledatabase. autonomousDatabaseBackups. list</code></p>
<p><code>oracledatabase. autonomousDatabaseCharacterSets. list</code></p>
<p><code>oracledatabase. autonomousDatabases. get</code></p>
<p><code>oracledatabase. autonomousDatabases. list</code></p>
<p><code>oracledatabase. autonomousDatabases. listRefreshableClones</code></p>
<p><code>oracledatabase. autonomousDbVersions. list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google Cloud Exadata Infrastructure Admin
<p>( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p>Grants full access to manage all Exadata Infrastructure resources.</p></td>
<td><p><code>oracledatabase. cloudExadataInfrastructures. create</code></p>
<p><code>oracledatabase. cloudExadataInfrastructures. delete</code></p>
<p><code>oracledatabase. cloudExadataInfrastructures. get</code></p>
<p><code>oracledatabase. cloudExadataInfrastructures. list</code></p>
<p><code>oracledatabase. cloudExadataInfrastructures. update</code></p>
<p><code>oracledatabase.dbServers.list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. flexComponents. list</code></p>
<p><code>oracledatabase.giVersions.list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.*</code></p>
<ul>
<li><code>oracledatabase. operations. cancel</code></li>
<li><code>oracledatabase. operations. delete</code></li>
<li><code>oracledatabase.operations.get</code></li>
<li><code>oracledatabase.operations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google Cloud Exadata Infrastructure User
<p>( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p>Grants user access to use all Exadata Infrastructure resources.</p></td>
<td><p><code>oracledatabase. cloudExadataInfrastructures. get</code></p>
<p><code>oracledatabase. cloudExadataInfrastructures. list</code></p>
<p><code>oracledatabase. cloudExadataInfrastructures. use</code></p>
<p><code>oracledatabase.dbServers.list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. flexComponents. list</code></p>
<p><code>oracledatabase.giVersions.list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google Cloud Exadata Infrastructure Viewer
<p>( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p>Grants read access to see all Exadata Infrastructure resources.</p></td>
<td><p><code>oracledatabase. cloudExadataInfrastructures. get</code></p>
<p><code>oracledatabase. cloudExadataInfrastructures. list</code></p>
<p><code>oracledatabase.dbServers.list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. flexComponents. list</code></p>
<p><code>oracledatabase.giVersions.list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google Cloud VM Cluster Admin
<p>( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p>Grants full access to manage all VM Cluster resources.</p></td>
<td><p><code>oracledatabase. cloudExadataInfrastructures. list</code></p>
<p><code>oracledatabase. cloudExadataInfrastructures. use</code></p>
<p><code>oracledatabase. cloudVmClusters.*</code></p>
<ul>
<li><code>oracledatabase. cloudVmClusters. create</code></li>
<li><code>oracledatabase. cloudVmClusters. delete</code></li>
<li><code>oracledatabase. cloudVmClusters. get</code></li>
<li><code>oracledatabase. cloudVmClusters. list</code></li>
<li><code>oracledatabase. cloudVmClusters. update</code></li>
</ul>
<p><code>oracledatabase.dbNodes.list</code></p>
<p><code>oracledatabase.dbServers.list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. get</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. list</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. use</code></p>
<p><code>oracledatabase.giVersions.list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase. minorVersions. list</code></p>
<p><code>oracledatabase.odbSubnets.get</code></p>
<p><code>oracledatabase.odbSubnets.list</code></p>
<p><code>oracledatabase.odbSubnets.use</code></p>
<p><code>oracledatabase.operations.*</code></p>
<ul>
<li><code>oracledatabase. operations. cancel</code></li>
<li><code>oracledatabase. operations. delete</code></li>
<li><code>oracledatabase.operations.get</code></li>
<li><code>oracledatabase.operations.list</code></li>
</ul>
<p><code>oracledatabase. systemVersions. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google Cloud VM Cluster Viewer
<p>( <code>roles/ oracledatabase.cloudVmClusterViewer</code> )</p>
<p>Grants read access to see all VM Cluster resources.</p></td>
<td><p><code>oracledatabase. cloudVmClusters. get</code></p>
<p><code>oracledatabase. cloudVmClusters. list</code></p>
<p><code>oracledatabase.dbNodes.list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google Cloud Container Database Viewer
<p>( <code>roles/ oracledatabase.databaseViewer</code> )</p>
<p>Grants read access to see all Container Database resources.</p></td>
<td><p><code>oracledatabase.databases.*</code></p>
<ul>
<li><code>oracledatabase.databases.get</code></li>
<li><code>oracledatabase.databases.list</code></li>
</ul>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>oracledatabase. pluggableDatabases.*</code></p>
<ul>
<li><code>oracledatabase. pluggableDatabases. get</code></li>
<li><code>oracledatabase. pluggableDatabases. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google Cloud DB System Admin
<p>( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p>Grants full access to manage all DB System resources.</p></td>
<td><p><code>oracledatabase. databaseCharacterSets. list</code></p>
<p><code>oracledatabase.databases.*</code></p>
<ul>
<li><code>oracledatabase.databases.get</code></li>
<li><code>oracledatabase.databases.list</code></li>
</ul>
<p><code>oracledatabase. dbSystemComputePerformances. list</code></p>
<p><code>oracledatabase. dbSystemInitialStorageSizes. list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase.dbSystems.*</code></p>
<ul>
<li><code>oracledatabase. dbSystems. create</code></li>
<li><code>oracledatabase. dbSystems. delete</code></li>
<li><code>oracledatabase.dbSystems.get</code></li>
<li><code>oracledatabase.dbSystems.list</code></li>
<li><code>oracledatabase. dbSystems. update</code></li>
</ul>
<p><code>oracledatabase.dbVersions.list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.*</code></p>
<ul>
<li><code>oracledatabase. operations. cancel</code></li>
<li><code>oracledatabase. operations. delete</code></li>
<li><code>oracledatabase.operations.get</code></li>
<li><code>oracledatabase.operations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google Cloud DB System Viewer
<p>( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p>Grants read access to see all DB System resources.</p></td>
<td><p><code>oracledatabase. databaseCharacterSets. list</code></p>
<p><code>oracledatabase.databases.*</code></p>
<ul>
<li><code>oracledatabase.databases.get</code></li>
<li><code>oracledatabase.databases.list</code></li>
</ul>
<p><code>oracledatabase. dbSystemComputePerformances. list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase.dbSystems.get</code></p>
<p><code>oracledatabase.dbSystems.list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin
<p>( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p>Grants full access to manage all Exadata Database Service on Exascale Infrastructure VM Cluster resources.</p></td>
<td><p><code>oracledatabase.dbNodes.list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. exadbVmClusters.*</code></p>
<ul>
<li><code>oracledatabase. exadbVmClusters. create</code></li>
<li><code>oracledatabase. exadbVmClusters. delete</code></li>
<li><code>oracledatabase. exadbVmClusters. get</code></li>
<li><code>oracledatabase. exadbVmClusters. list</code></li>
<li><code>oracledatabase. exadbVmClusters. update</code></li>
</ul>
<p><code>oracledatabase.giVersions.list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase. minorVersions. list</code></p>
<p><code>oracledatabase.operations.*</code></p>
<ul>
<li><code>oracledatabase. operations. cancel</code></li>
<li><code>oracledatabase. operations. delete</code></li>
<li><code>oracledatabase.operations.get</code></li>
<li><code>oracledatabase.operations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer
<p>( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p>Grants read access to see all Exadata Database Service on Exascale Infrastructure VM Cluster resources.</p></td>
<td><p><code>oracledatabase.dbNodes.list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. exadbVmClusters. get</code></p>
<p><code>oracledatabase. exadbVmClusters. list</code></p>
<p><code>oracledatabase.giVersions.list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase. minorVersions. list</code></p>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin
<p>( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p>Grants full access to manage all Exadata Database Service on Exascale Infrastructure Storage Vault resources.</p></td>
<td><p><code>oracledatabase.dbNodes.list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. create</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. delete</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. get</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. list</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. update</code></p>
<p><code>oracledatabase.giVersions.list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase. minorVersions. list</code></p>
<p><code>oracledatabase.operations.*</code></p>
<ul>
<li><code>oracledatabase. operations. cancel</code></li>
<li><code>oracledatabase. operations. delete</code></li>
<li><code>oracledatabase.operations.get</code></li>
<li><code>oracledatabase.operations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User
<p>( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p>Grants permissions to use Exadata Database Service on Exascale Infrastructure Storage Vault resources.</p></td>
<td><p><code>oracledatabase.dbNodes.list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. get</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. list</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. use</code></p>
<p><code>oracledatabase.giVersions.list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase. minorVersions. list</code></p>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer
<p>( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p>Grants read access to see all Exadata Database Service on Exascale Infrastructure Storage Vault resources.</p></td>
<td><p><code>oracledatabase.dbNodes.list</code></p>
<p><code>oracledatabase. dbSystemShapes. list</code></p>
<p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. get</code></p>
<p><code>oracledatabase. exascaleDbStorageVaults. list</code></p>
<p><code>oracledatabase.giVersions.list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase. minorVersions. list</code></p>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google Cloud GoldenGate Connection Admin
<p>( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p>Grants full access to manage all GoldenGate Connection resources.</p></td>
<td><p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. goldenGateConnectionTypes. list</code></p>
<p><code>oracledatabase. goldenGateConnections. create</code></p>
<p><code>oracledatabase. goldenGateConnections. delete</code></p>
<p><code>oracledatabase. goldenGateConnections. get</code></p>
<p><code>oracledatabase. goldenGateConnections. list</code></p>
<p><code>oracledatabase. goldenGateConnections. update</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.odbSubnets.get</code></p>
<p><code>oracledatabase.odbSubnets.list</code></p>
<p><code>oracledatabase.odbSubnets.use</code></p>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google Cloud GoldenGate Connection Assignment Admin
<p>( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p>Grants full access to manage all GoldenGate Connection Assignment resources.</p></td>
<td><p><code>oracledatabase. goldenGateConnectionAssignments.*</code></p>
<ul>
<li><code>oracledatabase. goldenGateConnectionAssignments. create</code></li>
<li><code>oracledatabase. goldenGateConnectionAssignments. delete</code></li>
<li><code>oracledatabase. goldenGateConnectionAssignments. get</code></li>
<li><code>oracledatabase. goldenGateConnectionAssignments. list</code></li>
<li><code>oracledatabase. goldenGateConnectionAssignments. test</code></li>
<li><code>oracledatabase. goldenGateConnectionAssignments. update</code></li>
</ul>
<p><code>oracledatabase. goldenGateConnections. get</code></p>
<p><code>oracledatabase. goldenGateConnections. list</code></p>
<p><code>oracledatabase. goldenGateConnections. use</code></p>
<p><code>oracledatabase. goldenGateDeployments. get</code></p>
<p><code>oracledatabase. goldenGateDeployments. list</code></p>
<p><code>oracledatabase. goldenGateDeployments. use</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer
<p>( <code>roles/ oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p>Grants read access to see all GoldenGate Connection Assignment resources.</p></td>
<td><p><code>oracledatabase. goldenGateConnectionAssignments. get</code></p>
<p><code>oracledatabase. goldenGateConnectionAssignments. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google Cloud GoldenGate Connection Viewer
<p>( <code>roles/ oracledatabase.goldenGateConnectionViewer</code> )</p>
<p>Grants read access to see all GoldenGate Connection resources.</p></td>
<td><p><code>oracledatabase. goldenGateConnections. get</code></p>
<p><code>oracledatabase. goldenGateConnections. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google GoldenGate Connections User
<p>( <code>roles/ oracledatabase.goldenGateConnectionsUser</code> )</p>
<p>Grants use access to GoldenGate Connections resources.</p></td>
<td><p><code>oracledatabase. goldenGateConnections. get</code></p>
<p><code>oracledatabase. goldenGateConnections. list</code></p>
<p><code>oracledatabase. goldenGateConnections. use</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google Cloud GoldenGate Deployment Admin
<p>( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p>Grants full access to manage all GoldenGate Deployment resources.</p></td>
<td><p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase. goldenGateDeploymentEnvironments. list</code></p>
<p><code>oracledatabase. goldenGateDeploymentTypes. list</code></p>
<p><code>oracledatabase. goldenGateDeploymentVersions. list</code></p>
<p><code>oracledatabase. goldenGateDeployments. create</code></p>
<p><code>oracledatabase. goldenGateDeployments. delete</code></p>
<p><code>oracledatabase. goldenGateDeployments. get</code></p>
<p><code>oracledatabase. goldenGateDeployments. list</code></p>
<p><code>oracledatabase. goldenGateDeployments. start</code></p>
<p><code>oracledatabase. goldenGateDeployments. stop</code></p>
<p><code>oracledatabase. goldenGateDeployments. update</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.odbSubnets.get</code></p>
<p><code>oracledatabase.odbSubnets.list</code></p>
<p><code>oracledatabase.odbSubnets.use</code></p>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google Cloud GoldenGate Deployment Viewer
<p>( <code>roles/ oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p>Grants read access to see all GoldenGate Deployment resources.</p></td>
<td><p><code>oracledatabase. goldenGateDeployments. get</code></p>
<p><code>oracledatabase. goldenGateDeployments. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google GoldenGate Deployments User
<p>( <code>roles/ oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p>Grants use access to GoldenGate Deployments resources.</p></td>
<td><p><code>oracledatabase. goldenGateDeployments. get</code></p>
<p><code>oracledatabase. goldenGateDeployments. list</code></p>
<p><code>oracledatabase. goldenGateDeployments. use</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google Network Admin
<p>( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p>Grants full access to manage all ODB Network and ODB Subnet resources.</p></td>
<td><p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.odbNetworks.*</code></p>
<ul>
<li><code>oracledatabase. odbNetworks. create</code></li>
<li><code>oracledatabase. odbNetworks. delete</code></li>
<li><code>oracledatabase.odbNetworks.get</code></li>
<li><code>oracledatabase. odbNetworks. list</code></li>
<li><code>oracledatabase. odbNetworks. update</code></li>
</ul>
<p><code>oracledatabase.odbSubnets.*</code></p>
<ul>
<li><code>oracledatabase. odbSubnets. create</code></li>
<li><code>oracledatabase. odbSubnets. delete</code></li>
<li><code>oracledatabase.odbSubnets.get</code></li>
<li><code>oracledatabase.odbSubnets.list</code></li>
<li><code>oracledatabase. odbSubnets. update</code></li>
<li><code>oracledatabase.odbSubnets.use</code></li>
</ul>
<p><code>oracledatabase.operations.*</code></p>
<ul>
<li><code>oracledatabase. operations. cancel</code></li>
<li><code>oracledatabase. operations. delete</code></li>
<li><code>oracledatabase.operations.get</code></li>
<li><code>oracledatabase.operations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google ODB Network Admin
<p>( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p>Grants full access to manage all ODB Network resources.</p></td>
<td><p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.odbNetworks.*</code></p>
<ul>
<li><code>oracledatabase. odbNetworks. create</code></li>
<li><code>oracledatabase. odbNetworks. delete</code></li>
<li><code>oracledatabase.odbNetworks.get</code></li>
<li><code>oracledatabase. odbNetworks. list</code></li>
<li><code>oracledatabase. odbNetworks. update</code></li>
</ul>
<p><code>oracledatabase.operations.*</code></p>
<ul>
<li><code>oracledatabase. operations. cancel</code></li>
<li><code>oracledatabase. operations. delete</code></li>
<li><code>oracledatabase.operations.get</code></li>
<li><code>oracledatabase.operations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google ODB Network Viewer
<p>( <code>roles/ oracledatabase.odbNetworkViewer</code> )</p>
<p>Grants read access to see all ODB Network resources.</p></td>
<td><p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.odbNetworks.get</code></p>
<p><code>oracledatabase. odbNetworks. list</code></p>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google ODB Subnet Admin
<p>( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p>Grants full access to manage all ODB Subnet resources.</p></td>
<td><p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.odbSubnets.*</code></p>
<ul>
<li><code>oracledatabase. odbSubnets. create</code></li>
<li><code>oracledatabase. odbSubnets. delete</code></li>
<li><code>oracledatabase.odbSubnets.get</code></li>
<li><code>oracledatabase.odbSubnets.list</code></li>
<li><code>oracledatabase. odbSubnets. update</code></li>
<li><code>oracledatabase.odbSubnets.use</code></li>
</ul>
<p><code>oracledatabase.operations.*</code></p>
<ul>
<li><code>oracledatabase. operations. cancel</code></li>
<li><code>oracledatabase. operations. delete</code></li>
<li><code>oracledatabase.operations.get</code></li>
<li><code>oracledatabase.operations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google ODB Subnet User
<p>( <code>roles/ oracledatabase.odbSubnetUser</code> )</p>
<p>Grants use access to ODB Subnet resources.</p></td>
<td><p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.odbSubnets.get</code></p>
<p><code>oracledatabase.odbSubnets.list</code></p>
<p><code>oracledatabase.odbSubnets.use</code></p>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Oracle Database@Google ODB Subnet Viewer
<p>( <code>roles/ oracledatabase.odbSubnetViewer</code> )</p>
<p>Grants read access to see all ODB Subnet resources.</p></td>
<td><p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.odbSubnets.get</code></p>
<p><code>oracledatabase.odbSubnets.list</code></p>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Oracle Database@Google Cloud Pluggable Database Viewer
<p>( <code>roles/ oracledatabase.pluggableDatabaseViewer</code> )</p>
<p>Grants read access to see all Pluggable Database resources.</p></td>
<td><p><code>oracledatabase. entitlements. list</code></p>
<p><code>oracledatabase.locations.*</code></p>
<ul>
<li><code>oracledatabase.locations.get</code></li>
<li><code>oracledatabase.locations.list</code></li>
</ul>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>oracledatabase. pluggableDatabases.*</code></p>
<ul>
<li><code>oracledatabase. pluggableDatabases. get</code></li>
<li><code>oracledatabase. pluggableDatabases. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td><code>oracledatabase. autonomousDatabaseBackups. clone</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. autonomousDatabaseBackups. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. autonomousDatabaseBackups. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. autonomousDatabaseBackups. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. autonomousDatabaseBackups. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. autonomousDatabaseCharacterSets. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. autonomousDatabases. clone</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. autonomousDatabases. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. autonomousDatabases. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. autonomousDatabases. failover</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. autonomousDatabases. generateWallet</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. autonomousDatabases. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. autonomousDatabases. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. autonomousDatabases. listRefreshableClones</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. autonomousDatabases. refresh</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. autonomousDatabases. restart</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. autonomousDatabases. restore</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. autonomousDatabases. start</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. autonomousDatabases. stop</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. autonomousDatabases. switchover</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. autonomousDatabases. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. autonomousDbVersions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. cloudExadataInfrastructures. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. cloudExadataInfrastructures. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. cloudExadataInfrastructures. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. cloudExadataInfrastructures. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. cloudExadataInfrastructures. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. cloudExadataInfrastructures. use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. cloudVmClusters. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. cloudVmClusters. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. cloudVmClusters. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code>roles/ oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. cloudVmClusters. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code>roles/ oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. cloudVmClusters. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. databaseCharacterSets. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase.databases.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code>roles/ oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase.databases.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code>roles/ oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase.dbNodes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code>roles/ oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase.dbServers.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. dbSystemComputePerformances. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. dbSystemInitialStorageSizes. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. dbSystemShapes. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. dbSystems. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. dbSystems. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase.dbSystems.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase.dbSystems.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. dbSystems. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase.dbVersions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. entitlements. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code>roles/ oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code>roles/ oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code>roles/ oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code>roles/ oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code>roles/ oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code>roles/ oracledatabase.pluggableDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. exadbVmClusters. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. exadbVmClusters. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. exadbVmClusters. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. exadbVmClusters. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. exadbVmClusters. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. exascaleDbStorageVaults. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. exascaleDbStorageVaults. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. exascaleDbStorageVaults. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. exascaleDbStorageVaults. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. exascaleDbStorageVaults. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. exascaleDbStorageVaults. use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. flexComponents. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase.giVersions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. goldenGateConnectionAssignments. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. goldenGateConnectionAssignments. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. goldenGateConnectionAssignments. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. goldenGateConnectionAssignments. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. goldenGateConnectionAssignments. test</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. goldenGateConnectionAssignments. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. goldenGateConnectionTypes. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. goldenGateConnections. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. goldenGateConnections. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. goldenGateConnections. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code>roles/ oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. goldenGateConnections. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code>roles/ oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. goldenGateConnections. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. goldenGateConnections. use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code>roles/ oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. goldenGateDeploymentEnvironments. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. goldenGateDeploymentTypes. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. goldenGateDeploymentVersions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. goldenGateDeployments. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. goldenGateDeployments. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. goldenGateDeployments. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code>roles/ oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code>roles/ oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. goldenGateDeployments. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code>roles/ oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code>roles/ oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. goldenGateDeployments. start</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. goldenGateDeployments. stop</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. goldenGateDeployments. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. goldenGateDeployments. use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code>roles/ oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code>roles/ oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code>roles/ oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code>roles/ oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code>roles/ oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code>roles/ oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code>roles/ oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code>roles/ oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code>roles/ oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code>roles/ oracledatabase.pluggableDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code>roles/ oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code>roles/ oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code>roles/ oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code>roles/ oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code>roles/ oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code>roles/ oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code>roles/ oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code>roles/ oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code>roles/ oracledatabase.pluggableDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. minorVersions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. odbNetworks. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>oracledatabase. odbNetworks. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase.odbNetworks.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code>roles/ oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>oracledatabase. odbNetworks. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code>roles/ oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. odbNetworks. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. odbSubnets. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. odbSubnets. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase.odbSubnets.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code>roles/ oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code>roles/ oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>oracledatabase.odbSubnets.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code>roles/ oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code>roles/ oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>oracledatabase. odbSubnets. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase.odbSubnets.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code>roles/ oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>oracledatabase. operations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. operations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code>roles/ oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code>roles/ oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code>roles/ oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code>roles/ oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code>roles/ oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code>roles/ oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code>roles/ oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code>roles/ oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code>roles/ oracledatabase.pluggableDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>oracledatabase.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code>roles/ oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code>roles/ oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code>roles/ oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code>roles/ oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code>roles/ oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code>roles/ oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code>roles/ oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code>roles/ oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code>roles/ oracledatabase.pluggableDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>oracledatabase. pluggableDatabases. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code>roles/ oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code>roles/ oracledatabase.pluggableDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>oracledatabase. pluggableDatabases. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code>roles/ oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code>roles/ oracledatabase.pluggableDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>oracledatabase. systemVersions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
