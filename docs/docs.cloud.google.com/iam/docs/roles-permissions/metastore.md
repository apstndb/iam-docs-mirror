---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/metastore
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/metastore
title: Dataproc Metastore roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Dataproc Metastore. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Dataproc Metastore roles

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
<td>Dataproc Metastore Admin
<p>( <code>roles/ metastore.admin</code> )</p>
<p>Full access to all Dataproc Metastore resources.</p></td>
<td><p><code>metastore.backups.*</code></p>
<ul>
<li><code>metastore.backups.create</code></li>
<li><code>metastore.backups.delete</code></li>
<li><code>metastore.backups.get</code></li>
<li><code>metastore.backups.getIamPolicy</code></li>
<li><code>metastore.backups.list</code></li>
<li><code>metastore.backups.setIamPolicy</code></li>
<li><code>metastore.backups.use</code></li>
</ul>
<p><code>metastore.federations.*</code></p>
<ul>
<li><code>metastore.federations.create</code></li>
<li><code>metastore. federations. createTagBinding</code></li>
<li><code>metastore.federations.delete</code></li>
<li><code>metastore. federations. deleteTagBinding</code></li>
<li><code>metastore.federations.get</code></li>
<li><code>metastore. federations. getIamPolicy</code></li>
<li><code>metastore.federations.list</code></li>
<li><code>metastore. federations. listEffectiveTags</code></li>
<li><code>metastore. federations. listTagBindings</code></li>
<li><code>metastore. federations. setIamPolicy</code></li>
<li><code>metastore.federations.update</code></li>
<li><code>metastore.federations.use</code></li>
</ul>
<p><code>metastore.imports.*</code></p>
<ul>
<li><code>metastore.imports.create</code></li>
<li><code>metastore.imports.get</code></li>
<li><code>metastore.imports.list</code></li>
<li><code>metastore.imports.update</code></li>
</ul>
<p><code>metastore.locations.*</code></p>
<ul>
<li><code>metastore.locations.get</code></li>
<li><code>metastore.locations.list</code></li>
</ul>
<p><code>metastore.migrations.*</code></p>
<ul>
<li><code>metastore.migrations.cancel</code></li>
<li><code>metastore.migrations.complete</code></li>
<li><code>metastore.migrations.delete</code></li>
<li><code>metastore.migrations.get</code></li>
<li><code>metastore.migrations.list</code></li>
<li><code>metastore.migrations.start</code></li>
</ul>
<p><code>metastore.operations.*</code></p>
<ul>
<li><code>metastore.operations.cancel</code></li>
<li><code>metastore.operations.delete</code></li>
<li><code>metastore.operations.get</code></li>
<li><code>metastore.operations.list</code></li>
</ul>
<p><code>metastore.services.create</code></p>
<p><code>metastore. services. createTagBinding</code></p>
<p><code>metastore.services.delete</code></p>
<p><code>metastore. services. deleteTagBinding</code></p>
<p><code>metastore.services.export</code></p>
<p><code>metastore.services.get</code></p>
<p><code>metastore. services. getIamPolicy</code></p>
<p><code>metastore.services.list</code></p>
<p><code>metastore. services. listEffectiveTags</code></p>
<p><code>metastore. services. listTagBindings</code></p>
<p><code>metastore.services.restore</code></p>
<p><code>metastore. services. setIamPolicy</code></p>
<p><code>metastore.services.update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataproc Metastore Editor
<p>( <code>roles/ metastore.editor</code> )</p>
<p>Read and write access to all Dataproc Metastore resources.</p></td>
<td><p><code>metastore.backups.create</code></p>
<p><code>metastore.backups.delete</code></p>
<p><code>metastore.backups.get</code></p>
<p><code>metastore.backups.list</code></p>
<p><code>metastore.backups.use</code></p>
<p><code>metastore.federations.create</code></p>
<p><code>metastore.federations.delete</code></p>
<p><code>metastore.federations.get</code></p>
<p><code>metastore.federations.list</code></p>
<p><code>metastore. federations. listEffectiveTags</code></p>
<p><code>metastore. federations. listTagBindings</code></p>
<p><code>metastore.federations.update</code></p>
<p><code>metastore.imports.*</code></p>
<ul>
<li><code>metastore.imports.create</code></li>
<li><code>metastore.imports.get</code></li>
<li><code>metastore.imports.list</code></li>
<li><code>metastore.imports.update</code></li>
</ul>
<p><code>metastore.locations.*</code></p>
<ul>
<li><code>metastore.locations.get</code></li>
<li><code>metastore.locations.list</code></li>
</ul>
<p><code>metastore.migrations.*</code></p>
<ul>
<li><code>metastore.migrations.cancel</code></li>
<li><code>metastore.migrations.complete</code></li>
<li><code>metastore.migrations.delete</code></li>
<li><code>metastore.migrations.get</code></li>
<li><code>metastore.migrations.list</code></li>
<li><code>metastore.migrations.start</code></li>
</ul>
<p><code>metastore.operations.*</code></p>
<ul>
<li><code>metastore.operations.cancel</code></li>
<li><code>metastore.operations.delete</code></li>
<li><code>metastore.operations.get</code></li>
<li><code>metastore.operations.list</code></li>
</ul>
<p><code>metastore.services.create</code></p>
<p><code>metastore. services. createTagBinding</code></p>
<p><code>metastore.services.delete</code></p>
<p><code>metastore. services. deleteTagBinding</code></p>
<p><code>metastore.services.export</code></p>
<p><code>metastore.services.get</code></p>
<p><code>metastore. services. getIamPolicy</code></p>
<p><code>metastore.services.list</code></p>
<p><code>metastore. services. listEffectiveTags</code></p>
<p><code>metastore. services. listTagBindings</code></p>
<p><code>metastore.services.restore</code></p>
<p><code>metastore.services.update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Dataproc Metastore Viewer
<p>( <code>roles/ metastore.viewer</code> )</p>
<p>Viewer role for Dataproc Metastore</p></td>
<td><p><code>metastore.backups.get</code></p>
<p><code>metastore.backups.getIamPolicy</code></p>
<p><code>metastore.backups.list</code></p>
<p><code>metastore.backups.use</code></p>
<p><code>metastore.databases.get</code></p>
<p><code>metastore. databases. getIamPolicy</code></p>
<p><code>metastore.databases.list</code></p>
<p><code>metastore.federations.get</code></p>
<p><code>metastore. federations. getIamPolicy</code></p>
<p><code>metastore.federations.list</code></p>
<p><code>metastore. federations. listEffectiveTags</code></p>
<p><code>metastore. federations. listTagBindings</code></p>
<p><code>metastore.imports.get</code></p>
<p><code>metastore.imports.list</code></p>
<p><code>metastore.locations.*</code></p>
<ul>
<li><code>metastore.locations.get</code></li>
<li><code>metastore.locations.list</code></li>
</ul>
<p><code>metastore.migrations.get</code></p>
<p><code>metastore.migrations.list</code></p>
<p><code>metastore.operations.get</code></p>
<p><code>metastore.operations.list</code></p>
<p><code>metastore.services.export</code></p>
<p><code>metastore.services.get</code></p>
<p><code>metastore. services. getIamPolicy</code></p>
<p><code>metastore.services.list</code></p>
<p><code>metastore. services. listEffectiveTags</code></p>
<p><code>metastore. services. listTagBindings</code></p>
<p><code>metastore.tables.get</code></p>
<p><code>metastore.tables.getIamPolicy</code></p>
<p><code>metastore.tables.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Metastore Federation Accessor
<p>( <code>roles/ metastore.federationAccessor</code> )</p>
<p>Access to the Metastore Federation resource.</p></td>
<td><p><code>metastore.federations.use</code></p></td>
</tr>
<tr class="odd">
<td>Dataproc Metastore Metadata Editor
<p>( <code>roles/ metastore.metadataEditor</code> )</p>
<p>Access to read and modify the metadata of databases and tables under those databases.</p></td>
<td><p><code>metastore.databases.create</code></p>
<p><code>metastore.databases.delete</code></p>
<p><code>metastore.databases.get</code></p>
<p><code>metastore. databases. getIamPolicy</code></p>
<p><code>metastore.databases.list</code></p>
<p><code>metastore.databases.update</code></p>
<p><code>metastore.services.get</code></p>
<p><code>metastore.services.use</code></p>
<p><code>metastore.tables.create</code></p>
<p><code>metastore.tables.delete</code></p>
<p><code>metastore.tables.get</code></p>
<p><code>metastore.tables.getIamPolicy</code></p>
<p><code>metastore.tables.list</code></p>
<p><code>metastore.tables.update</code></p></td>
</tr>
<tr class="even">
<td>Dataproc Metastore Metadata Mutate Admin
<p>( <code>roles/ metastore.metadataMutateAdmin</code> )</p>
<p>Access to mutate metadata from a Dataproc Metastore service's underlying metadata store.</p></td>
<td><p><code>metastore. services. mutateMetadata</code></p></td>
</tr>
<tr class="odd">
<td>Dataproc Metastore Metadata Operator
<p>( <code>roles/ metastore.metadataOperator</code> )</p>
<p>Read-only access to Dataproc Metastore resources with additional metadata operations permission.</p></td>
<td><p><code>metastore.backups.create</code></p>
<p><code>metastore.backups.delete</code></p>
<p><code>metastore.backups.get</code></p>
<p><code>metastore.backups.list</code></p>
<p><code>metastore.backups.use</code></p>
<p><code>metastore.imports.*</code></p>
<ul>
<li><code>metastore.imports.create</code></li>
<li><code>metastore.imports.get</code></li>
<li><code>metastore.imports.list</code></li>
<li><code>metastore.imports.update</code></li>
</ul>
<p><code>metastore.locations.*</code></p>
<ul>
<li><code>metastore.locations.get</code></li>
<li><code>metastore.locations.list</code></li>
</ul>
<p><code>metastore.operations.get</code></p>
<p><code>metastore.operations.list</code></p>
<p><code>metastore.services.export</code></p>
<p><code>metastore.services.get</code></p>
<p><code>metastore. services. getIamPolicy</code></p>
<p><code>metastore.services.list</code></p>
<p><code>metastore. services. listEffectiveTags</code></p>
<p><code>metastore. services. listTagBindings</code></p>
<p><code>metastore.services.restore</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Dataproc Metastore Data Owner
<p>( <code>roles/ metastore.metadataOwner</code> )</p>
<p>Full access to the metadata of databases and tables under those databases.</p></td>
<td><p><code>metastore.databases.*</code></p>
<ul>
<li><code>metastore.databases.create</code></li>
<li><code>metastore.databases.delete</code></li>
<li><code>metastore.databases.get</code></li>
<li><code>metastore. databases. getIamPolicy</code></li>
<li><code>metastore.databases.list</code></li>
<li><code>metastore. databases. setIamPolicy</code></li>
<li><code>metastore.databases.update</code></li>
</ul>
<p><code>metastore.services.get</code></p>
<p><code>metastore. services. getIamPolicy</code></p>
<p><code>metastore.services.list</code></p>
<p><code>metastore. services. listEffectiveTags</code></p>
<p><code>metastore. services. listTagBindings</code></p>
<p><code>metastore.services.use</code></p>
<p><code>metastore.tables.*</code></p>
<ul>
<li><code>metastore.tables.create</code></li>
<li><code>metastore.tables.delete</code></li>
<li><code>metastore.tables.get</code></li>
<li><code>metastore.tables.getIamPolicy</code></li>
<li><code>metastore.tables.list</code></li>
<li><code>metastore.tables.setIamPolicy</code></li>
<li><code>metastore.tables.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Dataproc Metastore Metadata Query Admin
<p>( <code>roles/ metastore.metadataQueryAdmin</code> )</p>
<p>Access to query metadata from a Dataproc Metastore service's underlying metadata store.</p></td>
<td><p><code>metastore. services. queryMetadata</code></p></td>
</tr>
<tr class="even">
<td>Dataproc Metastore Metadata User
<p>( <code>roles/ metastore.metadataUser</code> )</p>
<p>Access to the Dataproc Metastore gRPC endpoint</p></td>
<td><p><code>metastore.databases.get</code></p>
<p><code>metastore.databases.list</code></p>
<p><code>metastore.services.get</code></p>
<p><code>metastore.services.use</code></p></td>
</tr>
<tr class="odd">
<td>Dataproc Metastore Metadata Viewer
<p>( <code>roles/ metastore.metadataViewer</code> )</p>
<p>Access to read the metadata of databases and tables under those databases</p></td>
<td><p><code>metastore.databases.get</code></p>
<p><code>metastore. databases. getIamPolicy</code></p>
<p><code>metastore.databases.list</code></p>
<p><code>metastore.services.get</code></p>
<p><code>metastore.services.use</code></p>
<p><code>metastore.tables.get</code></p>
<p><code>metastore.tables.getIamPolicy</code></p>
<p><code>metastore.tables.list</code></p></td>
</tr>
<tr class="even">
<td>Dataproc Metastore Managed Migration Admin
<p>( <code>roles/ metastore.migrationAdmin</code> )</p>
<p>Access to Dataproc Metastore Managed Migration resources and workflow.</p></td>
<td><p><code>cloudsql.instances.connect</code></p>
<p><code>cloudsql.instances.get</code></p>
<p><code>cloudsql.instances.login</code></p>
<p><code>compute.autoscalers.create</code></p>
<p><code>compute.autoscalers.delete</code></p>
<p><code>compute.disks.create</code></p>
<p><code>compute.disks.delete</code></p>
<p><code>compute.forwardingRules.create</code></p>
<p><code>compute.forwardingRules.delete</code></p>
<p><code>compute.forwardingRules.use</code></p>
<p><code>compute. instanceGroupManagers. create</code></p>
<p><code>compute. instanceGroupManagers. delete</code></p>
<p><code>compute. instanceGroupManagers. use</code></p>
<p><code>compute.instanceGroups.delete</code></p>
<p><code>compute.instanceGroups.use</code></p>
<p><code>compute. instanceTemplates. create</code></p>
<p><code>compute. instanceTemplates. delete</code></p>
<p><code>compute.instanceTemplates.get</code></p>
<p><code>compute. instanceTemplates. useReadOnly</code></p>
<p><code>compute.instances.create</code></p>
<p><code>compute.instances.delete</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute.instances.setMetadata</code></p>
<p><code>compute.machineTypes.list</code></p>
<p><code>compute. regionBackendServices. create</code></p>
<p><code>compute. regionBackendServices. delete</code></p>
<p><code>compute. regionBackendServices. use</code></p>
<p><code>compute. regionHealthChecks. create</code></p>
<p><code>compute. regionHealthChecks. delete</code></p>
<p><code>compute.regionHealthChecks.use</code></p>
<p><code>compute. regionHealthChecks. useReadOnly</code></p>
<p><code>compute. serviceAttachments. create</code></p>
<p><code>compute. serviceAttachments. delete</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>compute.zones.list</code></p>
<p><code>datastream. connectionProfiles. create</code></p>
<p><code>datastream. connectionProfiles. delete</code></p>
<p><code>datastream.objects.*</code></p>
<ul>
<li><code>datastream.objects.get</code></li>
<li><code>datastream.objects.list</code></li>
<li><code>datastream. objects. startBackfillJob</code></li>
<li><code>datastream. objects. stopBackfillJob</code></li>
</ul>
<p><code>datastream.operations.get</code></p>
<p><code>datastream. privateConnections. create</code></p>
<p><code>datastream. privateConnections. delete</code></p>
<p><code>datastream.streams.create</code></p>
<p><code>datastream.streams.delete</code></p>
<p><code>datastream.streams.get</code></p>
<p><code>datastream.streams.update</code></p></td>
</tr>
<tr class="odd">
<td>Dataproc Metastore Viewer
<p>( <code>roles/ metastore.user</code> )</p>
<p>Read-only access to all Dataproc Metastore resources.</p></td>
<td><p><code>metastore.backups.get</code></p>
<p><code>metastore.backups.list</code></p>
<p><code>metastore.federations.get</code></p>
<p><code>metastore. federations. getIamPolicy</code></p>
<p><code>metastore.federations.list</code></p>
<p><code>metastore. federations. listEffectiveTags</code></p>
<p><code>metastore. federations. listTagBindings</code></p>
<p><code>metastore.imports.get</code></p>
<p><code>metastore.imports.list</code></p>
<p><code>metastore.locations.*</code></p>
<ul>
<li><code>metastore.locations.get</code></li>
<li><code>metastore.locations.list</code></li>
</ul>
<p><code>metastore.operations.get</code></p>
<p><code>metastore.operations.list</code></p>
<p><code>metastore.services.export</code></p>
<p><code>metastore.services.get</code></p>
<p><code>metastore. services. getIamPolicy</code></p>
<p><code>metastore.services.list</code></p>
<p><code>metastore. services. listEffectiveTags</code></p>
<p><code>metastore. services. listTagBindings</code></p>
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
<td>Dataproc Metastore Service Agent
<p>( <code>roles/ metastore.serviceAgent</code> )</p>
<p>Gives the Dataproc Metastore service account access to managed resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>compute. addresses. createInternal</code></p>
<p><code>compute. addresses. deleteInternal</code></p>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.use</code></p>
<p><code>compute.forwardingRules.create</code></p>
<p><code>compute.forwardingRules.delete</code></p>
<p><code>compute.forwardingRules.get</code></p>
<p><code>compute. forwardingRules. pscCreate</code></p>
<p><code>compute. forwardingRules. pscDelete</code></p>
<p><code>compute. globalAddresses. createInternal</code></p>
<p><code>compute. globalAddresses. deleteInternal</code></p>
<p><code>compute.globalAddresses.get</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.globalOperations.list</code></p>
<p><code>compute.networks.addPeering</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.removePeering</code></p>
<p><code>compute.networks.updatePeering</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>dns.changes.create</code></p>
<p><code>dns.changes.get</code></p>
<p><code>dns.managedZones.create</code></p>
<p><code>dns.managedZones.delete</code></p>
<p><code>dns.managedZones.get</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns. networks. bindPrivateDNSZone</code></p>
<p><code>dns. networks. targetWithPeeringZone</code></p>
<p><code>dns.resourceRecordSets.*</code></p>
<ul>
<li><code>dns.resourceRecordSets.create</code></li>
<li><code>dns.resourceRecordSets.delete</code></li>
<li><code>dns.resourceRecordSets.get</code></li>
<li><code>dns.resourceRecordSets.list</code></li>
<li><code>dns.resourceRecordSets.update</code></li>
</ul>
<p><code>metastore.databases.get</code></p>
<p><code>metastore. databases. setIamPolicy</code></p>
<p><code>metastore.databases.update</code></p>
<p><code>metastore.federations.use</code></p>
<p><code>metastore.services.get</code></p>
<p><code>metastore.tables.get</code></p>
<p><code>metastore.tables.setIamPolicy</code></p>
<p><code>metastore.tables.update</code></p>
<p><code>servicedirectory. namespaces. create</code></p>
<p><code>servicedirectory. namespaces. delete</code></p>
<p><code>servicedirectory. services. create</code></p>
<p><code>servicedirectory. services. delete</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.delete</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.update</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Dataproc Metastore permissions

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
<td><code>metastore.backups.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.backups.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.backups.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.backups.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.backups.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.backups.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.backups.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.databases.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.databases.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.databases.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataUser">Dataproc Metastore Metadata User</a> ( <code>roles/ metastore.metadataUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code>roles/ metastore.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>metastore. databases. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code>roles/ metastore.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.databases.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataUser">Dataproc Metastore Metadata User</a> ( <code>roles/ metastore.metadataUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code>roles/ metastore.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore. databases. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>metastore.databases.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>metastore.federations.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore. federations. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.federations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore. federations. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.federations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore. federations. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.federations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore. federations. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore. federations. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore. federations. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.federations.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.federations.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.federationAccessor">Metastore Federation Accessor</a> ( <code>roles/ metastore.federationAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>metastore.imports.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.imports.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.imports.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.imports.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.migrations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.migrations.complete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.migrations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.migrations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.migrations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.migrations.start</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.services.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore. services. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.services.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore. services. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.services.export</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.services.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataUser">Dataproc Metastore Metadata User</a> ( <code>roles/ metastore.metadataUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code>roles/ metastore.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>metastore. services. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.services.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore. services. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore. services. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore. services. mutateMetadata</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataMutateAdmin">Dataproc Metastore Metadata Mutate Admin</a> ( <code>roles/ metastore.metadataMutateAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore. services. queryMetadata</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataQueryAdmin">Dataproc Metastore Metadata Query Admin</a> ( <code>roles/ metastore.metadataQueryAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.services.restore</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore. services. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.services.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.services.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataUser">Dataproc Metastore Metadata User</a> ( <code>roles/ metastore.metadataUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code>roles/ metastore.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.tables.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.tables.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.tables.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code>roles/ metastore.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>metastore.tables.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code>roles/ metastore.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>metastore.tables.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataViewer">Dataproc Metastore Metadata Viewer</a> ( <code>roles/ metastore.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>metastore.tables.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>metastore.tables.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataEditor">Dataproc Metastore Metadata Editor</a> ( <code>roles/ metastore.metadataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOwner">Dataproc Metastore Data Owner</a> ( <code>roles/ metastore.metadataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
