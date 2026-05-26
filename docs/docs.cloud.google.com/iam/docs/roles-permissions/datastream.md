---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/datastream
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/datastream
title: Datastream roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Datastream. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Datastream roles

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
<td><h4 id="datastream.admin" class="role-title add-link" data-text="Datastream Admin" tabindex="-1">Datastream Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p>Full access to all Datastream resources.</p></td>
<td><p><code dir="ltr" translate="no">datastream.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  create</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  delete</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  destinationTypes</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  discover</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  get</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  list</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  listStaticServiceIps</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  sourceTypes</code></li>
<li><code dir="ltr" translate="no">datastream.  connectionProfiles.  update</code></li>
<li><code dir="ltr" translate="no">datastream.  locations.  fetchStaticIps</code></li>
<li><code dir="ltr" translate="no">datastream.locations.get</code></li>
<li><code dir="ltr" translate="no">datastream.locations.list</code></li>
<li><code dir="ltr" translate="no">datastream.objects.get</code></li>
<li><code dir="ltr" translate="no">datastream.objects.list</code></li>
<li><code dir="ltr" translate="no">datastream.  objects.  startBackfillJob</code></li>
<li><code dir="ltr" translate="no">datastream.  objects.  stopBackfillJob</code></li>
<li><code dir="ltr" translate="no">datastream.operations.cancel</code></li>
<li><code dir="ltr" translate="no">datastream.operations.delete</code></li>
<li><code dir="ltr" translate="no">datastream.operations.get</code></li>
<li><code dir="ltr" translate="no">datastream.operations.list</code></li>
<li><code dir="ltr" translate="no">datastream.  privateConnections.  create</code></li>
<li><code dir="ltr" translate="no">datastream.  privateConnections.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datastream.  privateConnections.  delete</code></li>
<li><code dir="ltr" translate="no">datastream.  privateConnections.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datastream.  privateConnections.  get</code></li>
<li><code dir="ltr" translate="no">datastream.  privateConnections.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastream.  privateConnections.  list</code></li>
<li><code dir="ltr" translate="no">datastream.  privateConnections.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datastream.  privateConnections.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">datastream.  privateConnections.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastream.routes.create</code></li>
<li><code dir="ltr" translate="no">datastream.routes.delete</code></li>
<li><code dir="ltr" translate="no">datastream.routes.get</code></li>
<li><code dir="ltr" translate="no">datastream.routes.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastream.routes.list</code></li>
<li><code dir="ltr" translate="no">datastream.routes.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastream.  streams.  computeState</code></li>
<li><code dir="ltr" translate="no">datastream.streams.create</code></li>
<li><code dir="ltr" translate="no">datastream.  streams.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datastream.streams.delete</code></li>
<li><code dir="ltr" translate="no">datastream.  streams.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datastream.streams.fetchErrors</code></li>
<li><code dir="ltr" translate="no">datastream.streams.get</code></li>
<li><code dir="ltr" translate="no">datastream.  streams.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastream.streams.list</code></li>
<li><code dir="ltr" translate="no">datastream.  streams.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datastream.  streams.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">datastream.streams.pause</code></li>
<li><code dir="ltr" translate="no">datastream.streams.resume</code></li>
<li><code dir="ltr" translate="no">datastream.  streams.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datastream.streams.start</code></li>
<li><code dir="ltr" translate="no">datastream.streams.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.viewer" class="role-title add-link" data-text="Datastream Viewer" tabindex="-1">Datastream Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p>Read-only access to all Datastream resources.</p></td>
<td><p><code dir="ltr" translate="no">datastream.  connectionProfiles.  destinationTypes</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  discover</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  get</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  list</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listStaticServiceIps</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  sourceTypes</code></p>
<p><code dir="ltr" translate="no">datastream.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastream.  locations.  fetchStaticIps</code></li>
<li><code dir="ltr" translate="no">datastream.locations.get</code></li>
<li><code dir="ltr" translate="no">datastream.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastream.objects.get</code></p>
<p><code dir="ltr" translate="no">datastream.objects.list</code></p>
<p><code dir="ltr" translate="no">datastream.operations.get</code></p>
<p><code dir="ltr" translate="no">datastream.operations.list</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  get</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  list</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.routes.get</code></p>
<p><code dir="ltr" translate="no">datastream.routes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.routes.list</code></p>
<p><code dir="ltr" translate="no">datastream.streams.fetchErrors</code></p>
<p><code dir="ltr" translate="no">datastream.streams.get</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.streams.list</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.bigqueryWriter" class="role-title add-link" data-text="Datastream Bigquery Writer" tabindex="-1">Datastream Bigquery Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p>Permissions needed for datastream to write to BigQuery.</p></td>
<td><p><code dir="ltr" translate="no">bigquery.connections.delegate</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.list</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  create</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  delete</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  destinationTypes</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  discover</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  get</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  list</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listStaticServiceIps</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  sourceTypes</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  update</code></p>
<p><code dir="ltr" translate="no">datastream.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastream.  locations.  fetchStaticIps</code></li>
<li><code dir="ltr" translate="no">datastream.locations.get</code></li>
<li><code dir="ltr" translate="no">datastream.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastream.objects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastream.objects.get</code></li>
<li><code dir="ltr" translate="no">datastream.objects.list</code></li>
<li><code dir="ltr" translate="no">datastream.  objects.  startBackfillJob</code></li>
<li><code dir="ltr" translate="no">datastream.  objects.  stopBackfillJob</code></li>
</ul>
<p><code dir="ltr" translate="no">datastream.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastream.operations.cancel</code></li>
<li><code dir="ltr" translate="no">datastream.operations.delete</code></li>
<li><code dir="ltr" translate="no">datastream.operations.get</code></li>
<li><code dir="ltr" translate="no">datastream.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  create</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  delete</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  get</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  list</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.routes.create</code></p>
<p><code dir="ltr" translate="no">datastream.routes.delete</code></p>
<p><code dir="ltr" translate="no">datastream.routes.get</code></p>
<p><code dir="ltr" translate="no">datastream.routes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.routes.list</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  computeState</code></p>
<p><code dir="ltr" translate="no">datastream.streams.create</code></p>
<p><code dir="ltr" translate="no">datastream.streams.delete</code></p>
<p><code dir="ltr" translate="no">datastream.streams.fetchErrors</code></p>
<p><code dir="ltr" translate="no">datastream.streams.get</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">datastream.streams.list</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.streams.pause</code></p>
<p><code dir="ltr" translate="no">datastream.streams.resume</code></p>
<p><code dir="ltr" translate="no">datastream.streams.start</code></p>
<p><code dir="ltr" translate="no">datastream.streams.update</code></p></td>
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
<td><h4 id="datastream.serviceAgent" class="role-title add-link" data-text="Datastream Service Agent" tabindex="-1">Datastream Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  datastream.serviceAgent</code> )</p>
<p>Grants Cloud Datastream permissions to write data in the user project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.connections.delegate</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.list</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.update</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.get</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
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
<p><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">compute.networks.removePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.routes.get</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  beginReadOnlyTransaction</code></p>
<p><code dir="ltr" translate="no">spanner.databases.getDdl</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionQuery</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  partitionRead</code></p>
<p><code dir="ltr" translate="no">spanner.databases.read</code></p>
<p><code dir="ltr" translate="no">spanner.databases.select</code></p>
<p><code dir="ltr" translate="no">spanner.databases.useDataBoost</code></p>
<p><code dir="ltr" translate="no">spanner.  databases.  useRoleBasedAccess</code></p>
<p><code dir="ltr" translate="no">spanner.sessions.create</code></p>
<p><code dir="ltr" translate="no">spanner.sessions.delete</code></p>
<p><code dir="ltr" translate="no">spanner.sessions.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Datastream permissions

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
<td><h4 id="datastream.connectionProfiles.create" class="permission-name add-link" data-text="datastream.connectionProfiles.create" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.connectionProfiles.createTagBinding" class="permission-name add-link" data-text="datastream.connectionProfiles.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.connectionProfiles.delete" class="permission-name add-link" data-text="datastream.connectionProfiles.delete" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.connectionProfiles.deleteTagBinding" class="permission-name add-link" data-text="datastream.connectionProfiles.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.connectionProfiles.destinationTypes" class="permission-name add-link" data-text="datastream.connectionProfiles.destinationTypes" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  destinationTypes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.connectionProfiles.discover" class="permission-name add-link" data-text="datastream.connectionProfiles.discover" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  discover</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.connectionProfiles.get" class="permission-name add-link" data-text="datastream.connectionProfiles.get" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.connectionProfiles.getIamPolicy" class="permission-name add-link" data-text="datastream.connectionProfiles.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.connectionProfiles.list" class="permission-name add-link" data-text="datastream.connectionProfiles.list" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.connectionProfiles.listEffectiveTags" class="permission-name add-link" data-text="datastream.connectionProfiles.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.connectionProfiles.listStaticServiceIps" class="permission-name add-link" data-text="datastream.connectionProfiles.listStaticServiceIps" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  listStaticServiceIps</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.connectionProfiles.listTagBindings" class="permission-name add-link" data-text="datastream.connectionProfiles.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.connectionProfiles.setIamPolicy" class="permission-name add-link" data-text="datastream.connectionProfiles.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.connectionProfiles.sourceTypes" class="permission-name add-link" data-text="datastream.connectionProfiles.sourceTypes" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  sourceTypes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.connectionProfiles.update" class="permission-name add-link" data-text="datastream.connectionProfiles.update" tabindex="-1"><code dir="ltr" translate="no">datastream.  connectionProfiles.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.locations.fetchStaticIps" class="permission-name add-link" data-text="datastream.locations.fetchStaticIps" tabindex="-1"><code dir="ltr" translate="no">datastream.  locations.  fetchStaticIps</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.locations.get" class="permission-name add-link" data-text="datastream.locations.get" tabindex="-1"><code dir="ltr" translate="no">datastream.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.locations.list" class="permission-name add-link" data-text="datastream.locations.list" tabindex="-1"><code dir="ltr" translate="no">datastream.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.objects.get" class="permission-name add-link" data-text="datastream.objects.get" tabindex="-1"><code dir="ltr" translate="no">datastream.objects.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.objects.list" class="permission-name add-link" data-text="datastream.objects.list" tabindex="-1"><code dir="ltr" translate="no">datastream.objects.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.objects.startBackfillJob" class="permission-name add-link" data-text="datastream.objects.startBackfillJob" tabindex="-1"><code dir="ltr" translate="no">datastream.  objects.  startBackfillJob</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.objects.stopBackfillJob" class="permission-name add-link" data-text="datastream.objects.stopBackfillJob" tabindex="-1"><code dir="ltr" translate="no">datastream.  objects.  stopBackfillJob</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.operations.cancel" class="permission-name add-link" data-text="datastream.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">datastream.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.operations.delete" class="permission-name add-link" data-text="datastream.operations.delete" tabindex="-1"><code dir="ltr" translate="no">datastream.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.operations.get" class="permission-name add-link" data-text="datastream.operations.get" tabindex="-1"><code dir="ltr" translate="no">datastream.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.operations.list" class="permission-name add-link" data-text="datastream.operations.list" tabindex="-1"><code dir="ltr" translate="no">datastream.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.privateConnections.create" class="permission-name add-link" data-text="datastream.privateConnections.create" tabindex="-1"><code dir="ltr" translate="no">datastream.  privateConnections.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.privateConnections.createTagBinding" class="permission-name add-link" data-text="datastream.privateConnections.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">datastream.  privateConnections.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.privateConnections.delete" class="permission-name add-link" data-text="datastream.privateConnections.delete" tabindex="-1"><code dir="ltr" translate="no">datastream.  privateConnections.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.privateConnections.deleteTagBinding" class="permission-name add-link" data-text="datastream.privateConnections.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">datastream.  privateConnections.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.privateConnections.get" class="permission-name add-link" data-text="datastream.privateConnections.get" tabindex="-1"><code dir="ltr" translate="no">datastream.  privateConnections.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.privateConnections.getIamPolicy" class="permission-name add-link" data-text="datastream.privateConnections.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastream.  privateConnections.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.privateConnections.list" class="permission-name add-link" data-text="datastream.privateConnections.list" tabindex="-1"><code dir="ltr" translate="no">datastream.  privateConnections.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.privateConnections.listEffectiveTags" class="permission-name add-link" data-text="datastream.privateConnections.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">datastream.  privateConnections.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.privateConnections.listTagBindings" class="permission-name add-link" data-text="datastream.privateConnections.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">datastream.  privateConnections.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.privateConnections.setIamPolicy" class="permission-name add-link" data-text="datastream.privateConnections.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastream.  privateConnections.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.routes.create" class="permission-name add-link" data-text="datastream.routes.create" tabindex="-1"><code dir="ltr" translate="no">datastream.routes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.routes.delete" class="permission-name add-link" data-text="datastream.routes.delete" tabindex="-1"><code dir="ltr" translate="no">datastream.routes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.routes.get" class="permission-name add-link" data-text="datastream.routes.get" tabindex="-1"><code dir="ltr" translate="no">datastream.routes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.routes.getIamPolicy" class="permission-name add-link" data-text="datastream.routes.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastream.routes.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.routes.list" class="permission-name add-link" data-text="datastream.routes.list" tabindex="-1"><code dir="ltr" translate="no">datastream.routes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.routes.setIamPolicy" class="permission-name add-link" data-text="datastream.routes.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastream.routes.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.streams.computeState" class="permission-name add-link" data-text="datastream.streams.computeState" tabindex="-1"><code dir="ltr" translate="no">datastream.  streams.  computeState</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.streams.create" class="permission-name add-link" data-text="datastream.streams.create" tabindex="-1"><code dir="ltr" translate="no">datastream.streams.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.streams.createTagBinding" class="permission-name add-link" data-text="datastream.streams.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">datastream.  streams.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.streams.delete" class="permission-name add-link" data-text="datastream.streams.delete" tabindex="-1"><code dir="ltr" translate="no">datastream.streams.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.streams.deleteTagBinding" class="permission-name add-link" data-text="datastream.streams.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">datastream.  streams.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.streams.fetchErrors" class="permission-name add-link" data-text="datastream.streams.fetchErrors" tabindex="-1"><code dir="ltr" translate="no">datastream.streams.fetchErrors</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.streams.get" class="permission-name add-link" data-text="datastream.streams.get" tabindex="-1"><code dir="ltr" translate="no">datastream.streams.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.streams.getIamPolicy" class="permission-name add-link" data-text="datastream.streams.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastream.  streams.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.streams.list" class="permission-name add-link" data-text="datastream.streams.list" tabindex="-1"><code dir="ltr" translate="no">datastream.streams.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.streams.listEffectiveTags" class="permission-name add-link" data-text="datastream.streams.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">datastream.  streams.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.streams.listTagBindings" class="permission-name add-link" data-text="datastream.streams.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">datastream.  streams.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.streams.pause" class="permission-name add-link" data-text="datastream.streams.pause" tabindex="-1"><code dir="ltr" translate="no">datastream.streams.pause</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.streams.resume" class="permission-name add-link" data-text="datastream.streams.resume" tabindex="-1"><code dir="ltr" translate="no">datastream.streams.resume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.streams.setIamPolicy" class="permission-name add-link" data-text="datastream.streams.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">datastream.  streams.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datastream.streams.start" class="permission-name add-link" data-text="datastream.streams.start" tabindex="-1"><code dir="ltr" translate="no">datastream.streams.start</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datastream.streams.update" class="permission-name add-link" data-text="datastream.streams.update" tabindex="-1"><code dir="ltr" translate="no">datastream.streams.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.bigqueryWriter">Datastream Bigquery Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datastream.bigqueryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.migrationAdmin">Dataproc Metastore Managed Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.migrationAdmin</code> )</p></td>
</tr>
</tbody>
</table>
