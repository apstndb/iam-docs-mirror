---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster
title: Cluster Director roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cluster Director. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cluster Director roles

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
<td><h4 id="hypercomputecluster.editor" class="role-title add-link" data-text="Cluster Director Editor Beta" tabindex="-1">Cluster Director Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p>Edit access to Cluster Director resources.</p></td>
<td><p><code dir="ltr" translate="no">hypercomputecluster.*</code></p>
<ul>
<li><code dir="ltr" translate="no">hypercomputecluster.  clusters.  create</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  clusters.  delete</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  clusters.  get</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  clusters.  list</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  clusters.  update</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  locations.  get</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  locations.  list</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  create</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  delete</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  get</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  list</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  update</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  operations.  get</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="hypercomputecluster.viewer" class="role-title add-link" data-text="Cluster Director Viewer Beta" tabindex="-1">Cluster Director Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  hypercomputecluster.viewer</code> )</p>
<p>Readonly access to Cluster Director resources.</p></td>
<td><p><code dir="ltr" translate="no">hypercomputecluster.  clusters.  get</code></p>
<p><code dir="ltr" translate="no">hypercomputecluster.  clusters.  list</code></p>
<p><code dir="ltr" translate="no">hypercomputecluster.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">hypercomputecluster.  locations.  get</code></li>
<li><code dir="ltr" translate="no">hypercomputecluster.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  get</code></p>
<p><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  list</code></p>
<p><code dir="ltr" translate="no">hypercomputecluster.  operations.  get</code></p>
<p><code dir="ltr" translate="no">hypercomputecluster.  operations.  list</code></p>
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
<td><h4 id="hypercomputecluster.serviceAgent" class="role-title add-link" data-text="Cluster Director Service Agent" tabindex="-1">Cluster Director Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</p>
<p>Grants Cluster Director Service Agent access to necessary GCP resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudbuild.connections.list</code></p>
<p><code dir="ltr" translate="no">cloudbuild.  repositories.  accessReadToken</code></p>
<p><code dir="ltr" translate="no">cloudbuild.repositories.list</code></p>
<p><code dir="ltr" translate="no">cloudquotas.quotas.get</code></p>
<p><code dir="ltr" translate="no">compute.acceleratorTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.addresses.create</code></p>
<p><code dir="ltr" translate="no">compute.addresses.delete</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.addresses.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.disks.create</code></p>
<p><code dir="ltr" translate="no">compute.disks.createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.disks.delete</code></p>
<p><code dir="ltr" translate="no">compute.disks.get</code></p>
<p><code dir="ltr" translate="no">compute.disks.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.disks.list</code></p>
<p><code dir="ltr" translate="no">compute.disks.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.disks.update</code></p>
<p><code dir="ltr" translate="no">compute.disks.use</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  cloneRules</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.firewallPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.firewallPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  update</code></p>
<p><code dir="ltr" translate="no">compute.firewallPolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.create</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.delete</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.update</code></p>
<p><code dir="ltr" translate="no">compute.futureReservations.get</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.create</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.delete</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.update</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.use</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  create</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  delete</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  update</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.use</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  create</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  delete</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  update</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.use</code></p>
<p><code dir="ltr" translate="no">compute.images.get</code></p>
<p><code dir="ltr" translate="no">compute.images.getFromFamily</code></p>
<p><code dir="ltr" translate="no">compute.images.list</code></p>
<p><code dir="ltr" translate="no">compute.images.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  create</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  get</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  list</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  update</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  use</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.create</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.delete</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.update</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.use</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  create</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  delete</code></p>
<p><code dir="ltr" translate="no">compute.instanceTemplates.get</code></p>
<p><code dir="ltr" translate="no">compute.instanceTemplates.list</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.instances.create</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.instances.delete</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  pscInterfaceCreate</code></p>
<p><code dir="ltr" translate="no">compute.instances.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.instances.setMetadata</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  setServiceAccount</code></p>
<p><code dir="ltr" translate="no">compute.instances.setTags</code></p>
<p><code dir="ltr" translate="no">compute.instances.suspend</code></p>
<p><code dir="ltr" translate="no">compute.instances.update</code></p>
<p><code dir="ltr" translate="no">compute.instances.use</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.machineTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.machineTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  create</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  delete</code></p>
<p><code dir="ltr" translate="no">compute.networkAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.networks.addPeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.create</code></p>
<p><code dir="ltr" translate="no">compute.networks.delete</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  getEffectiveFirewalls</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">compute.networks.removePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.networks.useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.reservationBlocks.get</code></p>
<p><code dir="ltr" translate="no">compute.reservationBlocks.list</code></p>
<p><code dir="ltr" translate="no">compute.  reservationSubBlocks.  get</code></p>
<p><code dir="ltr" translate="no">compute.  reservationSubBlocks.  list</code></p>
<p><code dir="ltr" translate="no">compute.reservations.get</code></p>
<p><code dir="ltr" translate="no">compute.reservations.list</code></p>
<p><code dir="ltr" translate="no">compute.  resourcePolicies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  resourcePolicies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.routers.create</code></p>
<p><code dir="ltr" translate="no">compute.routers.delete</code></p>
<p><code dir="ltr" translate="no">compute.routers.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.update</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.create</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.delete</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">config.artifacts.import</code></p>
<p><code dir="ltr" translate="no">config.deployments.deleteState</code></p>
<p><code dir="ltr" translate="no">config.deployments.getLock</code></p>
<p><code dir="ltr" translate="no">config.deployments.getState</code></p>
<p><code dir="ltr" translate="no">config.deployments.updateState</code></p>
<p><code dir="ltr" translate="no">config.previews.upload</code></p>
<p><code dir="ltr" translate="no">config.revisions.getState</code></p>
<p><code dir="ltr" translate="no">container.clusters.connect</code></p>
<p><code dir="ltr" translate="no">container.clusters.create</code></p>
<p><code dir="ltr" translate="no">container.clusters.delete</code></p>
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">container.clusters.list</code></p>
<p><code dir="ltr" translate="no">container.clusters.update</code></p>
<p><code dir="ltr" translate="no">container.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.operations.get</code></li>
<li><code dir="ltr" translate="no">container.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">container.pods.get</code></p>
<p><code dir="ltr" translate="no">container.pods.list</code></p>
<p><code dir="ltr" translate="no">container.thirdPartyObjects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.changes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.changes.create</code></li>
<li><code dir="ltr" translate="no">dns.changes.get</code></li>
<li><code dir="ltr" translate="no">dns.changes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.managedZones.create</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.delete</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.get</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.update</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  bindPrivateDNSZone</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.create</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.delete</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.get</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.list</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">file.instances.create</code></p>
<p><code dir="ltr" translate="no">file.instances.delete</code></p>
<p><code dir="ltr" translate="no">file.instances.get</code></p>
<p><code dir="ltr" translate="no">file.instances.list</code></p>
<p><code dir="ltr" translate="no">file.instances.update</code></p>
<p><code dir="ltr" translate="no">file.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">file.locations.get</code></li>
<li><code dir="ltr" translate="no">file.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">file.operations.get</code></p>
<p><code dir="ltr" translate="no">file.operations.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">logging.sinks.create</code></p>
<p><code dir="ltr" translate="no">logging.sinks.delete</code></p>
<p><code dir="ltr" translate="no">logging.sinks.get</code></p>
<p><code dir="ltr" translate="no">logging.sinks.list</code></p>
<p><code dir="ltr" translate="no">lustre.instances.create</code></p>
<p><code dir="ltr" translate="no">lustre.instances.delete</code></p>
<p><code dir="ltr" translate="no">lustre.instances.get</code></p>
<p><code dir="ltr" translate="no">lustre.instances.list</code></p>
<p><code dir="ltr" translate="no">lustre.instances.update</code></p>
<p><code dir="ltr" translate="no">lustre.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">lustre.locations.get</code></li>
<li><code dir="ltr" translate="no">lustre.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">lustre.operations.get</code></p>
<p><code dir="ltr" translate="no">lustre.operations.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.timeSeries.create</code></li>
<li><code dir="ltr" translate="no">monitoring.timeSeries.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  operations.  get</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  addPeering</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  deleteConnection</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  deletePeeredDnsDomain</code></p>
<p><code dir="ltr" translate="no">servicenetworking.services.get</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  listPeeredDnsDomains</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">storage.anywhereCaches.get</code></p>
<p><code dir="ltr" translate="no">storage.anywhereCaches.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.delete</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="hypercomputecluster.sharedVpcServiceAgent" class="role-title add-link" data-text="Cluster Director Shared VPC Service Agent" tabindex="-1">Cluster Director Shared VPC Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  hypercomputecluster.sharedVpcServiceAgent</code> )</p>
<p>Grants Cluster Director Service Agent access to necessary GCP resources in Shared VPC host project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.addresses.useInternal</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  get</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  list</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  use</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.instanceSettings.get</code></p>
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
<p><code dir="ltr" translate="no">compute.interconnects.use</code></p>
<p><code dir="ltr" translate="no">compute.networkAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.networkProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.networkProfiles.get</code></li>
<li><code dir="ltr" translate="no">compute.networkProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networks.access</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  getEffectiveFirewalls</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  getRegionEffectiveFirewalls</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.networks.useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  use</code></p>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
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
<p><code dir="ltr" translate="no">compute.serviceAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.use</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.list</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.managedZones.get</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  bindPrivateDNSZone</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  get</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkconnectivity.  locations.  get</code></li>
<li><code dir="ltr" translate="no">networkconnectivity.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  operations.  get</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  get</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  policyBasedRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  addressGroups.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  addressGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  addressGroups.  use</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  use</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authzPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authzPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  use</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  use</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  use</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  use</code></p>
<p><code dir="ltr" translate="no">networksecurity.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.locations.get</code></li>
<li><code dir="ltr" translate="no">networksecurity.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.operations.get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  sacAttachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  sacAttachments.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  sacAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  sacAttachments.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  sacAttachments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.sacRealms.get</code></p>
<p><code dir="ltr" translate="no">networksecurity.sacRealms.list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  use</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfiles.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfiles.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfiles.  use</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  use</code></p>
<p><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  use</code></p>
<p><code dir="ltr" translate="no">networksecurity.urlLists.get</code></p>
<p><code dir="ltr" translate="no">networksecurity.urlLists.list</code></p>
<p><code dir="ltr" translate="no">networksecurity.urlLists.use</code></p>
<p><code dir="ltr" translate="no">networkservices.  authzExtensions.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  authzExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  authzExtensions.  use</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.gateways.get</code></p>
<p><code dir="ltr" translate="no">networkservices.gateways.list</code></p>
<p><code dir="ltr" translate="no">networkservices.gateways.use</code></p>
<p><code dir="ltr" translate="no">networkservices.grpcRoutes.get</code></p>
<p><code dir="ltr" translate="no">networkservices.  grpcRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.httpRoutes.get</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  use</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.locations.get</code></li>
<li><code dir="ltr" translate="no">networkservices.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.meshes.get</code></p>
<p><code dir="ltr" translate="no">networkservices.meshes.list</code></p>
<p><code dir="ltr" translate="no">networkservices.meshes.use</code></p>
<p><code dir="ltr" translate="no">networkservices.operations.get</code></p>
<p><code dir="ltr" translate="no">networkservices.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.route_views.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  route_views.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  route_views.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.  serviceBindings.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  serviceBindings.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  swpSecurityExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.tcpRoutes.get</code></p>
<p><code dir="ltr" translate="no">networkservices.tcpRoutes.list</code></p>
<p><code dir="ltr" translate="no">networkservices.tlsRoutes.get</code></p>
<p><code dir="ltr" translate="no">networkservices.tlsRoutes.list</code></p>
<p><code dir="ltr" translate="no">networkservices.  wasmPlugins.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  wasmPlugins.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  wasmPlugins.  use</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicenetworking.services.get</code></p>
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

## Cluster Director permissions

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
<td><h4 id="hypercomputecluster.clusters.create" class="permission-name add-link" data-text="hypercomputecluster.clusters.create" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  clusters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="hypercomputecluster.clusters.delete" class="permission-name add-link" data-text="hypercomputecluster.clusters.delete" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  clusters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="hypercomputecluster.clusters.get" class="permission-name add-link" data-text="hypercomputecluster.clusters.get" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  clusters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.viewer">Cluster Director Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="hypercomputecluster.clusters.list" class="permission-name add-link" data-text="hypercomputecluster.clusters.list" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  clusters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.viewer">Cluster Director Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="hypercomputecluster.clusters.update" class="permission-name add-link" data-text="hypercomputecluster.clusters.update" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  clusters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="hypercomputecluster.locations.get" class="permission-name add-link" data-text="hypercomputecluster.locations.get" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.viewer">Cluster Director Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="hypercomputecluster.locations.list" class="permission-name add-link" data-text="hypercomputecluster.locations.list" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.viewer">Cluster Director Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="hypercomputecluster.machineLearningRuns.create" class="permission-name add-link" data-text="hypercomputecluster.machineLearningRuns.create" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="hypercomputecluster.machineLearningRuns.delete" class="permission-name add-link" data-text="hypercomputecluster.machineLearningRuns.delete" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="hypercomputecluster.machineLearningRuns.get" class="permission-name add-link" data-text="hypercomputecluster.machineLearningRuns.get" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.viewer">Cluster Director Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="hypercomputecluster.machineLearningRuns.list" class="permission-name add-link" data-text="hypercomputecluster.machineLearningRuns.list" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.viewer">Cluster Director Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="hypercomputecluster.machineLearningRuns.update" class="permission-name add-link" data-text="hypercomputecluster.machineLearningRuns.update" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  machineLearningRuns.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="hypercomputecluster.operations.cancel" class="permission-name add-link" data-text="hypercomputecluster.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="hypercomputecluster.operations.delete" class="permission-name add-link" data-text="hypercomputecluster.operations.delete" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="hypercomputecluster.operations.get" class="permission-name add-link" data-text="hypercomputecluster.operations.get" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.viewer">Cluster Director Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="hypercomputecluster.operations.list" class="permission-name add-link" data-text="hypercomputecluster.operations.list" tabindex="-1"><code dir="ltr" translate="no">hypercomputecluster.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.viewer">Cluster Director Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
