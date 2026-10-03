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
<td>Cluster Director Editor <sup>Beta</sup>
<p>( <code>roles/ hypercomputecluster.editor</code> )</p>
<p>Edit access to Cluster Director resources.</p></td>
<td><p><code>hypercomputecluster.*</code></p>
<ul>
<li><code>hypercomputecluster. clusters. create</code></li>
<li><code>hypercomputecluster. clusters. delete</code></li>
<li><code>hypercomputecluster. clusters. get</code></li>
<li><code>hypercomputecluster. clusters. list</code></li>
<li><code>hypercomputecluster. clusters. update</code></li>
<li><code>hypercomputecluster. locations. get</code></li>
<li><code>hypercomputecluster. locations. list</code></li>
<li><code>hypercomputecluster. machineLearningRuns. create</code></li>
<li><code>hypercomputecluster. machineLearningRuns. delete</code></li>
<li><code>hypercomputecluster. machineLearningRuns. get</code></li>
<li><code>hypercomputecluster. machineLearningRuns. list</code></li>
<li><code>hypercomputecluster. machineLearningRuns. update</code></li>
<li><code>hypercomputecluster. operations. cancel</code></li>
<li><code>hypercomputecluster. operations. delete</code></li>
<li><code>hypercomputecluster. operations. get</code></li>
<li><code>hypercomputecluster. operations. list</code></li>
</ul>
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
<td>Cluster Director Service Agent
<p>( <code>roles/ hypercomputecluster.serviceAgent</code> )</p>
<p>Grants Cluster Director Service Agent access to necessary GCP resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>aiplatform.endpoints.get</code></p>
<p><code>aiplatform.endpoints.predict</code></p>
<p><code>aiplatform.locations.get</code></p>
<p><code>aiplatform.locations.list</code></p>
<p><code>cloudbuild.connections.list</code></p>
<p><code>cloudbuild. repositories. accessReadToken</code></p>
<p><code>cloudbuild.repositories.list</code></p>
<p><code>cloudquotas.quotas.get</code></p>
<p><code>compute.acceleratorTypes.*</code></p>
<ul>
<li><code>compute.acceleratorTypes.get</code></li>
<li><code>compute.acceleratorTypes.list</code></li>
</ul>
<p><code>compute.addresses.create</code></p>
<p><code>compute.addresses.delete</code></p>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.addresses.setLabels</code></p>
<p><code>compute.disks.create</code></p>
<p><code>compute.disks.createTagBinding</code></p>
<p><code>compute.disks.delete</code></p>
<p><code>compute.disks.get</code></p>
<p><code>compute.disks.getIamPolicy</code></p>
<p><code>compute.disks.list</code></p>
<p><code>compute.disks.setLabels</code></p>
<p><code>compute.disks.update</code></p>
<p><code>compute.disks.use</code></p>
<p><code>compute. firewallPolicies. cloneRules</code></p>
<p><code>compute. firewallPolicies. create</code></p>
<p><code>compute. firewallPolicies. delete</code></p>
<p><code>compute.firewallPolicies.get</code></p>
<p><code>compute.firewallPolicies.list</code></p>
<p><code>compute. firewallPolicies. update</code></p>
<p><code>compute.firewallPolicies.use</code></p>
<p><code>compute.firewalls.create</code></p>
<p><code>compute.firewalls.delete</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute.firewalls.update</code></p>
<p><code>compute.futureReservations.get</code></p>
<p><code>compute. futureReservations. list</code></p>
<p><code>compute. globalAddresses. createInternal</code></p>
<p><code>compute. globalAddresses. deleteInternal</code></p>
<p><code>compute.globalAddresses.get</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute. globalAddresses. setLabels</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.globalOperations.list</code></p>
<p><code>compute.healthChecks.create</code></p>
<p><code>compute.healthChecks.delete</code></p>
<p><code>compute.healthChecks.get</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute.healthChecks.update</code></p>
<p><code>compute.healthChecks.use</code></p>
<p><code>compute. httpHealthChecks. create</code></p>
<p><code>compute. httpHealthChecks. delete</code></p>
<p><code>compute.httpHealthChecks.get</code></p>
<p><code>compute.httpHealthChecks.list</code></p>
<p><code>compute. httpHealthChecks. update</code></p>
<p><code>compute.httpHealthChecks.use</code></p>
<p><code>compute. httpsHealthChecks. create</code></p>
<p><code>compute. httpsHealthChecks. delete</code></p>
<p><code>compute.httpsHealthChecks.get</code></p>
<p><code>compute.httpsHealthChecks.list</code></p>
<p><code>compute. httpsHealthChecks. update</code></p>
<p><code>compute.httpsHealthChecks.use</code></p>
<p><code>compute.images.get</code></p>
<p><code>compute.images.getFromFamily</code></p>
<p><code>compute.images.list</code></p>
<p><code>compute.images.useReadOnly</code></p>
<p><code>compute. instanceGroupManagers. create</code></p>
<p><code>compute. instanceGroupManagers. delete</code></p>
<p><code>compute. instanceGroupManagers. get</code></p>
<p><code>compute. instanceGroupManagers. list</code></p>
<p><code>compute. instanceGroupManagers. update</code></p>
<p><code>compute. instanceGroupManagers. use</code></p>
<p><code>compute.instanceGroups.create</code></p>
<p><code>compute.instanceGroups.delete</code></p>
<p><code>compute.instanceGroups.get</code></p>
<p><code>compute.instanceGroups.list</code></p>
<p><code>compute.instanceGroups.update</code></p>
<p><code>compute.instanceGroups.use</code></p>
<p><code>compute. instanceTemplates. create</code></p>
<p><code>compute. instanceTemplates. delete</code></p>
<p><code>compute.instanceTemplates.get</code></p>
<p><code>compute.instanceTemplates.list</code></p>
<p><code>compute. instanceTemplates. useReadOnly</code></p>
<p><code>compute.instances.create</code></p>
<p><code>compute. instances. createTagBinding</code></p>
<p><code>compute.instances.delete</code></p>
<p><code>compute. instances. deleteTagBinding</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute. instances. pscInterfaceCreate</code></p>
<p><code>compute.instances.setLabels</code></p>
<p><code>compute.instances.setMetadata</code></p>
<p><code>compute. instances. setServiceAccount</code></p>
<p><code>compute.instances.setTags</code></p>
<p><code>compute.instances.suspend</code></p>
<p><code>compute.instances.update</code></p>
<p><code>compute.instances.use</code></p>
<p><code>compute.machineTypes.*</code></p>
<ul>
<li><code>compute.machineTypes.get</code></li>
<li><code>compute.machineTypes.list</code></li>
</ul>
<p><code>compute. networkAttachments. create</code></p>
<p><code>compute. networkAttachments. delete</code></p>
<p><code>compute.networkAttachments.get</code></p>
<p><code>compute. networkAttachments. list</code></p>
<p><code>compute.networks.addPeering</code></p>
<p><code>compute.networks.create</code></p>
<p><code>compute.networks.delete</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute. networks. getEffectiveFirewalls</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. networks. listPeeringRoutes</code></p>
<p><code>compute.networks.removePeering</code></p>
<p><code>compute.networks.updatePeering</code></p>
<p><code>compute.networks.updatePolicy</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute.networks.useExternalIp</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.regionOperations.list</code></p>
<p><code>compute.reservationBlocks.get</code></p>
<p><code>compute.reservationBlocks.list</code></p>
<p><code>compute. reservationSubBlocks. get</code></p>
<p><code>compute. reservationSubBlocks. list</code></p>
<p><code>compute.reservations.get</code></p>
<p><code>compute.reservations.list</code></p>
<p><code>compute. resourcePolicies. create</code></p>
<p><code>compute. resourcePolicies. delete</code></p>
<p><code>compute.resourcePolicies.get</code></p>
<p><code>compute.resourcePolicies.list</code></p>
<p><code>compute.resourcePolicies.use</code></p>
<p><code>compute.routers.create</code></p>
<p><code>compute.routers.delete</code></p>
<p><code>compute.routers.get</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.routers.update</code></p>
<p><code>compute.storagePools.get</code></p>
<p><code>compute.storagePools.list</code></p>
<p><code>compute.storagePools.use</code></p>
<p><code>compute.subnetworks.create</code></p>
<p><code>compute.subnetworks.delete</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>compute. subnetworks. useExternalIp</code></p>
<p><code>compute.zoneOperations.get</code></p>
<p><code>compute.zoneOperations.list</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>config.artifacts.import</code></p>
<p><code>config.deployments.deleteState</code></p>
<p><code>config.deployments.getLock</code></p>
<p><code>config.deployments.getState</code></p>
<p><code>config.deployments.updateState</code></p>
<p><code>config.previews.upload</code></p>
<p><code>config.revisions.getState</code></p>
<p><code>container.clusters.connect</code></p>
<p><code>container.clusters.create</code></p>
<p><code>container.clusters.delete</code></p>
<p><code>container.clusters.get</code></p>
<p><code>container.clusters.list</code></p>
<p><code>container.clusters.update</code></p>
<p><code>container.deployments.get</code></p>
<p><code>container.deployments.list</code></p>
<p><code>container.jobs.get</code></p>
<p><code>container.jobs.list</code></p>
<p><code>container.operations.*</code></p>
<ul>
<li><code>container.operations.get</code></li>
<li><code>container.operations.list</code></li>
</ul>
<p><code>container.pods.get</code></p>
<p><code>container.pods.list</code></p>
<p><code>container.thirdPartyObjects.*</code></p>
<ul>
<li><code>container. thirdPartyObjects. create</code></li>
<li><code>container. thirdPartyObjects. delete</code></li>
<li><code>container. thirdPartyObjects. get</code></li>
<li><code>container. thirdPartyObjects. list</code></li>
<li><code>container. thirdPartyObjects. update</code></li>
</ul>
<p><code>dns.changes.*</code></p>
<ul>
<li><code>dns.changes.create</code></li>
<li><code>dns.changes.get</code></li>
<li><code>dns.changes.list</code></li>
</ul>
<p><code>dns.managedZones.create</code></p>
<p><code>dns.managedZones.delete</code></p>
<p><code>dns.managedZones.get</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns.managedZones.update</code></p>
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
<p><code>file.instances.create</code></p>
<p><code>file.instances.delete</code></p>
<p><code>file.instances.get</code></p>
<p><code>file.instances.list</code></p>
<p><code>file.instances.update</code></p>
<p><code>file.locations.*</code></p>
<ul>
<li><code>file.locations.get</code></li>
<li><code>file.locations.list</code></li>
</ul>
<p><code>file.operations.get</code></p>
<p><code>file.operations.list</code></p>
<p><code>hypercomputecluster. clusters. update</code></p>
<p><code>hypercomputecluster. locations. get</code></p>
<p><code>hypercomputecluster. machineLearningRuns.*</code></p>
<ul>
<li><code>hypercomputecluster. machineLearningRuns. create</code></li>
<li><code>hypercomputecluster. machineLearningRuns. delete</code></li>
<li><code>hypercomputecluster. machineLearningRuns. get</code></li>
<li><code>hypercomputecluster. machineLearningRuns. list</code></li>
<li><code>hypercomputecluster. machineLearningRuns. update</code></li>
</ul>
<p><code>hypercomputecluster. operations.*</code></p>
<ul>
<li><code>hypercomputecluster. operations. cancel</code></li>
<li><code>hypercomputecluster. operations. delete</code></li>
<li><code>hypercomputecluster. operations. get</code></li>
<li><code>hypercomputecluster. operations. list</code></li>
</ul>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.list</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>logging.sinks.create</code></p>
<p><code>logging.sinks.delete</code></p>
<p><code>logging.sinks.get</code></p>
<p><code>logging.sinks.list</code></p>
<p><code>lustre.instances.create</code></p>
<p><code>lustre.instances.delete</code></p>
<p><code>lustre.instances.get</code></p>
<p><code>lustre.instances.list</code></p>
<p><code>lustre.instances.update</code></p>
<p><code>lustre.locations.*</code></p>
<ul>
<li><code>lustre.locations.get</code></li>
<li><code>lustre.locations.list</code></li>
</ul>
<p><code>lustre.operations.get</code></p>
<p><code>lustre.operations.list</code></p>
<p><code>monitoring. metricDescriptors. create</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring.timeSeries.*</code></p>
<ul>
<li><code>monitoring.timeSeries.create</code></li>
<li><code>monitoring.timeSeries.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>servicemanagement. services. report</code></p>
<p><code>servicenetworking. operations. get</code></p>
<p><code>servicenetworking. services. addPeering</code></p>
<p><code>servicenetworking. services. deleteConnection</code></p>
<p><code>servicenetworking. services. deletePeeredDnsDomain</code></p>
<p><code>servicenetworking.services.get</code></p>
<p><code>servicenetworking. services. listPeeredDnsDomains</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>storage.anywhereCaches.get</code></p>
<p><code>storage.anywhereCaches.list</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.delete</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.buckets.setIamPolicy</code></p>
<p><code>storage.buckets.update</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.update</code></p></td>
</tr>
<tr class="even">
<td>Cluster Director Shared VPC Service Agent
<p>( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</p>
<p>Grants Cluster Director Service Agent access to necessary GCP resources in Shared VPC host project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>compute. addresses. createInternal</code></p>
<p><code>compute. addresses. deleteInternal</code></p>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute. addresses. listEffectiveTags</code></p>
<p><code>compute. addresses. listTagBindings</code></p>
<p><code>compute.addresses.useInternal</code></p>
<p><code>compute.crossSiteNetworks.get</code></p>
<p><code>compute.crossSiteNetworks.list</code></p>
<p><code>compute. externalVpnGateways. get</code></p>
<p><code>compute. externalVpnGateways. list</code></p>
<p><code>compute. externalVpnGateways. listEffectiveTags</code></p>
<p><code>compute. externalVpnGateways. listTagBindings</code></p>
<p><code>compute. externalVpnGateways. use</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute. firewalls. listEffectiveTags</code></p>
<p><code>compute. firewalls. listTagBindings</code></p>
<p><code>compute.globalAddresses.get</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute.instanceSettings.get</code></p>
<p><code>compute. interconnectAttachmentGroups. get</code></p>
<p><code>compute. interconnectAttachmentGroups. list</code></p>
<p><code>compute. interconnectAttachments. get</code></p>
<p><code>compute. interconnectAttachments. list</code></p>
<p><code>compute. interconnectAttachments. listEffectiveTags</code></p>
<p><code>compute. interconnectAttachments. listTagBindings</code></p>
<p><code>compute.interconnectGroups.get</code></p>
<p><code>compute. interconnectGroups. list</code></p>
<p><code>compute. interconnectLocations.*</code></p>
<ul>
<li><code>compute. interconnectLocations. get</code></li>
<li><code>compute. interconnectLocations. list</code></li>
</ul>
<p><code>compute. interconnectRemoteLocations.*</code></p>
<ul>
<li><code>compute. interconnectRemoteLocations. get</code></li>
<li><code>compute. interconnectRemoteLocations. list</code></li>
</ul>
<p><code>compute.interconnects.get</code></p>
<p><code>compute.interconnects.list</code></p>
<p><code>compute. interconnects. listEffectiveTags</code></p>
<p><code>compute. interconnects. listTagBindings</code></p>
<p><code>compute.interconnects.use</code></p>
<p><code>compute.networkAttachments.get</code></p>
<p><code>compute. networkAttachments. list</code></p>
<p><code>compute. networkAttachments. listEffectiveTags</code></p>
<p><code>compute. networkAttachments. listTagBindings</code></p>
<p><code>compute.networkProfiles.*</code></p>
<ul>
<li><code>compute.networkProfiles.get</code></li>
<li><code>compute.networkProfiles.list</code></li>
</ul>
<p><code>compute.networks.access</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute. networks. getEffectiveFirewalls</code></p>
<p><code>compute. networks. getRegionEffectiveFirewalls</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. networks. listEffectiveTags</code></p>
<p><code>compute. networks. listPeeringRoutes</code></p>
<p><code>compute. networks. listTagBindings</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute.networks.useExternalIp</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. regionCompositeHealthChecks. get</code></p>
<p><code>compute. regionCompositeHealthChecks. list</code></p>
<p><code>compute. regionHealthAggregationPolicies. get</code></p>
<p><code>compute. regionHealthAggregationPolicies. list</code></p>
<p><code>compute. regionHealthSources. get</code></p>
<p><code>compute. regionHealthSources. list</code></p>
<p><code>compute. regionNetworkPolicies. get</code></p>
<p><code>compute. regionNetworkPolicies. list</code></p>
<p><code>compute. regionNetworkPolicies. use</code></p>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.routers.get</code></p>
<p><code>compute.routers.getRoutePolicy</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.routers.listBgpRoutes</code></p>
<p><code>compute. routers. listEffectiveTags</code></p>
<p><code>compute. routers. listRoutePolicies</code></p>
<p><code>compute. routers. listTagBindings</code></p>
<p><code>compute.routes.get</code></p>
<p><code>compute.routes.list</code></p>
<p><code>compute. routes. listEffectiveTags</code></p>
<p><code>compute.routes.listTagBindings</code></p>
<p><code>compute.serviceAttachments.get</code></p>
<p><code>compute. serviceAttachments. list</code></p>
<p><code>compute. serviceAttachments. listEffectiveTags</code></p>
<p><code>compute. serviceAttachments. listTagBindings</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute. subnetworks. listEffectiveTags</code></p>
<p><code>compute. subnetworks. listTagBindings</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>compute. subnetworks. useExternalIp</code></p>
<p><code>compute.targetVpnGateways.get</code></p>
<p><code>compute.targetVpnGateways.list</code></p>
<p><code>compute. targetVpnGateways. listEffectiveTags</code></p>
<p><code>compute. targetVpnGateways. listTagBindings</code></p>
<p><code>compute.vpnGateways.get</code></p>
<p><code>compute.vpnGateways.list</code></p>
<p><code>compute. vpnGateways. listEffectiveTags</code></p>
<p><code>compute. vpnGateways. listTagBindings</code></p>
<p><code>compute.vpnGateways.use</code></p>
<p><code>compute.vpnTunnels.get</code></p>
<p><code>compute.vpnTunnels.list</code></p>
<p><code>compute. vpnTunnels. listEffectiveTags</code></p>
<p><code>compute. vpnTunnels. listTagBindings</code></p>
<p><code>compute.wireGroups.get</code></p>
<p><code>compute.wireGroups.list</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>dns.managedZones.get</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns. networks. bindPrivateDNSZone</code></p>
<p><code>dns. networks. targetWithPeeringZone</code></p>
<p><code>networkconnectivity. internalRanges. get</code></p>
<p><code>networkconnectivity. internalRanges. list</code></p>
<p><code>networkconnectivity. locations.*</code></p>
<ul>
<li><code>networkconnectivity. locations. get</code></li>
<li><code>networkconnectivity. locations. list</code></li>
</ul>
<p><code>networkconnectivity. operations. get</code></p>
<p><code>networkconnectivity. operations. list</code></p>
<p><code>networkconnectivity. policyBasedRoutes. get</code></p>
<p><code>networkconnectivity. policyBasedRoutes. list</code></p>
<p><code>networkmanagement. connectivitytests. get</code></p>
<p><code>networkmanagement. connectivitytests. list</code></p>
<p><code>networksecurity. addressGroups. get</code></p>
<p><code>networksecurity. addressGroups. list</code></p>
<p><code>networksecurity. addressGroups. use</code></p>
<p><code>networksecurity. authorizationPolicies. get</code></p>
<p><code>networksecurity. authorizationPolicies. list</code></p>
<p><code>networksecurity. authorizationPolicies. use</code></p>
<p><code>networksecurity. authzPolicies. get</code></p>
<p><code>networksecurity. authzPolicies. list</code></p>
<p><code>networksecurity. clientTlsPolicies. get</code></p>
<p><code>networksecurity. clientTlsPolicies. list</code></p>
<p><code>networksecurity. clientTlsPolicies. use</code></p>
<p><code>networksecurity. firewallEndpointAssociations. get</code></p>
<p><code>networksecurity. firewallEndpointAssociations. list</code></p>
<p><code>networksecurity. firewallEndpoints. get</code></p>
<p><code>networksecurity. firewallEndpoints. list</code></p>
<p><code>networksecurity. firewallEndpoints. use</code></p>
<p><code>networksecurity. gatewaySecurityPolicies. get</code></p>
<p><code>networksecurity. gatewaySecurityPolicies. list</code></p>
<p><code>networksecurity. gatewaySecurityPolicies. use</code></p>
<p><code>networksecurity. gatewaySecurityPolicyRules. get</code></p>
<p><code>networksecurity. gatewaySecurityPolicyRules. list</code></p>
<p><code>networksecurity. gatewaySecurityPolicyRules. use</code></p>
<p><code>networksecurity.locations.*</code></p>
<ul>
<li><code>networksecurity.locations.get</code></li>
<li><code>networksecurity.locations.list</code></li>
</ul>
<p><code>networksecurity.operations.get</code></p>
<p><code>networksecurity. operations. list</code></p>
<p><code>networksecurity. sacAttachments.*</code></p>
<ul>
<li><code>networksecurity. sacAttachments. create</code></li>
<li><code>networksecurity. sacAttachments. delete</code></li>
<li><code>networksecurity. sacAttachments. get</code></li>
<li><code>networksecurity. sacAttachments. list</code></li>
</ul>
<p><code>networksecurity.sacRealms.get</code></p>
<p><code>networksecurity.sacRealms.list</code></p>
<p><code>networksecurity. securityProfileGroups. get</code></p>
<p><code>networksecurity. securityProfileGroups. list</code></p>
<p><code>networksecurity. securityProfileGroups. use</code></p>
<p><code>networksecurity. securityProfiles. get</code></p>
<p><code>networksecurity. securityProfiles. list</code></p>
<p><code>networksecurity. securityProfiles. use</code></p>
<p><code>networksecurity. serverTlsPolicies. get</code></p>
<p><code>networksecurity. serverTlsPolicies. list</code></p>
<p><code>networksecurity. serverTlsPolicies. use</code></p>
<p><code>networksecurity. tlsInspectionPolicies. get</code></p>
<p><code>networksecurity. tlsInspectionPolicies. list</code></p>
<p><code>networksecurity. tlsInspectionPolicies. use</code></p>
<p><code>networksecurity.urlLists.get</code></p>
<p><code>networksecurity.urlLists.list</code></p>
<p><code>networksecurity.urlLists.use</code></p>
<p><code>networkservices. authzExtensions. get</code></p>
<p><code>networkservices. authzExtensions. list</code></p>
<p><code>networkservices. authzExtensions. use</code></p>
<p><code>networkservices. endpointPolicies. get</code></p>
<p><code>networkservices. endpointPolicies. list</code></p>
<p><code>networkservices.gateways.get</code></p>
<p><code>networkservices.gateways.list</code></p>
<p><code>networkservices.gateways.use</code></p>
<p><code>networkservices.grpcRoutes.get</code></p>
<p><code>networkservices. grpcRoutes. list</code></p>
<p><code>networkservices. httpFilters. get</code></p>
<p><code>networkservices. httpFilters. list</code></p>
<p><code>networkservices.httpRoutes.get</code></p>
<p><code>networkservices. httpRoutes. list</code></p>
<p><code>networkservices. httpfilters. get</code></p>
<p><code>networkservices. httpfilters. list</code></p>
<p><code>networkservices. httpfilters. use</code></p>
<p><code>networkservices. lbEdgeExtensions. get</code></p>
<p><code>networkservices. lbEdgeExtensions. list</code></p>
<p><code>networkservices. lbRouteExtensions. get</code></p>
<p><code>networkservices. lbRouteExtensions. list</code></p>
<p><code>networkservices. lbTrafficExtensions. get</code></p>
<p><code>networkservices. lbTrafficExtensions. list</code></p>
<p><code>networkservices.locations.*</code></p>
<ul>
<li><code>networkservices.locations.get</code></li>
<li><code>networkservices.locations.list</code></li>
</ul>
<p><code>networkservices.meshes.get</code></p>
<p><code>networkservices.meshes.list</code></p>
<p><code>networkservices.meshes.use</code></p>
<p><code>networkservices.operations.get</code></p>
<p><code>networkservices. operations. list</code></p>
<p><code>networkservices.route_views.*</code></p>
<ul>
<li><code>networkservices. route_views. get</code></li>
<li><code>networkservices. route_views. list</code></li>
</ul>
<p><code>networkservices. serviceBindings. get</code></p>
<p><code>networkservices. serviceBindings. list</code></p>
<p><code>networkservices. serviceLbPolicies. get</code></p>
<p><code>networkservices. serviceLbPolicies. list</code></p>
<p><code>networkservices. swpSecurityExtensions. get</code></p>
<p><code>networkservices. swpSecurityExtensions. list</code></p>
<p><code>networkservices.tcpRoutes.get</code></p>
<p><code>networkservices.tcpRoutes.list</code></p>
<p><code>networkservices.tlsRoutes.get</code></p>
<p><code>networkservices.tlsRoutes.list</code></p>
<p><code>networkservices. wasmPlugins. get</code></p>
<p><code>networkservices. wasmPlugins. list</code></p>
<p><code>networkservices. wasmPlugins. use</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>servicenetworking.services.get</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
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
<td><code>hypercomputecluster. clusters. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>hypercomputecluster. clusters. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>hypercomputecluster. clusters. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>hypercomputecluster. clusters. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>hypercomputecluster. clusters. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>hypercomputecluster. locations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>hypercomputecluster. locations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>hypercomputecluster. machineLearningRuns. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>hypercomputecluster. machineLearningRuns. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>hypercomputecluster. machineLearningRuns. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>hypercomputecluster. machineLearningRuns. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>hypercomputecluster. machineLearningRuns. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>hypercomputecluster. operations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>hypercomputecluster. operations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>hypercomputecluster. operations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>hypercomputecluster. operations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
