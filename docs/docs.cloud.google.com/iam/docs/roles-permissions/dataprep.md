---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/dataprep
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep
title: Dataprep by Trifacta roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Dataprep by Trifacta. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Dataprep by Trifacta roles

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
<td><h4 id="dataprep.admin" class="role-title add-link" data-text="Dataprep Admin Beta" tabindex="-1">Dataprep Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  dataprep.admin</code> )</p>
<p>Admin role for dataprep</p></td>
<td><p><code dir="ltr" translate="no">dataprep.projects.use</code></p>
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
<td><h4 id="dataprep.projects.user" class="role-title add-link" data-text="Dataprep User Beta" tabindex="-1">Dataprep User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  dataprep.projects.user</code> )</p>
<p>Use of Dataprep.</p></td>
<td><p><code dir="ltr" translate="no">dataprep.projects.use</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
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
<td><h4 id="dataprep.serviceAgent" class="role-title add-link" data-text="Dataprep Service Agent" tabindex="-1">Dataprep Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</p>
<p>Dataprep service identity. Includes access to service accounts.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.bireservations.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  capacityCommitments.  get</code></p>
<p><code dir="ltr" translate="no">bigquery.  capacityCommitments.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.config.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.list</code></p>
<p><code dir="ltr" translate="no">bigquery.models.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.models.create</code></li>
<li><code dir="ltr" translate="no">bigquery.models.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.models.export</code></li>
<li><code dir="ltr" translate="no">bigquery.models.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.models.getMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.models.list</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateData</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.readsessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.readsessions.create</code></li>
<li><code dir="ltr" translate="no">bigquery.readsessions.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.readsessions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.  reservationAssignments.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservationAssignments.  search</code></p>
<p><code dir="ltr" translate="no">bigquery.reservationGroups.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservationGroups.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.get</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservations.  listFailoverDatasets</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.use</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.routines.create</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.get</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.list</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.update</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.savedqueries.get</code></p>
<p><code dir="ltr" translate="no">bigquery.savedqueries.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.createIndex</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.createSnapshot</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.deleteIndex</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.export</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.replicateData</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  restoreSnapshot</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateIndex</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.transfers.get</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  translation.  translate</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.create</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.update</code></p>
<p><code dir="ltr" translate="no">cloudbuild.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.locations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudbuild.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudbuild.operations.get</code></li>
<li><code dir="ltr" translate="no">cloudbuild.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.acceleratorTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.get</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.list</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.get</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.get</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.commitments.get</code></p>
<p><code dir="ltr" translate="no">compute.commitments.list</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.diskSettings.get</code></p>
<p><code dir="ltr" translate="no">compute.diskTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.diskTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.diskTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.disks.get</code></p>
<p><code dir="ltr" translate="no">compute.disks.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.disks.list</code></p>
<p><code dir="ltr" translate="no">compute.  disks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.disks.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  get</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  list</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.firewallPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.firewallPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.get</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.list</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.futureReservations.get</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  list</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.  globalOperations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalPublicDelegatedPrefixes.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalPublicDelegatedPrefixes.  list</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.hosts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.hosts.get</code></li>
<li><code dir="ltr" translate="no">compute.hosts.getVersion</code></li>
<li><code dir="ltr" translate="no">compute.hosts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.images.get</code></p>
<p><code dir="ltr" translate="no">compute.images.getFromFamily</code></p>
<p><code dir="ltr" translate="no">compute.images.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.images.list</code></p>
<p><code dir="ltr" translate="no">compute.  images.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.images.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  get</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  list</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.instanceSettings.get</code></p>
<p><code dir="ltr" translate="no">compute.instanceTemplates.get</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.instanceTemplates.list</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getEffectiveFirewalls</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getGuestAttributes</code></p>
<p><code dir="ltr" translate="no">compute.instances.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getScreenshot</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getSerialPortOutput</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getShieldedInstanceIdentity</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getShieldedVmIdentity</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listReferrers</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.instantSnapshots.get</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.instantSnapshots.list</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.interconnectGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectLocations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectLocations.  get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectLocations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.  get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.interconnects.get</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.licenseCodes.get</code></p>
<p><code dir="ltr" translate="no">compute.  licenseCodes.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenseCodes.list</code></p>
<p><code dir="ltr" translate="no">compute.licenses.get</code></p>
<p><code dir="ltr" translate="no">compute.licenses.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenses.list</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.get</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.list</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.machineTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.machineTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.multiMig.get</code></p>
<p><code dir="ltr" translate="no">compute.multiMig.list</code></p>
<p><code dir="ltr" translate="no">compute.multiMigMembers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.multiMigMembers.get</code></li>
<li><code dir="ltr" translate="no">compute.multiMigMembers.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networkAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.networkProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.networkProfiles.get</code></li>
<li><code dir="ltr" translate="no">compute.networkProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  getEffectiveFirewalls</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  getRegionEffectiveFirewalls</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.nodeGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.  nodeGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.nodeGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.nodeTemplates.get</code></p>
<p><code dir="ltr" translate="no">compute.  nodeTemplates.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.nodeTemplates.list</code></p>
<p><code dir="ltr" translate="no">compute.nodeTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.nodeTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.nodeTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.orgRolloutPlans.get</code></p>
<p><code dir="ltr" translate="no">compute.orgRolloutPlans.list</code></p>
<p><code dir="ltr" translate="no">compute.orgRollouts.get</code></p>
<p><code dir="ltr" translate="no">compute.orgRollouts.list</code></p>
<p><code dir="ltr" translate="no">compute.  organizations.  listAssociations</code></p>
<p><code dir="ltr" translate="no">compute.packetMirrorings.get</code></p>
<p><code dir="ltr" translate="no">compute.packetMirrorings.list</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.previewFeatures.get</code></p>
<p><code dir="ltr" translate="no">compute.previewFeatures.list</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.  publicAdvertisedPrefixes.  get</code></p>
<p><code dir="ltr" translate="no">compute.  publicAdvertisedPrefixes.  list</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  get</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  list</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.  regionOperations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listAvailableFeatures</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.validate</code></p>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.reservationBlocks.get</code></p>
<p><code dir="ltr" translate="no">compute.reservationBlocks.list</code></p>
<p><code dir="ltr" translate="no">compute.reservationSlots.get</code></p>
<p><code dir="ltr" translate="no">compute.reservationSlots.list</code></p>
<p><code dir="ltr" translate="no">compute.  reservationSubBlocks.  get</code></p>
<p><code dir="ltr" translate="no">compute.  reservationSubBlocks.  list</code></p>
<p><code dir="ltr" translate="no">compute.reservations.get</code></p>
<p><code dir="ltr" translate="no">compute.reservations.list</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.  resourcePolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.rolloutPlans.get</code></p>
<p><code dir="ltr" translate="no">compute.rolloutPlans.list</code></p>
<p><code dir="ltr" translate="no">compute.rollouts.get</code></p>
<p><code dir="ltr" translate="no">compute.rollouts.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.getRoutePolicy</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.listBgpRoutes</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listRoutePolicies</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.routes.get</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.routes.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.securityPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.securityPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.serviceAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.snapshotGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.  snapshotGroups.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.snapshotGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.snapshotSettings.get</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.get</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.list</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.spotAssistants.get</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.get</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.list</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listAvailableFeatures</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.get</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.list</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.get</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.get</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.validate</code></p>
<p><code dir="ltr" translate="no">compute.  vmExtensionPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  vmExtensionPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.list</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.  zoneOperations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataflow.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataflow.jobs.cancel</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.create</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.get</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.list</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.snapshot</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.updateContents</code></li>
</ul>
<p><code dir="ltr" translate="no">dataflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dataflow.metrics.get</code></p>
<p><code dir="ltr" translate="no">dataflow.snapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataflow.snapshots.delete</code></li>
<li><code dir="ltr" translate="no">dataflow.snapshots.get</code></li>
<li><code dir="ltr" translate="no">dataflow.snapshots.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.folders.create</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.repositories.create</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.cancel</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.create</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.get</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.getData</code></p>
<p><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.list</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.run</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.update</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.list</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">remotebuildexecution.blobs.get</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.folders.create</code></li>
<li><code dir="ltr" translate="no">storage.folders.delete</code></li>
<li><code dir="ltr" translate="no">storage.folders.get</code></li>
<li><code dir="ltr" translate="no">storage.folders.list</code></li>
<li><code dir="ltr" translate="no">storage.folders.rename</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.managedFolders.create</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.delete</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.multipartUploads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.multipartUploads.abort</code></li>
<li><code dir="ltr" translate="no">storage.  multipartUploads.  create</code></li>
<li><code dir="ltr" translate="no">storage.multipartUploads.list</code></li>
<li><code dir="ltr" translate="no">storage.  multipartUploads.  listParts</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.objects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.objects.create</code></li>
<li><code dir="ltr" translate="no">storage.objects.createContext</code></li>
<li><code dir="ltr" translate="no">storage.objects.delete</code></li>
<li><code dir="ltr" translate="no">storage.objects.deleteContext</code></li>
<li><code dir="ltr" translate="no">storage.objects.get</code></li>
<li><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.objects.list</code></li>
<li><code dir="ltr" translate="no">storage.objects.move</code></li>
<li><code dir="ltr" translate="no">storage.  objects.  overrideUnlockedRetention</code></li>
<li><code dir="ltr" translate="no">storage.objects.restore</code></li>
<li><code dir="ltr" translate="no">storage.objects.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.objects.setRetention</code></li>
<li><code dir="ltr" translate="no">storage.objects.update</code></li>
<li><code dir="ltr" translate="no">storage.objects.updateContext</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Dataprep by Trifacta permissions

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
<td><h4 id="dataprep.projects.use" class="permission-name add-link" data-text="dataprep.projects.use" tabindex="-1"><code dir="ltr" translate="no">dataprep.projects.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user">Dataprep User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.projects.user</code> )</p></td>
</tr>
</tbody>
</table>
