---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/datamigration
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration
title: Database Migration Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Database Migration Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Database Migration Service roles

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
<td><h4 id="datamigration.admin" class="role-title add-link" data-text="Database Migration Admin" tabindex="-1">Database Migration Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p>Full access to all resources of Database Migration.</p></td>
<td><p><code dir="ltr" translate="no">cloudaicompanion.  entitlements.  get</code></p>
<p><code dir="ltr" translate="no">datamigration.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionprofiles.  create</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionprofiles.  delete</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionprofiles.  get</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionprofiles.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionprofiles.  list</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionprofiles.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionprofiles.  update</code></li>
<li><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  apply</code></li>
<li><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  commit</code></li>
<li><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  convert</code></li>
<li><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  create</code></li>
<li><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  delete</code></li>
<li><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  get</code></li>
<li><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  list</code></li>
<li><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  rollback</code></li>
<li><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  seed</code></li>
<li><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  update</code></li>
<li><code dir="ltr" translate="no">datamigration.  locations.  fetchStaticIps</code></li>
<li><code dir="ltr" translate="no">datamigration.locations.get</code></li>
<li><code dir="ltr" translate="no">datamigration.locations.list</code></li>
<li><code dir="ltr" translate="no">datamigration.  mappingrules.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datamigration.  mappingrules.  import</code></li>
<li><code dir="ltr" translate="no">datamigration.  mappingrules.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  create</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  delete</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  demoteDestination</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  fetchSourceObjects</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  generateSshScript</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  generateTcpProxyScript</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  get</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  list</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  promote</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  restart</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  resume</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  start</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  stop</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  update</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationjobs.  verify</code></li>
<li><code dir="ltr" translate="no">datamigration.objects.get</code></li>
<li><code dir="ltr" translate="no">datamigration.objects.list</code></li>
<li><code dir="ltr" translate="no">datamigration.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">datamigration.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">datamigration.operations.get</code></li>
<li><code dir="ltr" translate="no">datamigration.operations.list</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateconnections.  create</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateconnections.  delete</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateconnections.  get</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateconnections.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateconnections.  list</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateconnections.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.editor" class="role-title add-link" data-text="Datamigration Editor" tabindex="-1">Datamigration Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p>Editor role for datamigration</p></td>
<td><p><code dir="ltr" translate="no">cloudaicompanion.  entitlements.  get</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionprofiles.  create</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionprofiles.  delete</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionprofiles.  get</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionprofiles.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionprofiles.  list</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionprofiles.  update</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  apply</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  commit</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  convert</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  create</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  delete</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  get</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  list</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  rollback</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  seed</code></p>
<p><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  update</code></p>
<p><code dir="ltr" translate="no">datamigration.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datamigration.  locations.  fetchStaticIps</code></li>
<li><code dir="ltr" translate="no">datamigration.locations.get</code></li>
<li><code dir="ltr" translate="no">datamigration.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datamigration.  mappingrules.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  mappingrules.  import</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationJobs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationJobs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  create</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  delete</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  demoteDestination</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  fetchSourceObjects</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  generateSshScript</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  generateTcpProxyScript</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  get</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  list</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  promote</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  restart</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  resume</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  start</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  stop</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  update</code></p>
<p><code dir="ltr" translate="no">datamigration.  migrationjobs.  verify</code></p>
<p><code dir="ltr" translate="no">datamigration.objects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datamigration.objects.get</code></li>
<li><code dir="ltr" translate="no">datamigration.objects.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datamigration.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datamigration.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">datamigration.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">datamigration.operations.get</code></li>
<li><code dir="ltr" translate="no">datamigration.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datamigration.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datamigration.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datamigration.  privateconnections.  create</code></p>
<p><code dir="ltr" translate="no">datamigration.  privateconnections.  delete</code></p>
<p><code dir="ltr" translate="no">datamigration.  privateconnections.  get</code></p>
<p><code dir="ltr" translate="no">datamigration.  privateconnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datamigration.  privateconnections.  list</code></p>
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
<td><h4 id="datamigration.serviceAgent" class="role-title add-link" data-text="Database Migration Service Agent" tabindex="-1">Database Migration Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</p>
<p>Gives Cloud Database Migration service account access to Cloud SQL resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">alloydb.clusters.create</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.delete</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  generateClientCertificate</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.get</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.import</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.list</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.update</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.connect</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.create</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.delete</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.executeSql</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.get</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.list</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.update</code></p>
<p><code dir="ltr" translate="no">alloydb.operations.get</code></p>
<p><code dir="ltr" translate="no">alloydb.operations.list</code></p>
<p><code dir="ltr" translate="no">alloydb.users.login</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.delete</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.connect</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.create</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.delete</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  demoteMaster</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.executeSql</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.export</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.import</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.login</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.migrate</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  promoteReplica</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.restart</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  startReplica</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.stopReplica</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.update</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.use</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.create</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.delete</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.networkAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.networks.addPeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">compute.networks.removePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routes.get</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.serviceAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  update</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">logging.logServiceIndexes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServices.list</code></p>
<p><code dir="ltr" translate="no">logging.logs.list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">storage.folders.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Database Migration Service permissions

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
<td><h4 id="datamigration.connectionProfiles.createTagBinding" class="permission-name add-link" data-text="datamigration.connectionProfiles.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">datamigration.  connectionProfiles.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.connectionProfiles.deleteTagBinding" class="permission-name add-link" data-text="datamigration.connectionProfiles.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">datamigration.  connectionProfiles.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.connectionProfiles.listEffectiveTags" class="permission-name add-link" data-text="datamigration.connectionProfiles.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.connectionProfiles.listTagBindings" class="permission-name add-link" data-text="datamigration.connectionProfiles.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.connectionprofiles.create" class="permission-name add-link" data-text="datamigration.connectionprofiles.create" tabindex="-1"><code dir="ltr" translate="no">datamigration.  connectionprofiles.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.connectionprofiles.delete" class="permission-name add-link" data-text="datamigration.connectionprofiles.delete" tabindex="-1"><code dir="ltr" translate="no">datamigration.  connectionprofiles.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.connectionprofiles.get" class="permission-name add-link" data-text="datamigration.connectionprofiles.get" tabindex="-1"><code dir="ltr" translate="no">datamigration.  connectionprofiles.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.connectionprofiles.getIamPolicy" class="permission-name add-link" data-text="datamigration.connectionprofiles.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datamigration.  connectionprofiles.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.connectionprofiles.list" class="permission-name add-link" data-text="datamigration.connectionprofiles.list" tabindex="-1"><code dir="ltr" translate="no">datamigration.  connectionprofiles.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.connectionprofiles.setIamPolicy" class="permission-name add-link" data-text="datamigration.connectionprofiles.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datamigration.  connectionprofiles.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.connectionprofiles.update" class="permission-name add-link" data-text="datamigration.connectionprofiles.update" tabindex="-1"><code dir="ltr" translate="no">datamigration.  connectionprofiles.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.conversionworkspaces.apply" class="permission-name add-link" data-text="datamigration.conversionworkspaces.apply" tabindex="-1"><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  apply</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.conversionworkspaces.commit" class="permission-name add-link" data-text="datamigration.conversionworkspaces.commit" tabindex="-1"><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  commit</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.conversionworkspaces.convert" class="permission-name add-link" data-text="datamigration.conversionworkspaces.convert" tabindex="-1"><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  convert</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.conversionworkspaces.create" class="permission-name add-link" data-text="datamigration.conversionworkspaces.create" tabindex="-1"><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.conversionworkspaces.delete" class="permission-name add-link" data-text="datamigration.conversionworkspaces.delete" tabindex="-1"><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.conversionworkspaces.get" class="permission-name add-link" data-text="datamigration.conversionworkspaces.get" tabindex="-1"><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.conversionworkspaces.getIamPolicy" class="permission-name add-link" data-text="datamigration.conversionworkspaces.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.conversionworkspaces.list" class="permission-name add-link" data-text="datamigration.conversionworkspaces.list" tabindex="-1"><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.conversionworkspaces.rollback" class="permission-name add-link" data-text="datamigration.conversionworkspaces.rollback" tabindex="-1"><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  rollback</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.conversionworkspaces.seed" class="permission-name add-link" data-text="datamigration.conversionworkspaces.seed" tabindex="-1"><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  seed</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.conversionworkspaces.setIamPolicy" class="permission-name add-link" data-text="datamigration.conversionworkspaces.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.conversionworkspaces.update" class="permission-name add-link" data-text="datamigration.conversionworkspaces.update" tabindex="-1"><code dir="ltr" translate="no">datamigration.  conversionworkspaces.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.locations.fetchStaticIps" class="permission-name add-link" data-text="datamigration.locations.fetchStaticIps" tabindex="-1"><code dir="ltr" translate="no">datamigration.  locations.  fetchStaticIps</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.locations.get" class="permission-name add-link" data-text="datamigration.locations.get" tabindex="-1"><code dir="ltr" translate="no">datamigration.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.locations.list" class="permission-name add-link" data-text="datamigration.locations.list" tabindex="-1"><code dir="ltr" translate="no">datamigration.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.mappingrules.getIamPolicy" class="permission-name add-link" data-text="datamigration.mappingrules.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datamigration.  mappingrules.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.mappingrules.import" class="permission-name add-link" data-text="datamigration.mappingrules.import" tabindex="-1"><code dir="ltr" translate="no">datamigration.  mappingrules.  import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.mappingrules.setIamPolicy" class="permission-name add-link" data-text="datamigration.mappingrules.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datamigration.  mappingrules.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.migrationJobs.createTagBinding" class="permission-name add-link" data-text="datamigration.migrationJobs.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationJobs.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.migrationJobs.deleteTagBinding" class="permission-name add-link" data-text="datamigration.migrationJobs.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationJobs.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.migrationJobs.listEffectiveTags" class="permission-name add-link" data-text="datamigration.migrationJobs.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationJobs.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.migrationJobs.listTagBindings" class="permission-name add-link" data-text="datamigration.migrationJobs.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationJobs.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.migrationjobs.create" class="permission-name add-link" data-text="datamigration.migrationjobs.create" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.migrationjobs.delete" class="permission-name add-link" data-text="datamigration.migrationjobs.delete" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.migrationjobs.demoteDestination" class="permission-name add-link" data-text="datamigration.migrationjobs.demoteDestination" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  demoteDestination</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.migrationjobs.fetchSourceObjects" class="permission-name add-link" data-text="datamigration.migrationjobs.fetchSourceObjects" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  fetchSourceObjects</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.migrationjobs.generateSshScript" class="permission-name add-link" data-text="datamigration.migrationjobs.generateSshScript" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  generateSshScript</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.migrationjobs.generateTcpProxyScript" class="permission-name add-link" data-text="datamigration.migrationjobs.generateTcpProxyScript" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  generateTcpProxyScript</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.migrationjobs.get" class="permission-name add-link" data-text="datamigration.migrationjobs.get" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.migrationjobs.getIamPolicy" class="permission-name add-link" data-text="datamigration.migrationjobs.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.migrationjobs.list" class="permission-name add-link" data-text="datamigration.migrationjobs.list" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.migrationjobs.promote" class="permission-name add-link" data-text="datamigration.migrationjobs.promote" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  promote</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.migrationjobs.restart" class="permission-name add-link" data-text="datamigration.migrationjobs.restart" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  restart</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.migrationjobs.resume" class="permission-name add-link" data-text="datamigration.migrationjobs.resume" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  resume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.migrationjobs.setIamPolicy" class="permission-name add-link" data-text="datamigration.migrationjobs.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.migrationjobs.start" class="permission-name add-link" data-text="datamigration.migrationjobs.start" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  start</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.migrationjobs.stop" class="permission-name add-link" data-text="datamigration.migrationjobs.stop" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  stop</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.migrationjobs.update" class="permission-name add-link" data-text="datamigration.migrationjobs.update" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.migrationjobs.verify" class="permission-name add-link" data-text="datamigration.migrationjobs.verify" tabindex="-1"><code dir="ltr" translate="no">datamigration.  migrationjobs.  verify</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.objects.get" class="permission-name add-link" data-text="datamigration.objects.get" tabindex="-1"><code dir="ltr" translate="no">datamigration.objects.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.objects.list" class="permission-name add-link" data-text="datamigration.objects.list" tabindex="-1"><code dir="ltr" translate="no">datamigration.objects.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.operations.cancel" class="permission-name add-link" data-text="datamigration.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">datamigration.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.operations.delete" class="permission-name add-link" data-text="datamigration.operations.delete" tabindex="-1"><code dir="ltr" translate="no">datamigration.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.operations.get" class="permission-name add-link" data-text="datamigration.operations.get" tabindex="-1"><code dir="ltr" translate="no">datamigration.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.operations.list" class="permission-name add-link" data-text="datamigration.operations.list" tabindex="-1"><code dir="ltr" translate="no">datamigration.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.privateConnections.createTagBinding" class="permission-name add-link" data-text="datamigration.privateConnections.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">datamigration.  privateConnections.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.privateConnections.deleteTagBinding" class="permission-name add-link" data-text="datamigration.privateConnections.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">datamigration.  privateConnections.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.privateConnections.listEffectiveTags" class="permission-name add-link" data-text="datamigration.privateConnections.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">datamigration.  privateConnections.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.privateConnections.listTagBindings" class="permission-name add-link" data-text="datamigration.privateConnections.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">datamigration.  privateConnections.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.privateconnections.create" class="permission-name add-link" data-text="datamigration.privateconnections.create" tabindex="-1"><code dir="ltr" translate="no">datamigration.  privateconnections.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.privateconnections.delete" class="permission-name add-link" data-text="datamigration.privateconnections.delete" tabindex="-1"><code dir="ltr" translate="no">datamigration.  privateconnections.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.privateconnections.get" class="permission-name add-link" data-text="datamigration.privateconnections.get" tabindex="-1"><code dir="ltr" translate="no">datamigration.  privateconnections.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.privateconnections.getIamPolicy" class="permission-name add-link" data-text="datamigration.privateconnections.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datamigration.  privateconnections.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datamigration.privateconnections.list" class="permission-name add-link" data-text="datamigration.privateconnections.list" tabindex="-1"><code dir="ltr" translate="no">datamigration.  privateconnections.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datamigration.privateconnections.setIamPolicy" class="permission-name add-link" data-text="datamigration.privateconnections.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datamigration.  privateconnections.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
</tbody>
</table>
